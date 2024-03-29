# Interface Configuration on Master_node: 

1.	Login to the UI of **Master_node** using the provided IP address.                                                        

  	![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/58c057cb-f18e-48b7-9fee-73eec24686b0)                

2. After login a new window will open. Go to the **Network** menu.                                                        

   ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6427ccdc-bff4-4f13-81a6-83e715910497)              

3.	Navigate to the **Interfaces** menu.                                                                                 

   ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/49991c68-41df-4ceb-827a-c70235203cce)              

4.	After login a new window will open. Select and **Edit** the **eth0** interface.                                                         

   ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0b0d67c1-c405-4281-b348-99273fb802fb)            

5. Click on **Edit** and a new window will open. Fill in the specified details given there.                                                                                                   
   **Protocol**:- Select Static Address in **Protocol**.                                                                                                                                   
   **Really switch protocol**:- There click on **Switch Protocol**.                                                                                                                      

   ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e00c1ede-81ed-42bc-a0bf-947d0ae798b2)            

6. After clicking on switch protocol there will be another information fillup.                                                                                      
   **IPv4 address**: Enter the **IPv4 address** for **Ex:192.168.1.102**.                                                                          
   **IPv4 netmask**: Select **IPv4 netmask** for **Ex: 255.255.255.0**.                                                                                                          
   **IPv4 gateway**: Enter the **IPv4 gateway** for **Ex: 192.168.1.1**.                                                                                                                   
   **IPv4 broadcast**: Enter the **IPv4 broadcast**. IPv4 broadcast comes by default.                                                                  

   ![image-6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ea148934-ffbb-4dda-9a1c-2acf2a88489d)

# Advance setting

7. Go to **Advance Setting**.                                                                                         

   ![image-7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6d446c22-fbad-4894-89d1-2055eefcf704)

8. A new window will open there. Add **Use custom DNS servers** there, enter, and click on the **+** icon, and it will be added.              

   ![image-8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2e1e38cb-3102-487a-b499-3057db1e7ed9)

9. Click on **Save** button. Click on the **Save** button then by default, you will return to the **interfaces** menu.                 

   ![image-9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f3fee8c7-ac5c-4304-8b43-c291b5e14268)

10. Navigate down and click on **ADD NEW INTERFACE**.                       

    ![image-10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/06bc0f32-5d29-495a-977b-e68dd899ac34)

11. A new window will open. Fill in the details.                                                                                           
    **Name**: Enter the **Name** for **Ex: eth 1**.                                                                                                               
    **Protocol**: Select the **Protocol** for **Ex: Static address**.                                                                                                           
    **Device**: Enter the **Device** for **Ex: eth 1**.                                                                                                                                    
     
    ![image-11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7042ae0b-739c-406c-bdaa-e9d9b5a23046)

12. Click on **CREATE INTERFACE** button.                                                                                                                                              

    ![image-12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a559587f-12e8-461c-8a0f-c887557f4696)

13. After clicking on the **CREATE INTERFACE** button a new window will open. Fill in the given details there.                      
   **IPv4 address**: Enter the **IPv4 address** for **Ex:100.100.100.1**.                                                                                                                 
   **IPv4 netmask**: Select **IPv4 netmask** for **Ex: 255.255.255.0**.                                                                                                                   
   **IPv4 gateway**: Enter the **IPv4 gateway** for **Ex: 192.168.1.1**. IPv4 gateway comes by default.                                                                                   
   **IPv4 broadcast**: Enter the **IPv4 broadcast** for **Ex: 100.100.100.255**. IPv4 broadcast comes by default.            

   ![image-13](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/068402dd-5a22-49b7-9831-07671a706c2c)

14. Click on **Save** button.
    ![image-14](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/3a878294-49af-4ee5-804c-22a91c0b9214)

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

21. Fill up the details to create an **IP Address**.                               
    **Name**: Enter the **Name** for **Ex:eth0**.                                                             
    **Address**: Enter the **Address** for **Ex:192.168.1.101**.                                            
    **Device**: Enter the **Device** for **Ex:eth0**.                                                             
    **Virtual Device Label** Enter the **Virtual Device Label** for **Ex: ha**.                           
    **Scope**: Enter the **Scope** for **Ex:Link**.                               

   ![image-21](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/146a67c4-f68d-4146-a614-403469dfa5be)

22. Click on the **Save** button.     

     ![image-22](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/3c3816ac-5133-4328-be35-38e3df4a263a)

23. Add and create an **eth2 IP Address** in the same way as you created an interface for eth0.                    
   **Name**: Enter the **Name** for **ex eth2**.                                                                         
   **Address**: Enter the **Address** for **ex 172.30.1.254**.                                                                       
   **Device**: Enter the **Device** for **ex eth2**.                                                                          
   **Virtual Device Label**:- Enter the **Virtual Device Label** for **ex: ha**.                                                    
   **Scope**:- Enter the **Scope** for **ex: link**.                                                                                    
24. After filling details click on **Save** button.                                                   

    ![image-44](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/25aab84c-de8c-43f8-9611-3bc101ff4965)


25. Click on **Interfaces** tab for **Track Interface**.                                                                     

     ![image-23](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/556cc821-0fba-4a4e-a2b0-459051e244a6)

26. After **Interfaces** a new window will open. Click on the **ADD** button.

    ![image-24](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ebe223e1-5d5b-4823-bde3-6f8c4ca50468)

27. Fill the details.                    
    **Name**: Enter the **Name** for **Ex:eth0_ha**.                 
    **Device**: Enter the **Device** for **Ex:eth0**.               
    **Weight**: Enter the **Weight** for **Ex:100**.              

    ![image-25](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/87f83bbe-0522-4de7-8d6f-cd2bc512940a)

28. Click on **Save** button.

    ![image-26](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8cb1010f-7c0f-4e41-96b0-ea1e3f7e36ec)


29. Same step for **eth1_ha**. And after clicking **Save & Apply**.

    ![image-27](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b23355e6-4569-494d-926f-26b84ec905d1)

# Add Backup_node as a peer

30. Click on **Peers** tab.

    ![image-28](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7a4fd6a0-031f-4686-b134-07588da988cd)

31. Click on **Add** button.

    ![image-29](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7bf78193-253b-45c3-b71d-b83cfa619177)

32. Fill the details.                                       
    **Name**: Enter the **Name** for **Ex:Backup_node**.                       
    **Peers Address**: Select the **Peers Address**. Navigate and Select custom enter IP 100.100.100.2 and press the **Enter** key.    

    ![image-30](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/db9a3715-4412-483e-a703-1cab11e35e76)

33. Click on **Save** button.

    ![image-31](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bbb27b56-38d2-4868-bfda-9f04a42a5262)

34. Click on **Instance** tab **VRRP Instance**.

    ![image-32](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1b8525e3-a86a-4709-85fb-f017b324f6cc)

35. After **Instance** a new window will open. Click on the **ADD** button.

    ![image-33](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bb4c4ea7-498e-46dc-9ed9-4f9617fd822e)

36. Fill up the details.                     
    **Name**: Enter the **Name** for **Ex:Master**.               
    **State**:Enter the **State** for **Ex:Master**.             
    **Interface**: Select the **Interface** for **Ex:eth1**.                    
    **Virtual Router ID**: Enter the **Virtual Router ID** for **Ex:100**.                    
    **Priority**: Enter the **Priority** for **Ex:100**.                     
    **Interval**: Enter the **Interval** for **Ex:1**.                           
    **Disable Preempt**: Enter the **Disable Preempt** for **Ex:na**.                         
    **Virtual IP Address**: Select the **Virtual IP Address**. Navigate Select eth0,eth2.                         

    ![image-34](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6b2dd9ff-cb5a-4b2a-a600-81c9ed959e85)

37. Click on **Save** button.

    ![image-35](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/121c2091-9c77-44bc-9243-dd135ad76555)

38. Go to the **Peer** and fill in the details.            
    **Unicast Source IP**: Navigate and Select **100.100.100.1**.           
    **Peer**: Peer select **Backup_node**.            
    **HA Authentication Type**: Select **Simple Password**.             
    **Password**: Enter **Password** for **Ex:admin**.                    

    ![image-36](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/3bd6a912-e097-4a00-a930-461958249525)

39. Click on **Save** button.                

    ![image-37](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e7bce692-9dbc-4d3e-969f-f3c837339acc)

40. Go to the **Track** and fill the details.                 
    **Track Interfaces**: Select **eth0_ha and eth1_ha**.               

    ![image-38](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5a628b56-287c-455c-ae0b-8c6b02e0220d)
41. Click on **Save** button.

    ![image-39](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ad03e3a1-2fe9-466b-9fc2-27f9e201a723)

42. Go to **System** menu.

    ![image-40](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4241620c-e323-45b4-b30c-55e92eed0e1b)

43. After going to **System** menu go to **Startup** menu in it located.

   ![image-41](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/27798e9c-578d-4d71-a96a-e7970cf3ad20)
   
44. Click on the **ENABLED** button to keepalive service and click on **RESTART** button Service.

    ![image-42](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4fd4e511-555d-40de-a067-22e31d04feba)

45. Check service status in CE Command line **ps | grep keep**.
```
3643 root      2188 S    /bin/sh /usr/bin/keepalived-rsync-inotify Backup Mas
4783 root      3428 S    {keepalive.sh} /bin/sh /usr/bin/keepalive.sh
11648 root      5812 S    /usr/sbin/keepalived -n -f /tmp/keepalived.conf
11649 root      5816 S    {keepalived_vrrp} /usr/sbin/keepalived -n -f /tmp/ke
30512 root      1120 R    grep keep
```
46. Verify Overview Status. Check if the status on both Master_node and Backup_node matches the expected status as provided.
47. Now go to **Services** menu and click on **Keepalived**.

    ![image-43](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7dc7af51-96d1-427b-941d-74a05ab1fb63)


48. Entering the ip addr command in the Master node will show an output like this. **eth0 (192.168.1.101) and eth2 (192.168.254.254)** as virtual IP will be used. And then after off the Master_node, it will switch to the configuration Backup node.

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
