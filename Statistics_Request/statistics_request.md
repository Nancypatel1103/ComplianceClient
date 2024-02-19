# Statistics Request

When the Device is registered, after going through the Assigned, after going through the deviceId and authToken matchup, the Device would make a Keepalive request for whether the device is on or off. if keepalive has a statistics event trigger then Device would make a statistics request.

Use of Statistics Request

- For statistics update

## InfiniteClouds config API

InfiniteClouds platform provides a POST request API to send register requests.
```
https://devicapi.elemprin.com/v1/device/registration    
or
https://devapi.gwcwifi.com/v1/device/registration

```
Request Body
```json
{
  "statusType": "statistics",
  "deviceId": "65d3244c32a7e60074663212",
  "deviceType": "CE",
  "machineId": "c4:4b:d1:00:81:c9",
  "macAddress": "c4:4b:d1:00:81:c8",
  "timestamp": 1708303849,
  "nicCount": 9,
  "cpuCount": 0,
  "remoteSites": [],
  "system": {
    "uptime": 187220,
    "memoryUsage": 24.89,
    "cpuUsage": 2
  },
  "firmware": {
    "currentVersion": "v1.12.2",
    "upgrading": ""
  },
  "config": {
    "revisionId": "df10799f-a699-487c-a39f-e92bf9eaa791"
  },
  "commands": [],
  "interfaces": [
    {
      "name": "br-lan",
      "interfaceName": "br-lan",
      "addresses": [
        {
          "address": "192.168.60.1",
          "netmask": "255.255.255.0"
        }
      ],
      "statistics": {
        "txPackets": 0,
        "rxPackets": 0,
        "txBytes": 0,
        "rxBytes": 0,
        "txDropped": 0,
        "rxDropped": 0,
        "txErrors": 0,
        "rxErrors": 0
      },
      "carrier": false,
      "operstate": false,
      "connected": false
    },
    {
      "name": "br-wan",
      "interfaceName": "br-wan",
      "addresses": [
        {
          "address": "192.168.111.3",
          "netmask": "255.255.255.0"
        }
      ],
      "statistics": {
        "txPackets": 99,
        "rxPackets": 560,
        "txBytes": 19094,
        "rxBytes": 51846,
        "txDropped": 0,
        "rxDropped": 0,
        "txErrors": 0,
        "rxErrors": 0
      },
      "carrier": true,
      "operstate": true,
      "connected": false
    },
    {
      "name": "eth0",
      "interfaceName": "eth0",
      "addresses": [],
      "statistics": {
        "txPackets": 0,
        "rxPackets": 0,
        "txBytes": 0,
        "rxBytes": 0,
        "txDropped": 0,
        "rxDropped": 0,
        "txErrors": 0,
        "rxErrors": 0
      },
      "carrier": false,
      "operstate": false,
      "connected": false
    },
    {
      "name": "eth1",
      "interfaceName": "eth1",
      "addresses": [],
      "statistics": {
        "txPackets": 0,
        "rxPackets": 0,
        "txBytes": 0,
        "rxBytes": 0,
        "txDropped": 0,
        "rxDropped": 0,
        "txErrors": 0,
        "rxErrors": 0
      },
      "carrier": false,
      "operstate": false,
      "connected": false
    },
    {
      "name": "eth2",
      "interfaceName": "eth2",
      "addresses": [],
      "statistics": {
        "txPackets": 0,
        "rxPackets": 0,
        "txBytes": 0,
        "rxBytes": 0,
        "txDropped": 0,
        "rxDropped": 0,
        "txErrors": 0,
        "rxErrors": 0
      },
      "carrier": false,
      "operstate": false,
      "connected": false
    },
    {
      "name": "eth3",
      "interfaceName": "eth3",
      "addresses": [],
      "statistics": {
        "txPackets": 99,
        "rxPackets": 578,
        "txBytes": 19468,
        "rxBytes": 63931,
        "txDropped": 0,
        "rxDropped": 0,
        "txErrors": 0,
        "rxErrors": 0
      },
      "carrier": true,
      "operstate": true,
      "connected": false
    },
    {
      "name": "eth4",
      "interfaceName": "eth4",
      "addresses": [],
      "statistics": {
        "txPackets": 0,
        "rxPackets": 0,
        "txBytes": 0,
        "rxBytes": 0,
        "txDropped": 0,
        "rxDropped": 0,
        "txErrors": 0,
        "rxErrors": 0
      },
      "carrier": false,
      "operstate": false,
      "connected": false
    },
    {
      "name": "eth5",
      "interfaceName": "eth5",
      "addresses": [],
      "statistics": {
        "txPackets": 0,
        "rxPackets": 0,
        "txBytes": 0,
        "rxBytes": 0,
        "txDropped": 0,
        "rxDropped": 0,
        "txErrors": 0,
        "rxErrors": 0
      },
      "carrier": false,
      "operstate": false,
      "connected": false
    },
    {
      "name": "wifi0",
      "interfaceName": "wifi0",
      "addresses": [],
      "statistics": {
        "txPackets": 0,
        "rxPackets": 0,
        "txBytes": 0,
        "rxBytes": 0,
        "txDropped": 0,
        "rxDropped": 0,
        "txErrors": 0,
        "rxErrors": 0
      },
      "carrier": true,
      "operstate": false,
      "connected": false
    },
    {
      "name": "wifi1",
      "interfaceName": "wifi1",
      "addresses": [],
      "statistics": {
        "txPackets": 0,
        "rxPackets": 0,
        "txBytes": 0,
        "rxBytes": 0,
        "txDropped": 0,
        "rxDropped": 0,
        "txErrors": 0,
        "rxErrors": 0
      },
      "carrier": true,
      "operstate": false,
      "connected": false
    }
  ]
}

```

Response Body
``` json
{
  "data": {
    "triggerevent": {
      "configupdate": false,
      "firmwareupdate": false,
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
    "triggerevent": {
      "configupdate": true,
      "firmwareupdate": false,
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
## Device config Request

Before calling the status API, the Device generates a status request body by generating required data like  MAC Address, Machine ID, and Interfaces list into a file called `/tmp/last_config_request.json`

The `Statistics` request can be tested using the `curl` command. You can take Request Body as a reference and change values as per your need.
The curl command is found in the main script /usr/bin/cgw_config.sh. 
```bash
```
## Device Backend Process


Endpoint Request Body: `/tmp/last_statistics_request.json`

Endpoint Response Body: `/tmp/last_statistics_response.json `
