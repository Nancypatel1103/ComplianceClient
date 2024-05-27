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
1. First download the test utility on your PC.
2. After downloading give command in terminal. 
  `pwd`
3. Run the **pwd** command then **cloud-ms-test-utility** will show and copy and open that folder.
4. Then enter a command again in the terminal. Give command and enter.
   `code .`
5. Enter then **Visual Studio Code** will open.
6. Then make the given changes in the image in the **.env and .env local** files given in it. **API URL** is given here for example **https://devicapi.elemprin.com/vi/** Enter your API URL in its place.
   `Note:- Here you have to enter the address of the server`
    ![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/33e65930-b7d0-4fb6-843c-e1ab8d6d4f4e)

7. Then install the **Device**. After installing the device, it has to be registered manually.
8. After that, to use the internet, the **SSID and Captive Portal** have to be connected with the device, and that Captive Portal has to be connected with the **SSID**. In this way, it has to be done manually.
9. And the **simulation** is made to avoid having to do this process manually.
10. For that, go to the terminal of your server and enter the command there.
   - **Utility**:- Runs the file by testing utility.js in the package file in the utility.
   - **No of devices**:- Write the number of devices you want to add **For Example:- Device:=1**. If you enter the number of the device, it will be registered in the system first. After the proper is registered it will assign to the organization.
   - **Organization ID**:- The ID of the Organization you want to add. The device will be registered with the organization. Copy the ID shown in the image in the organization ID and paste it here. For that ID, go to the organization and click on the edit button of your organization name, it will open as shown in the image, and copy the ID shown in it.
   
      ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1825b024-5933-49c5-9f38-a0245e8d13cf)

   - **No of SSID**:- Number of SSID you want to add. **For Example:- SSID=1**. SSID is generated after the organization is registered.
   - **No of Assigned SSID**:- Number of assigned SSID you want to add. **For Example:- Assign SSID=1**. After the captive portal is created, it will be assigned to the captive portal SSID. After the SSID is assigned, it is assigned to the SSID device.
   - **No of Assign CP**:- Number of captive portals you want to add. **For Example:- Assign CP=1**. Captive portal will be created after SSID becomes proper.

   ```
     npm run test-utility noOfDevice=1 organizationId=62d2983b3c886000327c8d39 noOfSSID=1 noOfAssignedSSID=1 noOfCP=1 noOfAssignedCP=1
   ```
   
11. After giving the command, if you look in the terminal, it will send a **keepalive** request.
12. After that, if you look at the server, the device is connected and online.
13. Until you click ctrl+c, the **keepalive** request will be sent to the terminal and the device will remain online until then.
14. When you click ctrl+c then the **keepalive** request will stop sending and the device will go offline.












































































































































