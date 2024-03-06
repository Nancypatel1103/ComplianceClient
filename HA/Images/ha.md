# Interface Configuration on Master_node: 

1.	Login to the UI of **Master_node** using the provided IP address.                                                        

  	![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f10832aa-1fa0-4488-a12d-f95ce01c57a7)

2. After login a new window will open. Go to the **Network** menu.                                                        

   ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9721914d-210b-4cb0-8573-c103cba6891a)             

3.	Navigate to the **Interfaces** menu.                                                                                 

   ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6de25958-096a-4216-b478-7f924f482bb9)             

4.	After login a new window will open. Select and **Edit** the **eth0** interface.                                                         

   ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2eb24177-d3dc-435c-9932-528261d72954)          

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

# Advance setting

7. Go to **Advance Setting**.                                                                                         

  ![image-7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cb6757ad-6ff8-47da-8f6f-52e438ac3387)


8. A new window will open there. Add **Use custom DNS servers** there, enter, and click on the **+** icon, and it will be added.              

   ![image-8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/14d03882-23ea-47f4-b37e-ba11a854ed31)

9. Click on **Save** button. Click on the **Save** button then by default, you will return to the **interfaces** menu.                 

   ![image-9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2f7747af-ed1c-4165-ab37-21083249ada7)

10. Navigate down and click on **ADD NEW INTERFACE**.                       

   ![image-10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9c6d3bb1-aef4-4760-b621-1f9aab0d528a)

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

   ![image-21](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b450585c-2751-4cb1-95b4-bd60d98b5497)

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

    ![image-28 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153615969/68e59ddd-4481-4ecb-9b0d-b65ea4b87a32)

# Add Backup_node as a peer

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

    ![image-45](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/06fe0b57-a07f-45f3-81b5-b2dd23595d17)

44.	Navigate to the **Interfaces** menu.                                                                                                                                               

   ![image-46](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bc048c9a-1933-4af8-96ce-c397010ffaca)

45.	After login a new window will open. Select and **Edit** the **eth0** interface.                                                                                     

   ![image-47](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/73d6074f-3a23-4632-a1d5-01adaa80074b)          

46. Click on **Edit** and a new window will open. Fill in the specified details given there.                                                                                                   
   **Protocol**:- Select Static Address in **Protocol**.                                                                                                                                  
   **Really Switch Protocol**:- There click on **Switch Protocol**.                                                                                                                         

   ![image-48](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/3bc3ac65-89e8-4e67-8fb5-7a88e0786ed7)

47. After clicking on switch protocol there will be another information fillup.                                                                        
   **IPv4 address**: Enter the **IPv4 address** for **Ex:192.168.1.103**.                                                                          
   **IPv4 netmask**: Select **IPv4 netmask** for **Ex: 255.255.255.0**.                                                                                                          
   **IPv4 gateway**: Enter the **IPv4 gateway** for **Ex: 192.168.1.1**.                                                                                                                  
   **IPv4 broadcast**: Enter the **IPv4 broadcast**. IPv4 broadcast comes by default.                                                                  

  ![image-49](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1f4aa05a-3422-45a0-ab52-193255f6adb8)

# Advance setting

48. Go to **Advance setting**.                                                                                         

   ![image-50](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a3f7f956-11e1-495b-b428-638b7e9a94fa)

49. A new window will open there. Add **Use custom DNS servers** there, enter and click on the **+** icon, and it will be added.              

  ![image-51](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6dc185a8-4812-42e6-9367-7e93ae03834f)

50. Click on **Save** button. Click on the **Save** button, and then by default, you will return to the interfaces menu.                 

   ![image-52](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e5ff696b-6ee7-4e5a-9f2a-af22e190cfb2)


51. Navigate down and click on **ADD NEW INTERFACE**.                       

    ![image-53](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ca30e2d8-4c83-4634-bc31-e77b15511340)

52. A new window will open. Fill in the details.                                                                                           
    **Name**: Enter the **Name** for **Ex: eth 1**.                                                                                                               
    **Protocol**: Select the **Protocol** for **Ex: Static address**.                                                                                                           
    **Device**: Enter the **Device** for **Ex: eth 1**.                                                                                                                                    
     
    ![image-54](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/429fe160-9a9a-4a11-8c87-3f92e3109ac2)

53. Click on **CREATE INTERFACE** button.                                                                                                                                              

    ![image-55](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9c583f86-1c65-4b0f-94be-b2b2f384878d)

54. After clicking on the **CREATE INTERFACE** button a new window will open. Fill in the given details there.                     
   **IPv4 address**: Enter the **IPv4 address** for **Ex:100.100.100.2**.                                                                                                                 
   **IPv4 netmask**: Select **IPv4 netmask** for **Ex: 255.255.255.0**.                                                                                                                    
   **IPv4 gateway**: Enter the **IPv4 gateway** for **Ex: 192.168.1.1**. IPv4 gateway comes by default.                                                                                   
   **IPv4 broadcast**: Enter the **IPv4 broadcast** for **Ex: 100.100.100.255**. IPv4 broadcast comes by default.            

    ![image-56](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/012eaf51-999b-48b0-be11-82582db8c0c2)

55. Click on **Save** button.
    ![image-57](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/96367cbd-a6e7-4781-9adf-b8c99cba291a)

56. Then go to the **Services** menu. Go to **Keepalived** inside the **Services** menu.

    ![image-58](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/10b6ead0-33b6-46a3-a8f7-bb3b56fbbab4)

57. After going to **Keepalived** a new window will open. Go to the **Globals** tab located there.

    ![image-59](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/42cbc3b1-5f2d-4ac2-b23f-53c01ff9a8fd)


58. Click on the **Globals** tab, then the **Keepalived Global Settings** page will open. Enter **Router_ID** where **Router ID** is given there for **Ex:- Backup_node**.

    ![image-60](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cef64d8f-e32f-4490-933f-6ea0227076fe)

59. After click on **Save & Apply** button.                

    ![image-61](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/07c61ca8-0995-49d7-8fcb-7978d0a772ad)

60. Go to **IP Address** tab for **IP Address**.

    ![image-62](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9d737a2b-75df-4cfe-badf-b2439c8edcc1)

61. Click on **ADD** button.

    ![image-63](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2d19bab3-41d5-46eb-a9bb-954c5ce6be24)

62. Fill up the details to create an **IP Address**.                         
    **Name**: Enter the **Name** for **Ex:eth0**.                                                                             
    **Address**: Enter the **Address** for **Ex:192.168.1.101**.                                                            
    **Device**: Enter the **Device** for **Ex:eth0**.                                                                           
    **Virtual Device Label** Enter the **Virtual Device Label** for **Ex: ha**.                                   
    **Scope**: Enter the **Scope** for **Ex:Link**.                                                   

    ![image-64](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8688f245-68aa-435d-8157-2f955fd88775)

63. Click on the **Save** button.     

     ![image-65](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/874c032a-42e1-4941-bcbe-2afad7f57853)

64. Add and create an **eth3 IP Address** in the same way as you created an interface for eth0.                      
   **Name**: Enter the **Name** for **ex eth3**.                                                                         
   **Address**: Enter the **Address** for **ex 172.30.2.254**.                                                                       
   **Device**: Enter the **Device** for **ex eth3**.                                                                          
   **Virtual Device Label**:- Enter the **Virtual Device Label** for **ex: ha**.                                                    
   **Scope**:- Enter the **Scope** for **ex: link**.                                                                                    
65. After filling details click on **Save** button.                                                   

    ![image-66](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/013ebabc-026f-49f5-b8cb-d7824c8d3275)


66. Click on **Interfaces** tab for **Track Interface**.                                                                        

     ![image-67](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cea0cf1e-2060-439c-b2f3-a0c6becc513f)

67. After **Interfaces** a new window will open. Click on the **ADD** button.

    ![image-68](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4fa3c482-5dae-4632-8012-b7649a43b590)

68. Fill the details.
    **Name**: Enter the **Name** for **Ex:eth0_ha**.
    **Device**: Enter the **Device** for **Ex:eth0**.
    **Weight**: Enter the **Weight** for **Ex:100**.

    ![image-69](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6b181b16-660e-4a1b-9a41-9644a0cc885f)

69. Click on **Save** button.

    ![image-70](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7e6274ed-37e2-4967-80e8-42832a898c7f)

70. Same step for **eth1**. And after clicking **Save & Apply**.

    ![image-71](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8fd555e0-3dee-4e72-a879-90908750908d)

# Add Backup_node as a peer

71. Click on **Peers** tab.

   ![image-72](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ec909cfd-8475-4e92-a538-26c42fe8fc9e)


72. Click on **Add** button.

    ![image-73](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/89915756-88d1-48f2-8ab4-71a194d28404)

73. Fill the details.               
    **Name**: Enter the **Name** for **Ex:Backup_node**.              
    **Peers Address**: Select the **Peers Address**. Navigate and Select custom enter IP 100.100.100.1 and press the **Enter** key.   

    ![image-74](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0581004c-827b-49a6-8f05-5b5a089e36d1)

74. Click on **Save** button.

   ![image-75](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7ee5fcbc-d94c-4245-8bbf-e8d3b8187cdb)


75. Click on **Instance** tab **VRRP Instance**.

    ![image-76](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c552b53b-c3a5-426e-912d-494b458acc5d)

76. After **Instance** a new window will open. Click on the **ADD** button.

    ![image-77](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c6e92a82-5f09-42e1-8a8c-561005215395)

77. Fill up the details               
    **Name**: Enter the **Name** for **Ex:Backup**.                  
    **State**:Enter the **State** for **Ex:Backup**.               
    **Interface**: Select the **Interface** for **Ex:eth1**.                 
    **Virtual Router ID**: Enter the **Virtual Router ID** for **Ex:100**.               
    **Priority**: Enter the **Priority** for **Ex:100**.                  
    **Interval**: Enter the **Interval** for **Ex:1**.                  
    **Disable Preempt**: Enter the **Disable Preempt** for **Ex:na**.                       
    **Virtual IP Address**: Select the **Virtual IP Address**. Navigate Select **eth0,eth2**.               

    ![image-78](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d29a8e1d-77b4-4491-97b7-b8247432ae3b)            

78. Click on **Save** button.

    ![image-79](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c38baaca-d1c2-4d51-8d69-e424cbe12cde)

79. Go to the **Peer** and fill in the details.                
    **Unicast Source IP**: Navigate and Select **100.100.0.30**.               
    **Peer**: Peer select **Master_node**.               
    **HA Authentication Type**: Select **Simple Password**.             
    **Password**: Enter **Password** for **Ex:admin**.           

    ![image-80](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d02e2b91-5784-484f-9cec-0c158bed5170)

80. Click on **Save** button.

    ![image-81](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/508e03de-846d-440a-900e-4ac3d729579f)

81. Go to the **Track** and fill the details.                      
    **Track Interfaces**: Select eth0_ha and eth1_ha                      

  ![image-82](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fea52efb-eb03-401b-8977-32cdf0478260)

82. Click on **Save** button.

    ![image-83](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/51419b5d-522e-4960-9d42-09dbfec0e341)

83. Go to **System** menu of Backup_node.

    ![image-84](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/377be9b1-e49f-4e46-8f88-ec3ba0a0722f)

84. Go to **Startup** menu.

   ![image-85](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1601fc64-6854-4186-9ed0-383feb5c3e59)
   
85. Click on the **ENABLED** button to keepalive service and click on **RESTART** button Service.

    ![image-87](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/580b4e5f-c0b2-4311-8a33-fe577e884acd)

86. Verify Overview Status. Check if the status on both Master_node and Backup_node matches the expected status as provided.
87. Now go to **Services** menu and click on **Keepalived**.
     ![image-43](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/dd7c7691-431b-48e7-aa58-4c8d5be78c05)

88. Turn off the master node Check the status of the backup node. When we turn off the master node, everything will be moved to the backup node. Then get the master/backup. When we start the master node, it will go to the master node and replace master/backup with backup/backup.

     ![image-43](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/761f945b-1d27-4102-87e0-341453b1702f)
