# AP Utility Tool Checking

## How to access AP when it's not registered
- First configure it. To configure, connect the router to the access point with a **LAN** cable.
- After connecting with the **LAN** cable, access the router.
- After accessing check if its IP comes or not go inside its device to check.
- If you go to a **LAN** device you will get the **MAC** address of the device and get the **WAN IP** which will be given by the router.
- It will give the **WAN IP** of the device only when it is connected. Access if by connecting to **WAN IP**.
- Then give the **WAN IP** there so that it will access the access point.
- After connecting you will get **WAN** and **LAN IP**.

## Access over default SSID after connecting to default SSID
- **SSID** is not present by default when connecting a device.
- If there is no **SSID** by default, Wi-Fi Connect will have a generic **SSID**. connect there **GWC and Infinite**. For **ex:- GWC-A032C1-5G and GWC-A032C1-2.4G** .
- This way you will see the **SSID**. In its password, the device that says **A032C1** will have 0-0 before and after it. such as **0A032C10**.   

   ![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8c5b8b94-569d-4a66-ade9-5e9aa61d567a)


## Access over ethernet over an IP Address
- command:- ` ssh 192.168.60.1`
- Ping command:- `ping 192.168.111.3`

```
PING 192.168.111.3 (192.168.111.3): 56 data bytes
64 bytes from 192.168.111.3: seq=0 ttl=64 time=0.280 ms    
64 bytes from 192.168.111.3: seq=1 ttl=64 time=0.130 ms       
64 bytes from 192.168.111.3: seq=2 ttl=64 time=0.149 ms      
64 bytes from 192.168.111.3: seq=3 ttl=64 time=0.161 ms           
64 bytes from 192.168.111.3: seq=4 ttl=64 time=0.159 ms       
64 bytes from 192.168.111.3: seq=5 ttl=64 time=0.132 ms         
64 bytes from 192.168.111.3: seq=6 ttl=64 time=0.171 ms      
64 bytes from 192.168.111.3: seq=7 ttl=64 time=0.163 ms     
64 bytes from 192.168.111.3: seq=8 ttl=64 time=0.153 ms     
64 bytes from 192.168.111.3: seq=9 ttl=64 time=0.163 ms       
64 bytes from 192.168.111.3: seq=10 ttl=64 time=0.223 ms      
64 bytes from 192.168.111.3: seq=11 ttl=64 time=0.126 ms        
^C    
--- 192.168.111.3 ping statistics ---            
12 packets transmitted, 12 packets received, 0% packet loss          
round-trip min/avg/max = 0.126/0.167/0.280 ms       
```
- UI login:-            

   To log into the UI, it is necessary to provide the IP of the AP in the browser. If you give the IP of the AP, the login page will open.
  ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bd83b5cf-a38c-4d42-8fdc-a254d822bcaf)


# Client to Wi-Fi Authentication Failure

## Check AP logs from AP native UI or command line using a command.
When a client connects to an AP, the device requires it to be connected to the device mobile. Then to check the log it has to be disconnected i.e. offline. Then the following command will be used to check the log.

AP native UI Body:- `logread `              
AP native UI for Message Body:- `logread -f `          

