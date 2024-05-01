# AP simulation 

## What is an AP simulation 
The process of simulating an Access Point's (AP) behavior in a network environment is known as an AP simulation. Without the requirement for actual hardware, it simulates the functions and behaviors of a physical access point (AP), enabling testing and validation of network topologies, applications, and deployments.

## Why do we need an AP simulation                                              
There are multiple reasons why an AP simulation is necessary:                                                        

- **Testing**: It lowers the possibility of mistakes or disruptions by enabling testing of network configurations and applications in a controlled environment prior to deployment.                                                                     
- **Validation**: Network configurations can be tested under a variety of scenarios for scalability, performance, and security without affecting the live environment.                                                                                                                  
- **Cost-Effectiveness**: By removing the need to buy actual hardware, simulating APs reduces expenses related to acquisition, upkeep, and space needs.                                                    
- **Convenience**: Users can simply recreate complex network scenarios and modify parameters with the simulations' flexibility and convenience.                                                

## How to Setup AP simulation 
1. First install the **Device**. After installing the device, it has to be registered manually.
2. After that, to use the internet, the **SSID and Captive Portal** have to be connected with the device, and that Captive Portal has to be connected with the **SSID**. In this way, it has to be done manually.
3. And the **simulation** is made to avoid having to do this process manually.
4. For that, go to the terminal of your server and enter the command there.
   - **Utility**:- Runs the file by testing utility.js in the package file in the utility.
   - **No of devices**:- Write the number of devices you want to add **For Example:- Device:=1**. If you enter the number of the device, it will be registered in the system first. After the proper is registered it will assign to the organization.
   - **Organization ID**:- The ID of the Organization you want to add. The device will be registered with the organization.
   - **No of SSID**:- Number of SSID you want to add. **For Example:- SSID=1**. SSID is generated after the organization is registered.
   - **No of Assigned SSID**:- Number of assigned SSID you want to add. **For Example:- Assign SSID=1**. After the captive portal is created, it will be assigned to the captive portal SSID. After the SSID is assigned, it is assigned to the SSID device.
   - **No of Assign CP**:- Number of captive portals you want to add. **For Example:- Assign CP=1**. Captive portal will be created after SSID becomes proper.

   ```
     npm run test-utility noOfDevice=1 organizationId=62d2983b3c886000327c8d39 noOfSSID=1 noOfAssignedSSID=1 noOfCP=1 noOfAssignedCP=1
   ```
   
6. After giving the command, if you look in the terminal, it will send a **keepalive** request.
7. After that, if you look at the server, the device is connected and online.
8. Until you click ctrl+c, the **keepalive** request will be sent to the terminal and the device will remain online until then.
9. When you click ctrl+c then the **keepalive** request will stop sending and the device will go offline.











































































































































