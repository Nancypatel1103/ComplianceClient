# AP-UTILITY-TOOL-CHECKING

## Register Request
When CE completed CE to Hub Communication, by that time, It would have an endpoint. Using `endpoint`, CE would make a register request.

Use of Register Request
- Report CE for the first time to the Cloud
- Get an authentication token from the cloud for communication

## InfiniteClouds Register API
InfiniteClouds platform provides a POST request API to send register requests.

```HTTP          
https://devicapi.elemprin.com/v1/device/registration    
or
https://devapi.gwcwifi.com/v1/device/registration
```
Request Body
```json
{
  "deviceType": "CE",
  "machineId": "c4:4b:d1:a0:32:c2",
  "macAddress": "c4:4b:d1:a0:32:c1",
  "timestamp": 1704397435,
  "deviceMetaInfo": {
    "deviceType": "CE",
    "deviceModel": "Infinite_110"
  },
  "firmware": {
    "currentVersion": "v1.11.1",
    "upgrading": ""
  },
  "interfaces": [
    {
      "name": "ath00",
      "interfaceName": "ath00",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID7",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 5.785,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 157,
        "ifname": "ath00",
        "mode": "Master",
        "bssid": "c4:4b:d1:a0:32:c6",
        "quality": 43
      }
    },
    {
      "name": "ath01",
      "interfaceName": "ath01",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID9",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 5.785,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 157,
        "ifname": "ath01",
        "mode": "Master",
        "bssid": "ca:4b:d1:a0:32:c6",
        "quality": 43
      }
    },
    {
      "name": "ath02",
      "interfaceName": "ath02",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID10",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 5.785,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 157,
        "ifname": "ath02",
        "mode": "Master",
        "bssid": "ce:4b:d1:a0:32:c6",
        "quality": 43
      }
    },
    {
      "name": "ath03",
      "interfaceName": "ath03",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID11",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 5.785,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 157,
        "ifname": "ath03",
        "mode": "Master",
        "bssid": "d2:4b:d1:a0:32:c6",
        "quality": 43
      }
    },
    {
      "name": "ath04",
      "interfaceName": "ath04",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID12",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 5.785,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 157,
        "ifname": "ath04",
        "mode": "Master",
        "bssid": "d6:4b:d1:a0:32:c6",
        "quality": 43
      }
    },
    {
      "name": "ath05",
      "interfaceName": "ath05",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID13",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 5.785,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 157,
        "ifname": "ath05",
        "mode": "Master",
        "bssid": "da:4b:d1:a0:32:c6",
        "quality": 43
      }
    },
    {
      "name": "ath06",
      "interfaceName": "ath06",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID14",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 5.785,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 157,
        "ifname": "ath06",
        "mode": "Master",
        "bssid": "de:4b:d1:a0:32:c6",
        "quality": 43
      }
    },
    {
      "name": "ath07",
      "interfaceName": "ath07",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID15",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 5.785,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 157,
        "ifname": "ath07",
        "mode": "Master",
        "bssid": "e2:4b:d1:a0:32:c6",
        "quality": 43
      }
    },
    {
      "name": "ath10",
      "interfaceName": "ath10",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID1",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 2.462,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 11,
        "ifname": "ath10",
        "mode": "Master",
        "bssid": "ca:4b:d1:a0:32:c7",
        "quality": 8
      }
    },
    {
      "name": "ath11",
      "interfaceName": "ath11",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID_2",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 2.462,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 11,
        "ifname": "ath11",
        "mode": "Master",
        "bssid": "c4:4b:d1:a0:32:c7",
        "quality": 8
      }
    },
    {
      "name": "ath12",
      "interfaceName": "ath12",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID_3",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 2.462,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 11,
        "ifname": "ath12",
        "mode": "Master",
        "bssid": "ce:4b:d1:a0:32:c7",
        "quality": 8
      }
    },
    {
      "name": "ath13",
      "interfaceName": "ath13",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID4",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 2.462,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 11,
        "ifname": "ath13",
        "mode": "Master",
        "bssid": "d2:4b:d1:a0:32:c7",
        "quality": 8
      }
    },
    {
      "name": "ath14",
      "interfaceName": "ath14",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID5",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 2.462,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 11,
        "ifname": "ath14",
        "mode": "Master",
        "bssid": "d6:4b:d1:a0:32:c7",
        "quality": 8
      }
    },
    {
      "name": "ath15",
      "interfaceName": "ath15",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "SSID6",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 2.462,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 11,
        "ifname": "ath15",
        "mode": "Master",
        "bssid": "da:4b:d1:a0:32:c7",
        "quality": 8
      }
    },
    {
      "name": "ath16",
      "interfaceName": "ath16",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "gcw-nadiad",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "WPA2 PSK (CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 2,
          "pair_ciphers": [
            "CCMP"
          ],
          "group_ciphers": [
            "CCMP"
          ]
        },
        "frequency": 2.462,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 11,
        "ifname": "ath16",
        "mode": "Master",
        "bssid": "de:4b:d1:a0:32:c7",
        "quality": 8
      }
    },
    {
      "name": "ath17",
      "interfaceName": "ath17",
      "addresses": [],
      "wireless": {
        "noise": -98,
        "ssid": "nadiad-testing",
        "country": "BH",
        "assoclist": {},
        "encyption": {
          "enabled": true,
          "auth_algs": {},
          "description": "mixed WPA/WPA2 PSK (TKIP, CCMP)",
          "wep": false,
          "auth_suites": [
            "PSK"
          ],
          "wpa": 3,
          "pair_ciphers": [
            "TKIP",
            "CCMP"
          ],
          "group_ciphers": [
            "TKIP"
          ]
        },
        "frequency": 2.462,
        "bitrate": 286,
        "txpower": 1,
        "signal": 1,
        "channel": 11,
        "ifname": "ath17",
        "mode": "Master",
        "bssid": "e2:4b:d1:a0:32:c7",
        "quality": 8
      }
    },
    {
      "name": "br-ath00",
      "interfaceName": "br-ath00",
      "addresses": [
        {
          "address": "192.168.18.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath01",
      "interfaceName": "br-ath01",
      "addresses": [
        {
          "address": "192.168.7.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath02",
      "interfaceName": "br-ath02",
      "addresses": [
        {
          "address": "192.168.5.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath03",
      "interfaceName": "br-ath03",
      "addresses": [
        {
          "address": "192.168.13.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath04",
      "interfaceName": "br-ath04",
      "addresses": [
        {
          "address": "192.168.14.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath05",
      "interfaceName": "br-ath05",
      "addresses": [
        {
          "address": "192.168.15.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath06",
      "interfaceName": "br-ath06",
      "addresses": [
        {
          "address": "192.168.16.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath07",
      "interfaceName": "br-ath07",
      "addresses": [
        {
          "address": "192.168.17.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath10",
      "interfaceName": "br-ath10",
      "addresses": [
        {
          "address": "192.168.12.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath11",
      "interfaceName": "br-ath11",
      "addresses": [
        {
          "address": "192.168.11.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath12",
      "interfaceName": "br-ath12",
      "addresses": [
        {
          "address": "192.168.9.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath13",
      "interfaceName": "br-ath13",
      "addresses": [
        {
          "address": "192.168.8.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath14",
      "interfaceName": "br-ath14",
      "addresses": [
        {
          "address": "192.168.2.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath15",
      "interfaceName": "br-ath15",
      "addresses": [
        {
          "address": "192.168.3.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-ath17",
      "interfaceName": "br-ath17",
      "addresses": [
        {
          "address": "192.168.10.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-lan",
      "interfaceName": "br-lan",
      "addresses": [
        {
          "address": "192.168.99.1",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "br-wan",
      "interfaceName": "br-wan",
      "addresses": [
        {
          "address": "192.168.1.3",
          "netmask": "255.255.255.0"
        }
      ]
    },
    {
      "name": "eth0",
      "interfaceName": "eth0",
      "addresses": []
    },
    {
      "name": "eth1",
      "interfaceName": "eth1",
      "addresses": []
    },
    {
      "name": "eth2",
      "interfaceName": "eth2",
      "addresses": []
    },
    {
      "name": "eth3",
      "interfaceName": "eth3",
      "addresses": []
    },
    {
      "name": "wifi0",
      "interfaceName": "wifi0",
      "addresses": [],
      "htmodelist": [
        "HT20",
        "HT40",
        "HT80"
      ],
      "channellist": [
        {
          "channel": 36,
          "frequency": "5.180"
        },
        {
          "channel": 40,
          "frequency": "5.200"
        },
        {
          "channel": 44,
          "frequency": "5.220"
        },
        {
          "channel": 48,
          "frequency": "5.240"
        },
        {
          "channel": 52,
          "frequency": "5.260"
        },
        {
          "channel": 56,
          "frequency": "5.280"
        },
        {
          "channel": 60,
          "frequency": "5.300"
        },
        {
          "channel": 64,
          "frequency": "5.320"
        },
        {
          "channel": 149,
          "frequency": "5.745"
        },
        {
          "channel": 153,
          "frequency": "5.765"
        },
        {
          "channel": 157,
          "frequency": "5.785"
        },
        {
          "channel": 161,
          "frequency": "5.805"
        },
        {
          "channel": 165,
          "frequency": "5.825"
        }
      ],
      "txpowerlist": {
        "1000": 30,
        "794": 29,
        "630": 28,
        "501": 27,
        "398": 26,
        "316": 25,
        "251": 24,
        "199": 23,
        "158": 22,
        "125": 21,
        "100": 20,
        "79": 19,
        "63": 18,
        "50": 17,
        "39": 16,
        "31": 15,
        "25": 14,
        "19": 13,
        "15": 12,
        "12": 11,
        "10": 10,
        "7": 9,
        "6": 8,
        "5": 7,
        "3": 5,
        "2": 4,
        "1": 1
      },
      "bandlist": [
        "5GHz"
      ],
      "channel": 36,
      "htmode": "HT20",
      "txpower": 1,
      "country": 48,
      "band": "5GHz"
    },
    {
      "name": "wifi1",
      "interfaceName": "wifi1",
      "addresses": [],
      "htmodelist": [
        "HT20",
        "HT40"
      ],
      "channellist": [
        {
          "channel": 1,
          "frequency": "2.412"
        },
        {
          "channel": 2,
          "frequency": "2.417"
        },
        {
          "channel": 3,
          "frequency": "2.422"
        },
        {
          "channel": 4,
          "frequency": "2.427"
        },
        {
          "channel": 5,
          "frequency": "2.432"
        },
        {
          "channel": 6,
          "frequency": "2.437"
        },
        {
          "channel": 7,
          "frequency": "2.442"
        },
        {
          "channel": 8,
          "frequency": "2.447"
        },
        {
          "channel": 9,
          "frequency": "2.452"
        },
        {
          "channel": 10,
          "frequency": "2.457"
        },
        {
          "channel": 11,
          "frequency": "2.462"
        },
        {
          "channel": 12,
          "frequency": "2.467"
        },
        {
          "channel": 13,
          "frequency": "2.472"
        }
      ],
      "txpowerlist": {
        "1000": 30,
        "794": 29,
        "630": 28,
        "501": 27,
        "398": 26,
        "316": 25,
        "251": 24,
        "199": 23,
        "158": 22,
        "125": 21,
        "100": 20,
        "79": 19,
        "63": 18,
        "50": 17,
        "39": 16,
        "31": 15,
        "25": 14,
        "19": 13,
        "15": 12,
        "12": 11,
        "10": 10,
        "7": 9,
        "6": 8,
        "5": 7,
        "3": 5,
        "2": 4,
        "1": 1
      },
      "bandlist": [
        "2GHz"
      ],
      "channel": 1,
      "htmode": "HT20",
      "txpower": 1,
      "country": 48,
      "band": "2GHz"
    }
  ]
}
```
Response Body when the Device is already assigned to the User
```json
{
  "data": {
    "assigned": true,
    "authToken": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJkZXZpY2VEYXRhIjp7Im1hY0FkZHJlc3MiOiJjNDo0YjpkMTphMDozMjpjMSIsImRldmljZUlkIjoiNjU5M2Q1ZDhkOWYxODAwMDQ4MWE0YWE5In0sImlhdCI6MTcwNzk5OTE0OCwiZXhwIjoxNzA4MDAyNzQ4LCJhdWQiOiJsb2NhbGhvc3QiLCJpc3MiOiJsb2NhbGhvc3QifQ.JH354IQ2UqzJDEJNNJgRunfWRTYdCJ9lpyg1iop_AJw",
    "deviceId": "6593d5d8d9f18000481a4aa9",
    "port": 21428,
    "tokenExpiry": "3600",
    "type": "Bearer"
  },
  "message": "Device is already exists with same mac address",
  "status": 200,
  "errors": false,
  "httpCode": 200,
  "errorCode": 0
}
```
> When CE is not assigned to any user. Then it doesn't get an authentication token. Authtoken is used to authorize CE devices for subsequent communication with other APIs.

