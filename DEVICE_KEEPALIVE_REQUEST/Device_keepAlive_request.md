# Device-Cloud Communication
# KeepAvlive Request

When the Device is registered, after going through the Assigned, after going through the deviceId and authToken matchup, the Device would make a Keepalive request for whether the device is on or off. 

Use of Keepalive Request

- trigger event for config update, firmware update, and status check on or off.

## InfiniteClouds KeepAlive API

InfiniteClouds platform provides a POST request API to send keepalive request.

```HTTP
https://devicapi.elemprin.com/v1/device/registration 
or
https://devapi.gwcwifi.com/v1/device/registration
```
Request Body
```json
{
  "statusType": "keepAlive",
  "deviceId": "6593d5d8d9f18000481a4aa9",
  "deviceType": "CE",
  "machineId": "c4:4b:d1:a0:32:c2",
  "macAddress": "c4:4b:d1:a0:32:c1",
  "timestamp": 1704472804,
  "config": {
    "revisionId": "a65d5d43-0fb5-4416-b42e-de16f5537aec"
  }
}
```
Response Body 

```json
{
  "data": {
    "triggerEvent": {
      "configUpdate": false,
      "firmwareUpdate": false,
      "commands": []
    }
  },
  "message": "success",
  "status": 200,
  "errors": false,
  "httpCode": 200,
  "errorCode": 0
}
```
Response Body when config and firmware update. 
```json
{
  "data": {
    "triggerEvent": {
      "configUpdate": true,
      "firmwareUpdate": true,
      "commands": []
    }
  },
  "message": "success",
  "status": 200,
  "errors": false,
  "httpCode": 200,
  "errorCode": 0
}
```
> Here is the config update it will be true only when some changes are made in cloud-config.                   
> When a device is not assigned to any user, it does not receive an authToken. The authToken is used to authorize devices for subsequent communication to other APIs.

## Device KeepAlive Request
Before calling Keepalive API, the Device generates the keepalive request body by generating required data like  MAC Address, Machine ID, and Interfaces list into a file called `/tmp/last_keepAlive_request.json`

The `keepAlive` request can be tested using the `curl` command. You can take Request Body as a reference and change values as per your need.
The curl command is found in the main script /usr/bin/gwc_keepalive.sh. Without authToken and device id command not running. Device id and authToken are found in `/tmp/last_register_response.json`.

``` bash
curl -k -H 'Content-Type: application/json' -H 'Authorization: Bearer eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiI2NDExNmQzYWU1Mjg2NTU5MTViNmU0NWI6OmNlOjo2MGZiNDQ
3OS1jMzkzLTMzOTgtODM2Zi1lZjUzMWU4OWM5MWY6OjA4OjAwOjI3Ojk1OmEzOjY1IiwiaWF0IjoxNjc4ODgyNTA2LCJleHAiOjE2Nzg4ODYxMDZ9.SfPP8U0D6CCOTH0ZAjIKxyoGf_r9KrvmiWP_41jcV-0dKmblLYOtfa
v2rlV9dSr7RQUj1liB6bCxACFn8jDWRQ' -d @/tmp/last_keepAlive_request.json https://devapi.gwcwifi.com/v1/device/registration

{"triggerEvent":{"configUpdate":false,"firmwareUpdate":false,"sendStatus":false,"commands":null}}
```
## Device Backend Process
InfiniteClouds Device runs a few services to communicate with InfiniteClouds. One such service is the `keepAlive` service.

Start Register Service:`/etc/init.d/keepalive start`

Stop Register Service: `/etc/init.d/keepalive stop`

Check Register Service `/etc/init.d/keepalive status`

The `keepalive` service Device takes care of two jobs.
1. get a status check of devices
2. trigger when config and firmware update 

The device also stored keepAlive requests and responses in files.

Endpoint Request Body: `/tmp/last_keepAlive_request.json`

Endpoint Response Body: `/tmp/last_keepAlive_response.json`
