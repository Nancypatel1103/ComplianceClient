# Interface Configuration on Master_node:

1.	Login to the UI of Master_node using the provided IP address.                                                        

  	![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/58c057cb-f18e-48b7-9fee-73eec24686b0)                

2. After login a new window will open. Go to **Network** menu.                                                        

   ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6427ccdc-bff4-4f13-81a6-83e715910497)              

3.	Navigate to the **Interfaces** menu.                                                                                 

   ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/49991c68-41df-4ceb-827a-c70235203cce)              

4.	After login a new window will open. Select and **Edit** the **eth0** interface.                                                         

   ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0b0d67c1-c405-4281-b348-99273fb802fb)            

5. Click on **Edit** and a new window will open. Fill the specified details given there.                                                                                                   
   **Protocol**:- Select Static Address in **Protocol**.                                                                                                                                   
   **Royal Switch Protocol**:- There click on **Switch Protocol**.                                                                                                                      

   ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e00c1ede-81ed-42bc-a0bf-947d0ae798b2)            

6. After clicking on switch protocol there will be another information fillup.                                                                        
   **IPv4 address**: Enter the **IPv4 address** for **Ex:192.168.1.102**.                                                                          
   **IPv4 netmask**: Select **IPv4 netmask** for **Ex: 255.255.255.0**.                                                                                                          
   **IPv4 gateway**: Enter the **IPv4 gateway** for **Ex: 192.168.1.1**.                                                                                                                   
   **IPv4 broadcast**: Enter the **IPv4 broadcast**. IPv4 broadcast comes by default.                                                                  

   ![image-6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ea148934-ffbb-4dda-9a1c-2acf2a88489d)

# Advance setting

7. Go to **Advance setting**.                                                                                         

   ![image-7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6d446c22-fbad-4894-89d1-2055eefcf704)

8. A new window will open there. Add **use custom DNS servers** there, enter and click on **plus**, it will be added.              

   ![image-8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2e1e38cb-3102-487a-b499-3057db1e7ed9)

9. Click on **Save** button. Click on **Save** button then by default you will return to interfaces menu.                 

   ![image-9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f3fee8c7-ac5c-4304-8b43-c291b5e14268)

10. Navigate down and click on **ADD NEW INTERFACE**.                       

    ![image-10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/06bc0f32-5d29-495a-977b-e68dd899ac34)

11. A new window will open. Fill the details.                                                                                           
    **Name**: Enter the **Name** for **Ex: eth 1**.                                                                                                               
    **Protocol**: Select the **Protocol** for **Ex: Static address**.                                                                                                           
    **Device**: Enter the **Device** for **Ex: eth 1**.                                                                                                                                    
     
    ![image-11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7042ae0b-739c-406c-bdaa-e9d9b5a23046)

12. Click on **CREATE INTERFACE** button.                                                                                                                                              

    ![image-12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a559587f-12e8-461c-8a0f-c887557f4696)

13. After clicking on **CREATE INTERFACE** button a new window will open. Fill the given details there.
   **IPv4 address**: Enter the **IPv4 address** for **Ex:100.100.100.1**.                                                                                                                 
   **IPv4 netmask**: Select **IPv4 netmask** for **Ex: 255.255.255.0**.                                                                                                                   
   **IPv4 gateway**: Enter the **IPv4 gateway** for **Ex: 192.168.1.1**. IPv4 gateway comes by default.                                                                                   
   **IPv4 broadcast**: Enter the **IPv4 broadcast** for **Ex: 100.100.100.255**. IPv4 broadcast comes by default.            

    ![image-13](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4d6cb6e9-0af8-4663-aff5-56da0a5357a0)

14. Click on **Save** button.
    ![image-14](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cd922595-a5b4-42ed-b877-70f9f0d77b1a)

15. Then go to the **Services** menu. Go to **Keepalived** inside the **Services** menu.

     ![image-15](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/33bbae52-8e7b-4e7f-b7f4-4e45c7ac7ed3)

16. After going to **Keepalived** a new window will open. Go to the **Globals** tab located there.

    ![image-16](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6b65aeae-f785-4606-af79-453aba9890b2)

17. Click on the **Globals** tab, then the **Keepalived Global Settings** page will open. Enter **Router_ID** where **Router ID** is given there for **Ex:- Master_node**.

    ![image-17](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b241bb72-9227-4502-8932-bc3c3f3a4769)

18. After click on **Save & Apply** button.

    ![image-18](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/3fa61536-9916-4a62-9966-50ade6297cc1)

19. Go to **IP Address** tab for **IP Address**.

    ![image-19](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/980bbcd2-3d33-4c9a-bf1f-171043b10131)

20. Click on **ADD** button.

    ![image-20](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b5dcb54c-2e9f-4c64-a33e-dcd22d749c30)

21. Fill up the details to create interface.
    **Name**: Enter the **Name** for **Ex:eth0**.                                                             
    **Address**: Enter the **Address** for **Ex:192.168.1.101**.                                            
    **Device**: Enter the **Device** for **Ex:eth0**.                                                             
    **Virtual Device Label** Enter the **Virtual Device Label** for **Ex: Ha**.                           
    **Scope**: Enter the **Scope** for **Ex:Link**.                               

    ![image-21](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8195872a-72f1-481c-99df-1c0cae076ef7)

22. Click on the **Save** button.     

     ![image-22](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c9cf1d08-6e49-4686-8ecb-54eae13da3e9)

23. Add and create eth2 interface in the same way as you created interface for eth0.
   **Name**: Enter the **Name** for **ex eth2**.                                                                         
   **Address**: Enter the **Address** for **ex 172.30.1.254**.                                                                       
   **Device**: Enter the **Device** for **ex eth2**.                                                                          
   **Virtual Device Label**:- Enter the **Virtual Device Label** for **ex: ha**.                                                    
   **Scope**:- Enter the **Scope** for **ex: link**.                                                                                    
24. After filling details click on **Save** button.                                                   
25. Click on **Interfaces** tab for **Track Interface**.                                                                     

     ![image-23](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/556cc821-0fba-4a4e-a2b0-459051e244a6)

26. After **Interfaces** a new window will open. Click on **ADD** button.

    ![image-24](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ebe223e1-5d5b-4823-bde3-6f8c4ca50468)

27. Fill the details.
    **Name**: Enter the **Name** for **Ex:eth0_ha**.
    **Device**: Enter the **Device** for **Ex:eth0**.
    **Weight**: Enter the **Weight** for **Ex:100**.

    ![image-25](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/87f83bbe-0522-4de7-8d6f-cd2bc512940a)

28. Click on **Save** button.

    ![image-26](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8cb1010f-7c0f-4e41-96b0-ea1e3f7e36ec)

> NOTE:- Same step for eth1

29. And after click **Save & Apply**.

    ![image-27](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b23355e6-4569-494d-926f-26b84ec905d1)

# Add Backup_node as a peer

30. Click on **Peers** tab.

    ![image-28](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7a4fd6a0-031f-4686-b134-07588da988cd)

31. Click on **Add** button.

    ![image-29](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7bf78193-253b-45c3-b71d-b83cfa619177)

32. Fill the details
    **Name**: Enter the **Name** for **Ex:Backup_node**.
    **Peers Address**: Select the **Peers Address**. Navigate and Select custom enter IP 100.100.100.2 and press **Enter** key.

    ![image-30](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/db9a3715-4412-483e-a703-1cab11e35e76)

33. Click on **Save** button.

    ![image-31](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bbb27b56-38d2-4868-bfda-9f04a42a5262)

34. Click on **Instance** tab **VRRP Instance**.

    ![image-32](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1b8525e3-a86a-4709-85fb-f017b324f6cc)

35. After **Instance** a new window will open. Click on **ADD** button.

    ![image-33](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bb4c4ea7-498e-46dc-9ed9-4f9617fd822e)

36. 
    


    

    
