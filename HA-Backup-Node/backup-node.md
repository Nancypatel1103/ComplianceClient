# Interface Configuration on Backup_node:

1.	Login to the UI of Master_node using the provided IP address.                                                                                                          

  	![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/dea0fb31-1c67-494c-969d-e13deb067786)               

2. After login a new window will open. Go to the **Network** menu.                                                                                             

    ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fac55ed4-4994-4085-97e6-e3c066b33d9b)

3.	Navigate to the **Interfaces** menu.                                                                                                                                               

   ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5dc59558-8977-43f0-ba86-44bb8eae501f)
            

4.	After login a new window will open. Select and **Edit** the **eth0** interface.                                                                                     

   ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1003ded5-5d5b-4817-9da9-12f0e5b9b165)           

5. Click on **Edit** and a new window will open. Fill in the specified details given there.                                                                                                   
   **Protocol**:- Select Static Address in **Protocol**.                                                                                                                                  
   **Royal Switch Protocol**:- There click on **Switch Protocol**.                                                                                                                         
   ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ca057636-4c49-4c92-8634-bfdae5b017f6)

6. After clicking on switch protocol there will be another information fillup.                                                                        
   **IPv4 address**: Enter the **IPv4 address** for **Ex:192.168.1.103**.                                                                          
   **IPv4 netmask**: Select **IPv4 netmask** for **Ex: 255.255.255.0**.                                                                                                          
   **IPv4 gateway**: Enter the **IPv4 gateway** for **Ex: 192.168.1.1**.                                                                                                                  
   **IPv4 broadcast**: Enter the **IPv4 broadcast**. IPv4 broadcast comes by default.                                                                  

   ![image-6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/3eb1db0a-8e62-4815-8765-acbcc503f1f0)


# Advance setting

7. Go to **Advance setting**.                                                                                         

   ![image-7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/57cbdbc7-41fe-4c69-98ce-e5bacb6aeb80)


8. A new window will open there. Add **use custom DNS servers** there, enter and click on **plus**, it will be added.              

   ![image-8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/3905481e-7523-4714-b46e-f48764856461)

9. Click on **Save** button. Click on the **Save** button, and then by default, you will return to the interfaces menu.                 

   ![image-9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ff83b9be-8412-4578-b5ec-4d7f46336df3)


10. Navigate down and click on **ADD NEW INTERFACE**.                       

    ![image-10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b5760781-9e42-42ca-a370-5bc9114dd2e7)

11. A new window will open. Fill in the details.                                                                                           
    **Name**: Enter the **Name** for **Ex: eth 1**.                                                                                                               
    **Protocol**: Select the **Protocol** for **Ex: Static address**.                                                                                                           
    **Device**: Enter the **Device** for **Ex: eth 1**.                                                                                                                                    
     
    ![image-11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1862d245-2201-4a03-add9-508bb22a09d4)

12. Click on **CREATE INTERFACE** button.                                                                                                                                              

    ![image-12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6b82329e-0571-4ac7-8c11-9727a5c6926c)

13. After clicking on the **CREATE INTERFACE** button a new window will open. Fill in the given details there.
   **IPv4 address**: Enter the **IPv4 address** for **Ex:100.100.100.2**.                                                                                                                 
   **IPv4 netmask**: Select **IPv4 netmask** for **Ex: 255.255.255.0**.                                                                                                                   
   **IPv4 gateway**: Enter the **IPv4 gateway** for **Ex: 192.168.1.1**. IPv4 gateway comes by default.                                                                                   
   **IPv4 broadcast**: Enter the **IPv4 broadcast** for **Ex: 100.100.100.255**. IPv4 broadcast comes by default.            

    ![image-13](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cf613d8c-20b9-458c-87c9-e530d52c7dd9)

14. Click on **Save** button.
    ![image-14](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5f91541a-2b96-41e1-92ff-07c0a05a9584)

15. Then go to the **Services** menu. Go to **Keepalived** inside the **Services** menu.

     ![image-15](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0206a5b1-5d10-4925-b2d4-fb16f755aa58)

16. After going to **Keepalived** a new window will open. Go to the **Globals** tab located there.

    ![image-16](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4b46c432-14d7-4ecd-8f4a-5ec96fa61c93)

17. Click on the **Globals** tab, then the **Keepalived Global Settings** page will open. Enter **Router_ID** where **Router ID** is given there for **Ex:- Backup_node**.

    ![image-17](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/285c390b-a5e3-4602-b2eb-1a3336cadfca)

18. After click on **Save & Apply** button.                

    ![image-18](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d9731808-9633-4b9c-8bec-db8223cbad8b)

19. Go to **IP Address** tab for **IP Address**.

    ![image-19](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a6090b72-5ff6-43a1-9421-f87706198baa)

20. Click on **ADD** button.

    ![image-20](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c95af12a-f479-4202-9a60-3b964bdbf28e)

21. Fill up the details to create an interface.
    **Name**: Enter the **Name** for **Ex:eth0**.                                                                             
    **Address**: Enter the **Address** for **Ex:192.168.1.101**.                                                            
    **Device**: Enter the **Device** for **Ex:eth0**.                                                                           
    **Virtual Device Label** Enter the **Virtual Device Label** for **Ex: Ha**.                                   
    **Scope**: Enter the **Scope** for **Ex:Link**.                                                   

    ![image-21](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/601c3a94-58e9-41c0-b19d-47166855f9c5)

22. Click on the **Save** button.     

     ![image-22](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/40bbad2f-1c6c-49ad-b7f2-4f65f409f111)


23. Add and create an eth2 interface in the same way as you created an interface for eth0.
   **Name**: Enter the **Name** for **ex eth3**.                                                                         
   **Address**: Enter the **Address** for **ex 172.30.2.254**.                                                                       
   **Device**: Enter the **Device** for **ex eth3**.                                                                          
   **Virtual Device Label**:- Enter the **Virtual Device Label** for **ex: ha**.                                                    
   **Scope**:- Enter the **Scope** for **ex: link**.                                                                                    
24. After filling details click on **Save** button.                                                   
25. Click on **Interfaces** tab for **Track Interface**.                                                                        

     ![image-23](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0ff6821f-f16c-4226-a48d-b69980233658)


26. After **Interfaces** a new window will open. Click on the **ADD** button.

    ![image-24](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/95c1ede1-bf70-404e-a5bf-0e96b6985531)

27. Fill the details.
    **Name**: Enter the **Name** for **Ex:eth0_ha**.
    **Device**: Enter the **Device** for **Ex:eth0**.
    **Weight**: Enter the **Weight** for **Ex:100**.

    ![image-25](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/535b5909-ce70-47c1-afb5-457375f17af5)

28. Click on **Save** button.

    ![image-26](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fd058b7d-9788-4430-a0c3-56eef4639975)

> NOTE:- Same step for eth1

29. And after click **Save & Apply**.

    ![image-27](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/479abd3f-6a8f-4433-83a3-283121d933e4)

# Add Backup_node as a peer

30. Click on **Peers** tab.

    ![image-28](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a16dc2b3-d709-48c4-9c03-7c0507e70fe2)

31. Click on **Add** button.

    ![image-29](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c1b614e0-1b97-4fec-9678-697fc1b5c48c)

32. Fill the details
    **Name**: Enter the **Name** for **Ex:Backup_node**.
    **Peers Address**: Select the **Peers Address**. Navigate and Select custom enter IP 100.100.100.1 and press the **Enter** key.

    ![image-30](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/42440dd7-533e-4c1c-9c04-21ffde57cfaa)

33. Click on **Save** button.

    ![image-31](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b5a2f602-8c67-4d3c-a785-8beea2486ffd)

34. Click on **Instance** tab **VRRP Instance**.

    ![image-32](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5e7c4445-4ef4-4f57-8849-6d1c4bb4ab4f)

35. After **Instance** a new window will open. Click on the **ADD** button.

    ![image-33](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/89b068b8-7fe4-4599-bb79-cabb0917d1ad)

36. Fill up the details
    **Name**: Enter the **Name** for **Ex:Backup**.
    **State**:Enter the **State** for **Ex:Backup**.
    **Interface**: Select the **Interface** for **Ex:eth1**.
    **Virtual Router ID**: Enter the **Virtual Router ID** for **Ex:100**.
    **Priority**: Enter the **Priority** for **Ex:100**.
    **Interval**: Enter the **Interval** for **Ex:1**.
    **Disable Preempt**: Enter the **Disable Preempt** for **Ex:NA**.
    **Virtual IP Address**: Select the **Virtual IP Address**. Navigate Select **eth0,eth2**.

    ![image-34](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c082e605-9218-4127-b223-6b2abc14828a)              

37. Click on **Save** button.

    ![image-35](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/07976a49-be73-474e-b78c-7db7833bf6db)                                

    

    


    

    
