# Interface Configuration on Master_node: 

1.	Login to the UI of **Master_node** using the provided IP address.                                                        

  	![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f10832aa-1fa0-4488-a12d-f95ce01c57a7)

2. After login a new window will open. Go to the **Network** menu.                                                        

   ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9721914d-210b-4cb0-8573-c103cba6891a)             

3.	Navigate to the **Interfaces** menu.                                                                                 

    ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6de25958-096a-4216-b478-7f924f482bb9)             

4.	After login a new window will open. Select and **Edit** the **eth0** interface.                                                         

    ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1607d014-ab60-43d6-8a95-ce272732d42b)

5. Click on **Edit** and a new window will open. Fill in the specified details given there.                                                                                                   
   **Protocol**:- Select Static Address in **Protocol**.                                                                                                                                   
   **Really switch protocol**:- There click on **Switch Protocol**.                                                                                                                      

   ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/3c4424c8-ec6d-44f1-bb18-437241077f04)

6. After clicking on switch protocol there will be another information fillup.                                                                                      
   **IPv4 address**: Enter the **IPv4 address** for **Ex:192.168.1.102**.                                                                          
   **IPv4 netmask**: Select **IPv4 netmask** for **Ex: 255.255.255.0**.                                                                                                          
   **IPv4 gateway**: Enter the **IPv4 gateway** for **Ex: 192.168.1.1**.                                                                                                                   
   **IPv4 broadcast**: Enter the **IPv4 broadcast**. IPv4 broadcast comes by default.                                                                  

   ![image-6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4c97d7c3-7c58-4c6f-9790-a3eda0fd050f)

## Advance setting

7. Go to **Advance Setting**.                                                                                         

   ![image-7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cb6757ad-6ff8-47da-8f6f-52e438ac3387)


8. A new window will open there. Add **Use custom DNS servers** there, enter, and click on the **+** icon, and it will be added.              

   ![image-8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/14d03882-23ea-47f4-b37e-ba11a854ed31)

9. Click on **Save** button. Click on the **Save** button then by default, you will return to the **interfaces** menu.                 

   ![image-9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2f7747af-ed1c-4165-ab37-21083249ada7)

10. Navigate down and click on **ADD NEW INTERFACE**.                       

    ![image-10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f5991e3a-4a5a-46d7-bfe0-68c769976d3b)

11. A new window will open. Fill in the details.                                                                                           
    **Name**: Enter the **Name** for **Ex: eth 1**.                                                                                                               
    **Protocol**: Select the **Protocol** for **Ex: Static address**.                                                                                                           
    **Device**: Enter the **Device** for **Ex: eth 1**.                                                                                                                                    
     
    ![image-11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f9155852-7293-4466-b903-ee8ad2ab92f6)

12. Click on **CREATE INTERFACE** button.                                                                                                                                              

    ![image-12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/eac1c25d-93eb-4f9b-a9b7-baab49a09236)

13. After clicking on the **CREATE INTERFACE** button a new window will open. Fill in the given details there.                      
   **IPv4 address**: Enter the **IPv4 address** for **Ex:100.100.100.1**.                                                                                                                 
   **IPv4 netmask**: Select **IPv4 netmask** for **Ex: 255.255.255.0**.                                                                                                                   
   **IPv4 gateway**: Enter the **IPv4 gateway** for **Ex: 192.168.1.1**. IPv4 gateway comes by default.                                                                                   
   **IPv4 broadcast**: Enter the **IPv4 broadcast** for **Ex: 100.100.100.255**. IPv4 broadcast comes by default.            

     ![image-13](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7bc142d4-4924-4a75-acf1-270b79bc118e)

14. Click on **Save** button.

     ![image-14](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ae737b93-1ec1-48f5-b785-a804c16b7e3f)

15. Then go to the **Services** menu. Go to **Keepalived** inside the **Services** menu.

     ![image-15](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/436e162f-3658-458a-8d89-bebab8a53a82)

16. After going to **Keepalived** a new window will open. Go to the **Globals** tab located there.

    ![image-16](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/336a01bd-0c3f-4395-8a35-77ee05a9026c)

17. Click on the **Globals** tab, then the **Keepalived Global Settings** page will open. Enter **Router_ID** where **Router ID** is given there for **Ex:- Master_node**.

    ![image-17](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/69249566-be63-47f3-b34e-09f833436dd4)

18. After click on **Save & Apply** button.

    ![image-18](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f945cdcd-18c5-4883-9970-6b40ec8532c8)


19. Go to **IP Address** tab for **IP Address**.

    ![image-19](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/47a13f34-23f3-4718-8af5-e8c87964fe10)

20. Click on **ADD** button.

    ![image-20](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cdf9b195-cd75-4ede-a881-bf002d4a0a94)

21. Fill up the details to create an **IP Address**.                               
    **Name**: Enter the **Name** for **Ex:eth0**.                                                             
    **Address**: Enter the **Address** for **Ex:192.168.1.101**.                                            
    **Device**: Enter the **Device** for **Ex:eth0**.                                                             
    **Virtual Device Label** Enter the **Virtual Device Label** for **Ex: ha**.                           
    **Scope**: Enter the **Scope** for **Ex:Link**.                               

    ![image-21](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b450585c-2751-4cb1-95b4-bd60d98b5527)

22. Click on the **Save** button.     

     ![image-22](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bd2f5a95-8fa8-4bd2-a3d5-b02572907e21)

23. Add and create an **eth2 IP Address** in the same way as you created an interface for eth0.                    
   **Name**: Enter the **Name** for **ex eth2**.                                                                         
   **Address**: Enter the **Address** for **ex 172.30.1.254**.                                                                       
   **Device**: Enter the **Device** for **ex eth2**.                                                                          
   **Virtual Device Label**:- Enter the **Virtual Device Label** for **ex: ha**.                                                    
   **Scope**:- Enter the **Scope** for **ex: link**.                                                                                    
24. After filling details click on **Save** button.                                                   

    ![image-23](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d9ade0bd-554f-458e-8824-b3d15de1328f)


25. Click on **Interfaces** tab for **Track Interface**.                                                                     

     ![image-24 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/06239947-62ff-4899-b497-6f917cb0e807)

26. After **Interfaces** a new window will open. Click on the **ADD** button.

    ![image-25 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/09ba41be-1d08-46fc-b099-d7c0db641ef3)

27. Fill the details.                    
    **Name**: Enter the **Name** for **Ex:eth0_ha**.                 
    **Device**: Enter the **Device** for **Ex:eth0**.               
    **Weight**: Enter the **Weight** for **Ex:100**.              

    ![image-26 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/dc459398-b570-4e96-b484-b4d929763fda)

28. Click on **Save** button.

    ![image-27 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/740c860c-ea6a-4c60-8669-1033b2557a59)

29. Same step for **eth1_ha**. And after clicking **Save & Apply**.

    ![image-28 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/68e59ddd-4481-4ecb-9b0d-b65ea4b87a32)

## Add Backup_node as a peer

30. Click on **Peers** tab.

    ![image-29](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cbe580f9-3fa1-4787-89cf-8c68df3e02c7)

31. Click on **Add** button.

    ![image-30 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/22e8bb10-0208-4a30-a562-34330e1ede0e)

32. Fill the details.                                       
    **Name**: Enter the **Name** for **Ex:Backup_node**.                       
    **Peers Address**: Select the **Peers Address**. Navigate and Select custom enter IP 100.100.100.2 and press the **Enter** key.    

    ![image-31](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b772e5c2-abb2-4a3b-98f5-19200fcaa797)

33. Click on **Save** button.

   ![image-32](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9b90d242-8dbb-42d9-976f-359be488e700)

34. Click on **Instance** tab **VRRP Instance**.

    ![image-33 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7ee04259-3a1c-47bc-9caf-6c6a94f63310)

35. After **Instance** a new window will open. Click on the **ADD** button.

    ![image-34 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/def2d2be-fbb2-4724-8be3-118400d94204)

36. Fill up the details.                     
    **Name**: Enter the **Name** for **Ex:Master**.               
    **State**:Enter the **State** for **Ex:Master**.             
    **Interface**: Select the **Interface** for **Ex:eth1**.                    
    **Virtual Router ID**: Enter the **Virtual Router ID** for **Ex:100**.                    
    **Priority**: Enter the **Priority** for **Ex:100**.                     
    **Interval**: Enter the **Interval** for **Ex:1**.                           
    **Disable Preempt**: Enter the **Disable Preempt** for **Ex:na**.                         
    **Virtual IP Address**: Select the **Virtual IP Address**. Navigate Select eth0,eth2.                         

    ![image-35 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5e05927d-306c-40e8-a8f3-2ebdfebe1ec3)

37. Click on **Save** button.

    ![image-36 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fd695aba-bfbc-47b3-bb82-397792a7a965)

38. Go to the **Peer** and fill in the details.            
    **Unicast Source IP**: Navigate and Select **100.100.100.1**.           
    **Peer**: Peer select **Backup_node**.            
    **HA Authentication Type**: Select **Simple Password**.             
    **Password**: Enter **Password** for **Ex:admin**.                    

    ![image-37 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b2474666-0170-40db-9a69-aa538ab79af9)

39. Click on **Save** button.                

    ![image-38 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d73b7150-5013-4086-a079-271e733fd9b4)

40. Go to the **Track** and fill the details.                 
    **Track Interfaces**: Select **eth0_ha and eth1_ha**.               

    ![image-39 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7f8d7413-2784-4993-92c4-865c592aa33c)

41. Click on **Save** button.

    ![image-40 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2d685835-970d-46b7-9c81-2c67551a70d0)


# Interface Configuration on Backup_node:

42.	Login to the UI of **Backup_node** using the provided IP address.                                                                                                           

  	![image-44 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/3dccf01e-eef5-4061-8a9b-6642cf92e20d)

43. After login a new window will open. Go to the **Network** menu.                                                                                             

    ![image-45](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7189a909-8aec-4af4-be75-a45936aea89d)

44.	Navigate to the **Interfaces** menu.                                                                                                                                               

    ![image-46](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/398b48e1-b706-44db-8792-63067c71032c)

45.	After login a new window will open. Select and **Edit** the **eth0** interface.                                                                                     

    ![image-47](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6ae095aa-2ffd-4997-a410-7e3267daeaad)         

46. Click on **Edit** and a new window will open. Fill in the specified details given there.                                                                                                   
   **Protocol**:- Select Static Address in **Protocol**.                                                                                                                                  
   **Really Switch Protocol**:- There click on **Switch Protocol**.                                                                                                                         

    ![image-48](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e6d56699-a7ba-425e-9d6e-ee1fd9e326cf)

47. After clicking on switch protocol there will be another information fillup.                                                                        
   **IPv4 address**: Enter the **IPv4 address** for **Ex:192.168.1.103**.                                                                          
   **IPv4 netmask**: Select **IPv4 netmask** for **Ex: 255.255.255.0**.                                                                                                          
   **IPv4 gateway**: Enter the **IPv4 gateway** for **Ex: 192.168.1.1**.                                                                                                                  
   **IPv4 broadcast**: Enter the **IPv4 broadcast**. IPv4 broadcast comes by default.                                                                  

    ![image-49](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fa05b602-1dfe-434a-9539-c79597e7790e)

## Advance setting

48. Go to **Advance setting**.                                                                                         

    ![image-50](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4a860f72-dcbc-46f7-a90d-67e6f58e3c88)


49. A new window will open there. Add **Use custom DNS servers** there, enter, and click on the **+** icon, and it will be added.              

    ![image-52](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e5ff696b-6ee7-4e5a-9f2a-af22e190cfb2)

50. Click on **Save** button. Click on the **Save** button, and then by default, you will return to the interfaces menu.                 

    ![image-53](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ca30e2d8-4c83-4634-bc31-e77b15511340)

51. Navigate down and click on **ADD NEW INTERFACE**.                       

    ![image-10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f5991e3a-4a5a-46d7-bfe0-68c769976d3b)

52. A new window will open. Fill in the details.                                                                                           
    **Name**: Enter the **Name** for **Ex: eth 1**.                                                                                                               
    **Protocol**: Select the **Protocol** for **Ex: Static address**.                                                                                                           
    **Device**: Enter the **Device** for **Ex: eth 1**.                                                                                                                                    
     
    ![image-55](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9c583f86-1c65-4b0f-94be-b2b2f384878d)

53. Click on **CREATE INTERFACE** button.                                                                                                                                              

    ![image-56](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/012eaf51-999b-48b0-be11-82582db8c0c2)

54. After clicking on the **CREATE INTERFACE** button a new window will open. Fill in the given details there.                     
   **IPv4 address**: Enter the **IPv4 address** for **Ex:100.100.100.2**.                                                                                                                 
   **IPv4 netmask**: Select **IPv4 netmask** for **Ex: 255.255.255.0**.                                                                                                                    
   **IPv4 gateway**: Enter the **IPv4 gateway** for **Ex: 192.168.1.1**. IPv4 gateway comes by default.                                                                                   
   **IPv4 broadcast**: Enter the **IPv4 broadcast** for **Ex: 100.100.100.255**. IPv4 broadcast comes by default.            

    ![image-57](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/96367cbd-a6e7-4781-9adf-b8c99cba291a)

55. Click on **Save** button.
    ![image-58](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/10b6ead0-33b6-46a3-a8f7-bb3b56fbbab4)

56. Then go to the **Services** menu. Go to **Keepalived** inside the **Services** menu.

    ![image-59](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/42cbc3b1-5f2d-4ac2-b23f-53c01ff9a8fd)

57. After going to **Keepalived** a new window will open. Go to the **Globals** tab located there.

    ![image-60](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cef64d8f-e32f-4490-933f-6ea0227076fe)


58. Click on the **Globals** tab, then the **Keepalived Global Settings** page will open. Enter **Router_ID** where **Router ID** is given there for **Ex:- Backup_node**.

    ![image-61](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/07c61ca8-0995-49d7-8fcb-7978d0a772ad)

59. After click on **Save & Apply** button.                

    ![image-62](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9d737a2b-75df-4cfe-badf-b2439c8edcc1)

60. Go to **IP Address** tab for **IP Address**.

    ![image-63](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2d19bab3-41d5-46eb-a9bb-954c5ce6be24)

61. Click on **ADD** button.

    ![image-64](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8688f245-68aa-435d-8157-2f955fd88775)

62. Fill up the details to create an **IP Address**.                         
    **Name**: Enter the **Name** for **Ex:eth0**.                                                                             
    **Address**: Enter the **Address** for **Ex:192.168.1.101**.                                                            
    **Device**: Enter the **Device** for **Ex:eth0**.                                                                           
    **Virtual Device Label** Enter the **Virtual Device Label** for **Ex: ha**.                                   
    **Scope**: Enter the **Scope** for **Ex:Link**.                                                   

    ![image-65](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/874c032a-42e1-4941-bcbe-2afad7f57853)

63. Click on the **Save** button.     

     ![image-66](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/013ebabc-026f-49f5-b8cb-d7824c8d3275)

64. Add and create an **eth3 IP Address** in the same way as you created an interface for eth0.                      
   **Name**: Enter the **Name** for **ex eth3**.                                                                         
   **Address**: Enter the **Address** for **ex 172.30.2.254**.                                                                       
   **Device**: Enter the **Device** for **ex eth3**.                                                                          
   **Virtual Device Label**:- Enter the **Virtual Device Label** for **ex: ha**.                                                    
   **Scope**:- Enter the **Scope** for **ex: link**.                                                                                    
65. After filling details click on the **Save** button.                                                   

    ![image-67](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cea0cf1e-2060-439c-b2f3-a0c6becc513f)


66. Click on **Interfaces** tab for **Track Interface**.                                                                        

     ![image-68](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4fa3c482-5dae-4632-8012-b7649a43b590)

67. After **Interfaces** a new window will open. Click on the **ADD** button.

    ![image-69](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6b181b16-660e-4a1b-9a41-9644a0cc885f)

68. Fill the details.                               
    **Name**: Enter the **Name** for **Ex:eth0_ha**.                   
    **Device**: Enter the **Device** for **Ex:eth0**.                    
    **Weight**: Enter the **Weight** for **Ex:100**.                   

    ![image-70](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7e6274ed-37e2-4967-80e8-42832a898c7f)

69. Click on **Save** button.

    ![image-71](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8fd555e0-3dee-4e72-a879-90908750908d)

70. Same step for **eth1**. And after clicking **Save & Apply**.

    ![image-72](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ec909cfd-8475-4e92-a538-26c42fe8fc9e)

# Add Backup_node as a peer

71. Click on **Peers** tab.

    ![image-73](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/89915756-88d1-48f2-8ab4-71a194d28404)


72. Click on **Add** button.

    ![image-74](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0581004c-827b-49a6-8f05-5b5a089e36d1)

73. Fill the details.               
    **Name**: Enter the **Name** for **Ex:Master_node**.              
    **Peers Address**: Select the **Peers Address**. Navigate and Select custom enter IP 100.100.100.1 and press the **Enter** key.   

    ![image-75](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7ee5fcbc-d94c-4245-8bbf-e8d3b8187cdb)

74. Click on **Save** button.

    ![image-76](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c552b53b-c3a5-426e-912d-494b458acc5d)


75. Click on **Instance** tab **VRRP Instance**.

    ![image-77](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c6e92a82-5f09-42e1-8a8c-561005215395)

76. After **Instance** a new window will open. Click on the **ADD** button.

    ![image-78](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d29a8e1d-77b4-4491-97b7-b8247432ae3b)            

77. Fill up the details               
    **Name**: Enter the **Name** for **Ex:Backup**.                  
    **State**:Enter the **State** for **Ex:Backup**.               
    **Interface**: Select the **Interface** for **Ex:eth1**.                 
    **Virtual Router ID**: Enter the **Virtual Router ID** for **Ex:100**.               
    **Priority**: Enter the **Priority** for **Ex:50**.                  
    **Interval**: Enter the **Interval** for **Ex:1**.                  
    **Disable Preempt**: Enter the **Disable Preempt** for **Ex:na**.                       
    **Virtual IP Address**: Select the **Virtual IP Address**. Navigate Select **eth0,eth2**.               

    ![image-79](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7fa0bcb0-676a-4736-8f53-373dfdcda665)

78. Click on **Save** button.

    ![image-80](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d02e2b91-5784-484f-9cec-0c158bed5170)

79. Go to the **Peer** and fill in the details.                
    **Unicast Source IP**: Navigate and Select **100.100.100.2**.               
    **Peer**: Peer select **Master_node**.               
    **HA Authentication Type**: Select **Simple Password**.             
    **Password**: Enter **Password** for **Ex:admin**.           

     ![image-81](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/3bcbb594-efc7-446a-b949-7c9eaab582a5)


80. Click on **Save** button.

    ![image-82](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7e91874b-5e62-409e-ac9e-f3293dd4f456)

81. Go to the **Track** and fill the details.                      
    **Track Interfaces**: Select eth0_ha and eth1_ha                      

     ![image-83](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/51419b5d-522e-4960-9d42-09dbfec0e341)

82. Click on **Save** button.

    ![image-84](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/377be9b1-e49f-4e46-8f88-ec3ba0a0722f)

## Ensure Keepalived Service is Enabled and Restarted on both nodes

83. Go to **System** menu of Backup_node.

    ![image-85](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1601fc64-6854-4186-9ed0-383feb5c3e59)
   
84. Go to **Startup** menu.

    ![image-86](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/55a7fe66-c1ee-4e50-bf0b-8bb4cf826ad0)
   
85. Click on the **ENABLED** button to keepalive service and click on **RESTART** button Service.

    ![image-87](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/87b341ad-56d8-4c62-a45f-67d9388b6316)

86. Check service status in CE Command line **ps | grep keep**.
      ```
           ps | grep keep
           3643 root      2188 S    /bin/sh /usr/bin/keepalived-rsync-inotify Backup Mas
           4783 root      3428 S    {keepalive.sh} /bin/sh /usr/bin/keepalive.sh
           11648 root      5812 S    /usr/sbin/keepalived -n -f /tmp/keepalived.conf
           11649 root      5816 S    {keepalived_vrrp} /usr/sbin/keepalived -n -f /tmp/ke
           30512 root      1120 R    grep keep
      ```


## Verify Overview Status on Both Nodes:
88. When the configuration is successful in both nodes, the status will be like the below in both nods overview menus.
89. Check if the status on both Master_node and Backup_node matches the expected status as provided.
90. Now go to the **Services** menu and click on **Keepalived**.

### Master_node

91. When the configuration is done, the status of the node will appear. The status of the **Master_node** will be like this.
    ![image-90](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/02c5a625-186f-4c8b-8341-007a631cbd1d)

- IP addr show of **Master_node** will be like this. **eth0 (192.168.1.101) and eth2 (192.168.254.254)** as virtual IP will be used.
   ```
     root@Master_node:~# ip addr show
     1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host 
       valid_lft forever preferred_lft forever
    2: ip6tnl0@NONE: <NOARP> mtu 1452 qdisc noop state DOWN group default qlen 1000
    link/tunnel6 :: brd :: permaddr 4a35:c191:6636::
   3: ip_vti0@NONE: <NOARP> mtu 1480 qdisc noop state DOWN group default qlen 1000
    link/ipip 0.0.0.0 brd 0.0.0.0
   4: ip6_vti0@NONE: <NOARP> mtu 1332 qdisc noop state DOWN group default qlen 1000
    link/tunnel6 :: brd :: permaddr ae69:71fe:29b5::
   5: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 08:00:27:c6:33:21 brd ff:ff:ff:ff:ff:ff
    inet 192.168.1.101/32 scope link eth0:ha
       valid_lft forever preferred_lft forever
    inet 192.168.1.102/24 brd 192.168.1.255 scope global eth0
       valid_lft forever preferred_lft forever
    inet6 fe80::a00:27ff:fec6:3321/64 scope link 
       valid_lft forever preferred_lft forever
   6: eth1: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 08:00:27:0f:37:6b brd ff:ff:ff:ff:ff:ff
    inet 100.100.100.1/24 brd 100.100.100.255 scope global eth1
       valid_lft forever preferred_lft forever
    inet6 fe80::a00:27ff:fe0f:376b/64 scope link 
       valid_lft forever preferred_lft forever
   7: eth2: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 08:00:27:82:00:57 brd ff:ff:ff:ff:ff:ff
    inet 192.168.254.254/32 scope link eth2:ha
       valid_lft forever preferred_lft forever
    inet 192.168.254.1/24 brd 192.168.254.255 scope global eth2
       valid_lft forever preferred_lft forever
    inet6 fe80::a00:27ff:fe82:57/64 scope link 
       valid_lft forever preferred_lft forever
  ```

## Backup_node
92. **Backup_node** status will be as follows.

    ![image-88](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f5e95d07-6c5e-42f7-884e-757697da9609)
 
 - IP addr show of **Backup_node** will be like this. **eth0 (192.168.1.103 and eth2 (192.168.254.2)** as virtual IP will be used. 

   ```
   root@Backup_node:~# ip addr show
   1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host 
       valid_lft forever preferred_lft forever
   2: ip6tnl0@NONE: <NOARP> mtu 1452 qdisc noop state DOWN group default qlen 1000
    link/tunnel6 :: brd :: permaddr 9607:ea3f:6936::
   3: ip_vti0@NONE: <NOARP> mtu 1480 qdisc noop state DOWN group default qlen 1000
    link/ipip 0.0.0.0 brd 0.0.0.0
   4: ip6_vti0@NONE: <NOARP> mtu 1332 qdisc noop state DOWN group default qlen 1000
    link/tunnel6 :: brd :: permaddr 1e03:c9a5:3074::
   5: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 08:00:27:92:4b:a8 brd ff:ff:ff:ff:ff:ff
    inet 192.168.1.103/24 brd 192.168.1.255 scope global eth0
       valid_lft forever preferred_lft forever
    inet6 fe80::a00:27ff:fe92:4ba8/64 scope link 
       valid_lft forever preferred_lft forever
   6: eth1: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 08:00:27:dc:ee:80 brd ff:ff:ff:ff:ff:ff
    inet 100.100.100.2/24 brd 100.100.100.255 scope global eth1
       valid_lft forever preferred_lft forever
    inet6 fe80::a00:27ff:fedc:ee80/64 scope link 
       valid_lft forever preferred_lft forever
   7: eth2: <BROADCAST,MULTICAST> mtu 1500 qdisc noop state DOWN group default qlen 1000
    link/ether 08:00:27:45:9c:a4 brd ff:ff:ff:ff:ff:ff
   8: eth3: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 08:00:27:3b:e7:b0 brd ff:ff:ff:ff:ff:ff
    inet 192.168.254.2/24 brd 192.168.254.255 scope global eth3
       valid_lft forever preferred_lft forever
    inet6 fe80::a00:27ff:fe3b:e7b0/64 scope link 
       valid_lft forever preferred_lft forever
    ```

## Testing:

93. When the **Master_node** goes off, it will switch to the **Backup node's** node. Its status will be **Master/Backup** because the backup will go to the **Master_node**. And then when the **Master_node** turns on it will go back to **Master/Master**.

     ![image-89](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/abcfe1f8-35d8-40e7-ba5c-4ee07dc1e6f7)

- When the **Master_node** shuts down its ip goes to **Backup_node** then its app addr show will be like this.

  ```
  root@Backup_node1:~# ip addr show
 1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host 
       valid_lft forever preferred_lft forever
2: ip6tnl0@NONE: <NOARP> mtu 1452 qdisc noop state DOWN group default qlen 1000
    link/tunnel6 :: brd :: permaddr 9607:ea3f:6936::
3: ip_vti0@NONE: <NOARP> mtu 1480 qdisc noop state DOWN group default qlen 1000
    link/ipip 0.0.0.0 brd 0.0.0.0
4: ip6_vti0@NONE: <NOARP> mtu 1332 qdisc noop state DOWN group default qlen 1000
    link/tunnel6 :: brd :: permaddr 1e03:c9a5:3074::
5: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 08:00:27:92:4b:a8 brd ff:ff:ff:ff:ff:ff
    inet 192.168.1.101/32 scope link eth0:ha
       valid_lft forever preferred_lft forever
    inet 192.168.1.103/24 brd 192.168.1.255 scope global eth0
       valid_lft forever preferred_lft forever
    inet6 fe80::a00:27ff:fe92:4ba8/64 scope link 
       valid_lft forever preferred_lft forever
6: eth1: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 08:00:27:dc:ee:80 brd ff:ff:ff:ff:ff:ff
    inet 100.100.100.2/24 brd 100.100.100.255 scope global eth1
       valid_lft forever preferred_lft forever
    inet6 fe80::a00:27ff:fedc:ee80/64 scope link 
       valid_lft forever preferred_lft forever
7: eth2: <BROADCAST,MULTICAST> mtu 1500 qdisc noop state DOWN group default qlen 1000
    link/ether 08:00:27:45:9c:a4 brd ff:ff:ff:ff:ff:ff
8: eth3: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 08:00:27:3b:e7:b0 brd ff:ff:ff:ff:ff:ff
    inet 192.168.254.254/32 scope link eth3:ha
       valid_lft forever preferred_lft forever
    inet 192.168.254.2/24 brd 192.168.254.255 scope global eth3
       valid_lft forever preferred_lft forever
    inet6 fe80::a00:27ff:fe3b:e7b0/64 scope link 
       valid_lft forever preferred_lft forever 

  ```


 
