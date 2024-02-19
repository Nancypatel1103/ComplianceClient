# Config-Request

When the Device is registered, after going through the Assigned, after going through the deviceId and authToken matchup, the Device would make a Keepalive request for whether the device is on or off. if keepalive has a config event trigger then Device would make a config request.

Use of config Request

- For config update 

## InfiniteClouds config API

InfiniteClouds platform provides a POST request API to send register requests.

``` HTTP
https://devicapi.elemprin.com/v1/device/registration    
or
https://devapi.gwcwifi.com/v1/device/registration

```
Request Body
```json
```

Response Body status send 
```json
{
  "data": {
    "radios": [
      {
        "interfaceName": "wifi0",
        "wirelessNetworks": [
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": false,
              "tag": null
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "6596b9c62f3a2a004872059d",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID7",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": true,
              "upload": 1000000,
              "download": 1000000
            },
            "addresses": [
              {
                "address": "192.168.18.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath00"
          },
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": false,
              "tag": null
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "65952285788ae8004967b2a3",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID9",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [
              {
                "address": "192.168.7.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath01"
          },
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": "657db4d044b161004928d754",
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": false,
              "tag": null
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "65963ad936c23a004af455c9",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID10",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [
              {
                "address": "192.168.5.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [
              "facebook.com",
              "fbcdn.net",
              "facebook.net",
              "akamaihd.net",
              "cdnjs.cloudflare.com",
              "static.xx.fbcdn.net",
              "twitter.com",
              "api.twitter.com",
              "twimg.com",
              "google.com",
              "www.google.com",
              "clients1.google.com",
              "accounts.youtube.com",
              "accounts.google.com",
              "ssl.gstatic.com",
              "ssl.google-analytics.com",
              "googleusercontent.com",
              "gwcwifi.com",
              "play.google.com",
              "accounts.google.co.in",
              "www.gstatic.com",
              "whatsapp.com"
            ],
            "captivePortalHost": "devhotspot.gwcwifi.com",
            "interfaceName": "ath02"
          },
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": false,
              "tag": null
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "65963b1e36c23a004af456e4",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID11",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [
              {
                "address": "192.168.13.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath03"
          },
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": false,
              "tag": null
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "65963b4636c23a004af4578a",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID12",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [
              {
                "address": "192.168.14.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath04"
          },
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": false,
              "tag": null
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "65963bcd36c23a004af45a21",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID13",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [
              {
                "address": "192.168.15.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath05"
          },
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": false,
              "tag": null
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "65963c0936c23a004af45b40",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID14",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [
              {
                "address": "192.168.16.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath06"
          },
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": false,
              "tag": null
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "65963cb236c23a004af45ece",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID15",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [
              {
                "address": "192.168.17.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath07"
          }
        ],
        "htmode": "HT20",
        "channel": 157,
        "txPower": 1,
        "band": "5GHz",
        "country": 356
      },
      {
        "interfaceName": "wifi1",
        "wirelessNetworks": [
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": true,
              "tag": 100
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "65951c82788ae800496794de",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID1",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [
              {
                "address": "192.168.12.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath10"
          },
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": false,
              "tag": null
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "65951fc7788ae8004967a4b9",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID_2",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [
              {
                "address": "192.168.11.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath11"
          },
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": true,
              "tag": 101
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "65951ffb788ae8004967a5e5",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID_3",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [
              {
                "address": "192.168.9.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath12"
          },
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": true,
              "tag": 100
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "65952027788ae8004967a6ad",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID4",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [
              {
                "address": "192.168.8.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath13"
          },
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": false,
              "tag": null
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "65952082788ae8004967a84b",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID5",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [
              {
                "address": "192.168.2.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath14"
          },
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": false,
              "tag": null
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "659520d7788ae8004967a9dd",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "SSID6",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [
              {
                "address": "192.168.3.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath15"
          },
          {
            "hidden": false,
            "configType": "bridge",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk2",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": false,
              "tag": null
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "65809ae244b16100493020c1",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "gcw-nadiad",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad24",
            "bandwidthLimit": {
              "enable": false
            },
            "addresses": [],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath16"
          },
          {
            "hidden": false,
            "configType": "route",
            "captivePortalId": null,
            "saeRequireMfp": false,
            "wmm": true,
            "isolate": false,
            "sae": false,
            "saePwe": false,
            "encryption": "psk",
            "cipher": "",
            "macPolicy": "disable",
            "bandSteering": false,
            "fastRoaming": false,
            "vlan": {
              "enable": false,
              "tag": null
            },
            "wlanSchedule": {
              "enable": false
            },
            "macFilterList": [],
            "igmp": false,
            "_id": "6580509244b16100492f7179",
            "authServer": null,
            "authServerPort": null,
            "status": false,
            "ssid": "nadiad-testing",
            "organizationId": "655b605abb005a0049126beb",
            "key": "sharad121",
            "bandwidthLimit": {
              "enable": true,
              "upload": 1000000,
              "download": 1000000
            },
            "addresses": [
              {
                "address": "192.168.10.1",
                "netmask": "255.255.255.0"
              }
            ],
            "deviceData": [],
            "whitelistDomains": [],
            "interfaceName": "ath17"
          }
        ],
        "htmode": "HT20",
        "channel": 0,
        "txPower": 1,
        "band": "2GHz",
        "country": 356
      }
    ],
    "_id": "6593d5d8d9f18000481a4aa9",
    "deviceName": "sharad device",
    "macAddress": "c4:4b:d1:a0:32:c1",
    "machineId": "c8da3b42-66aa-6b31-ab58-b7fcc744730f",
    "port": 21428,
    "createdAt": "2024-01-02T09:22:32.845Z",
    "updatedAt": "2024-02-19T07:03:03.094Z",
    "__v": 0,
    "assignedAt": "2024-01-02T09:23:15.439Z",
    "organizationId": "655b605abb005a0049126beb",
    "revisionId": "2f094820-07ee-4453-af69-fd960059f656",
    "upnp": {
      "enable": true
    },
    "firewall": {
      "dnat": []
    },
    "airtimeFairness": {
      "enable": true
    },
    "appDetection": {
      "enable": true
    },
    "rogueApDetection": {
      "enable": true
    },
    "snmp": {
      "enable": false,
      "hostName": "sharad",
      "location": "nadiad",
      "version": "v1",
      "community": "testing",
      "contact": "sharad@elemprin.com",
      "port": "161",
      "description": "1331"
    },
    "syslog": {
      "enable": false,
      "server": "1.1.1.1",
      "protocol": "tcp",
      "port": "121"
    },
    "firmwareSchedule": {
      "enable": false
    }
  },
  "message": "success",
  "status": 200,
  "errors": false,
  "httpCode": 200,
  "errorCode": 0
}

```
> When the device is not assigned to any user. So there it doesn't get authToken. The autoToken is used to authorize the device for subsequent communication with other APIs

## Device config Request

Before calling the status API, the Device generates a status request body by generating required data like  MAC Address, Machine ID, and Interfaces list into a file called `/tmp/last_config_request.json`

`config` request can be tested using the `curl` command. You can take Request Body as a reference and change values as per your need.
The curl command is found in the main script /usr/bin/cgw_config.sh. add  some entries in the command like device id,authToken, in URL add config?deviceType=CE&revisionID=0. 

```bash
```
## Device Backend Process


Endpoint Request Body: `/tmp/last_config_request.json`

Endpoint Response Body: `/tmp/last_config_response.json`




