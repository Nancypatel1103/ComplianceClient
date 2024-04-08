# HA Configuration

## What is a HA Configuration
High Availability (HA) in both Backup_node and Master_node refers to the capability of the nodes to ensure uninterrupted operation and minimal downtime. In the context of networking, HA involves redundant systems and failover mechanisms that automatically switch to backup nodes in case of primary node failure. This ensures continuous access to services and resources, even during hardware or software failures. HA setups typically employ techniques like load balancing, clustering, and data replication to distribute workload and maintain service availability. In essence, HA in both Backup_node and Master_node enhances reliability, resilience, and fault tolerance in network infrastructures, crucial for critical applications and services.

## Why do we need HA Configuration
High Availability (HA) in both Backup_node and Master_node is essential to ensure uninterrupted operation of critical systems and services. HA setups provide redundancy and failover mechanisms that automatically switch to backup nodes in case of primary node failure. This reduces downtime, ensuring continuous access to resources and services for users. HA also enhances reliability, resilience, and fault tolerance in network infrastructures, crucial for maintaining productivity and meeting service level agreements. Additionally, HA minimizes the risk of data loss and ensures business continuity, making it indispensable for organizations relying on continuous operation of their IT infrastructure.

## How to Interface Configuration on Master_node

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

### Advance setting

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

29. Same step for **eth2_ha**. And after clicking **Save & Apply**.

    ![image-28](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5073a1c4-3a23-4f1b-96ec-d7db75d6d6cd)

### Add Backup_node as a peer

30. Click on **Peers** tab.

    ![image-29](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0a707720-5add-4263-8811-395c7160759d)


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
    **Track Interfaces**: Select **eth0_ha and eth2_ha**.               

    ![image-39](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2ff0998c-b370-406e-b340-96dd9955f5b4)

41. Click on **Save** button.

   ![image-40 ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d01a0e55-64cb-4596-ae53-938a07c57891)


## How to interface configuration on Backup_node:

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

### Advance setting

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

70. Same step for **eth3_ha**. And after clicking **Save & Apply**.

    ![image-72](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6338609f-6520-46b0-8a99-8f11300d6c6b)

### Add Backup_node as a peer

71. Click on **Peers** tab.

    ![image-73](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7bed345a-f126-4f0f-a29a-8907e6ec58f4)


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
    **Virtual IP Address**: Select the **Virtual IP Address**. Navigate Select **eth0,eth3**.               

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
    **Track Interfaces**: Select eth0_ha and eth3_ha                      

     ![image-83](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a89da737-735b-4198-9188-a0f665a56608)

82. Click on **Save** button.

    ![image-84](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/64591082-a13c-42b6-b615-79ed7dfa60ea)

### Ensure Keepalived Service is Enabled and Restarted on both nodes

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


### Verify Overview Status on Both Nodes:
88. Check if the status on both Master_node and Backup_node matches the expected status as provided.
89. Now go to the **Services** menu and click on **Keepalived**.

#### Master_node

90. When the configuration is done, the status of the node will appear. The status of the **Master_node** will be like this.
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

#### Backup_node
91. **Backup_node** status will be as follows.

    ![image-88](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f5e95d07-6c5e-42f7-884e-757697da9609)
 
 - IP addr show of **Backup_node** will be like this. 

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

### Testing:

92. When the **Master_node** goes off, it will switch to the **Backup node's** node. Its status will be **Master/Backup** because the backup will go to the **Master_node**. And then when the **Master_node** turns on it will go back to **Master/Master**.

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
 
## How to Sync configuration on Master_node:

93.	Login to the UI of **Master_node** using the provided IP address.                                                        

  	![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f10832aa-1fa0-4488-a12d-f95ce01c57a7)

94. Go to the **Services** menu. Go to **Keepalived** inside the **Services** menu.

   ![image-92](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/96e4e5d6-5ad2-4252-826c-086129bca93b)

95. After clicking **Keepalived** a window will open. Go to the **Script** tab.

   ![image-93](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2f459080-9c0d-4e48-8651-8a99f3d86107)

96. A new window will open. Click on the **Add** button.

   ![image-94](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/463d5e15-535e-4f41-957c-d7ee00187858)

97. Fill the details.
   **Name**: Enter the **Name** for **Ex: sync_ha**.
   **Script**: Click on **Select file** and choose file(By default file will appear there, you have to select)
   **Interval**: Interval which will be 6 by default.
   **Weight**: Enter the **Weight** for **Ex: 100**.

   ![image-95](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/63c24d24-8e47-4d50-91d2-841c36d14899)

98. Click on **Save** button.

    ![image-96](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/482db965-46d9-4993-a4e1-b4321ccf9a8c)

99. After clicking the **Save** button. And click on the **SAVE & APPLY** button.

    ![image-97](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2f3391c7-3ac9-4be8-be06-598463836c23)

100. Click on **SAVE & APPLY** then this will happen.

   ![image-98](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6ce3731a-898d-40c0-948d-4922f4d26b2e)

101. Then click on the **Add** button of **Track Script**.

   ![image-99](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/19e87116-0869-41dc-b515-90b8a0dd627b)

102. Fill these details
    **Name**: Enter the **Name** for **Ex:sender**
    **VRRP Script**: Select **sync_ha**.
    **Weight**: Enter the **Weight** for **Ex:100**.

  ![image-100](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f43fb55a-f8f6-4a71-a731-496066de3bbe)

103. Click on the **Save** button.

   ![image-121](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b4c9c6ed-1eb7-48f4-b0d4-141f8cd29507)

104. Go to the **Peers** button.

   ![image-102](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0c995ace-1b37-4108-82a4-f613b03bf939)

105. Click on the **Edit** button.

   ![image-103](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/050eb52f-251d-4926-b715-ef751c4a402b)

106. A new window will open. Then click the box of **Enable sync**.

   ![image-118](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/eecf43ff-8c4f-44cf-9c7a-954094687d8c)

107. Fill in the details.             
    **SSH Port**: Enter the port for **Ex:25321**.            
    **SSH Mode**: Select **Sender**.                         
    **sync Director**: The sync directory will appear by default.                     
    **Path SSH Private Key**: First go to your local terminal for the path to SSH private key.                                                    
    - They gave this command **ssh-keygen**.             
    - After giving the **ssh-keygen** command, enter 4 times and you will get the key.            
      ```
      # ssh-keygen 
      Generating public/private rsa key pair.

      Enter file in which to save the key (/root/.ssh/id_rsa): Enter passphrase (empty for no passphrase):            
      Enter same passphrase again:            
      Your identification has been saved in /root/.ssh/id_rsa             
      Your public key has been saved in /root/.ssh/id_rsa.pub                   
      The key fingerprint is:                 
      SHA256:4uHsxMYJOH1fmso+h5ew4sH0pAJgmBhQjeV7/PTD9bI root@sharad-Latitude-5480
      The key's randomart image is:                        
      +---[RSA 3072]----+
      |+..+.            |
      |oo...            |
      |=.  .            |
      |o  o o           |
      |. o = B S . .    |
      | . + &.B * . .   |
      |  . + @+=.+ . .  |
      |   ..*+.+  . o   |
      |   ..o=+    E    |
      +----[SHA256]-----+     ```            
   

 - Then click on **Select File**. After clicking on **Select File**, click on browse and select the file.

   ![image-104](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/05d4b411-5d1a-4b44-91a6-be396c0e40a3)

108. Click on the **Save** button.

   ![image-105](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c83676a1-06b9-4a87-bee1-e87c4833683f)

109. Then click the **SAVE & APPLY** button.

   ![image-106](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/12c969b5-3883-4358-8d85-70fd0a2f1dfe)

110. Go to the **Instant** tab.

   ![image-107](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b6b0e397-6985-4980-a04d-fc55261047b7)

111. Click on the **Edit** button.

   ![image-108](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/01143695-9668-40f9-8693-7b589ddb71da)

112. Go to the **Tracking** tab.

   ![image-109](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/91dc9ac5-34c1-4603-b5ab-b20768b502f0)

113. Navigate to the **Track Script** and choose the **sender**.

   ![image-110](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/99f88db9-9c3c-49f0-afcf-6f96a1ed9c31)

114. Click on the **Save** button.

   ![image-111](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/caf43e94-5858-4c48-8dff-747ac175041f)

    
 ## How to Sync configuration on Backup_node:

115.	Log in to the UI of **Backup_node** using the provided IP address.                                                        

  ![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f10832aa-1fa0-4488-a12d-f95ce01c57a7)

116. Go to the **Services** menu. Go to **Keepalived** inside the **Services** menu.

   ![image-92](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/96e4e5d6-5ad2-4252-826c-086129bca93b)

117. After clicking **Keepalived** a window will open. Go to the **Script** tab.

   ![image-93](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2f459080-9c0d-4e48-8651-8a99f3d86107)

118. A new window will open. Click on the **Add** button.

   ![image-94](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/463d5e15-535e-4f41-957c-d7ee00187858)

119. Fill in the details.                     
   **Name**: Enter the **Name** for **Ex: sync_ha**.                      
   **Script**: Click on **Select file** and choose file(By default file will appear there, you have to select).               
   **Interval**: Interval which will be 6 by default.                  
   **Weight**: Enter the **Weight** for **Ex: 100**.            

   ![image-95](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/63c24d24-8e47-4d50-91d2-841c36d14899)

120. Click on the **Save** button.

   ![image-96](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/482db965-46d9-4993-a4e1-b4321ccf9a8c)

121. After clicking the **Save** button. And click on the **SAVE & APPLY** button.

   ![image-97](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2f3391c7-3ac9-4be8-be06-598463836c23)

122. Click on **SAVE & APPLY** then this will happen.

   ![image-98](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6ce3731a-898d-40c0-948d-4922f4d26b2e)

123. Then click on the **Add** button of **Track Script**.

   ![image-99](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/19e87116-0869-41dc-b515-90b8a0dd627b)

124. Fill these details.                                            
    **Name**: Enter the **Name** for **Ex:receiver**.                            
    **VRRP Script**: Select **sync_ha**.                          
    **Weight**: Enter the **Weight** for **Ex:100**.                     
   
   ![image-112](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/52f8804e-36e1-494b-9455-92f0f62aa056)

125. Click on the **Save** button.

   ![image-122](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d4d42457-1208-4694-9907-867aba4e1d3d)


126. Go to the **Peers** button.

  ![image-117](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4f76f4f5-5562-426e-9244-6656747b6c27)

127. Click on the **Edit** button.

   ![image-120](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f17596cf-e307-4597-808f-36c0b3b81afe)

128. A new window will open. Then click the box of **Enable sync**.

   ![image-119](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d72d3b81-3871-4b67-ba47-1a5f1646f7d4)

129. Fill in the details.                      
    **SSH Port**: Enter the port for **Ex:25321**.                   
    **sync Mode**: Select **Receiver**.                  
    **SSH Public Key**: First go to your local terminal for the path to
    SSH private key.                      
    - They gave this command **cat/id-ras.pub**. If you give this command, a key will be generated, copy and paste there.         
    
   ![image-113](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c9238be2-92d2-4119-a83e-87e08b0d2eb9)

130. Click on the **Save** button.

  ![image-116](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b706685f-9563-4f07-8adf-82c3bb5f3d80)

131. Then click the **SAVE & APPLY** button.

   ![image-106](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/12c969b5-3883-4358-8d85-70fd0a2f1dfe)

132. Go to the **Instant** tab.

   ![image-77](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c6e92a82-5f09-42e1-8a8c-561005215395)

133. Click on the **Edit** button.

   ![image-108](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/01143695-9668-40f9-8693-7b589ddb71da)

134. Go to the **Tracking** tab.

   ![image-109](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/91dc9ac5-34c1-4603-b5ab-b20768b502f0)

135. Navigate to the **Track Script** and choose the **Receiver**.

   ![image-114](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4200fb06-b4e1-4db5-9bf9-1beb1b5d10c2)

136. Click on the **Save** button.

   ![image-115](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/936a83d1-ee94-45a7-91f5-e867e959c662) 

137. After synchronization, check that the config file of the master node should be in the backup node.
- Enter this path `/usr/share/keepalived/rsync` and check if 3 config files appear as shown in the image below then understand that synchronization is complete. And if it doesn't come then something is not synced.

  ![image-123](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fc61826e-865b-406f-8d05-69b6c44444f4)

    
    
    
   

