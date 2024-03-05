# Interface Configuration on Backup_node:

1.	Login to the UI of **Master_node** using the provided IP address.                                                                                                           

  	![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/dea0fb31-1c67-494c-969d-e13deb067786)               

2. After login a new window will open. Go to the **Network** menu.                                                                                             

    ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fac55ed4-4994-4085-97e6-e3c066b33d9b)

3.	Navigate to the **Interfaces** menu.                                                                                                                                               

   ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5dc59558-8977-43f0-ba86-44bb8eae501f)
            

4.	After login a new window will open. Select and **Edit** the **eth0** interface.                                                                                     

   ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1003ded5-5d5b-4817-9da9-12f0e5b9b165)           

5. Click on **Edit** and a new window will open. Fill in the specified details given there.                                                                                                   
   **Protocol**:- Select Static Address in **Protocol**.                                                                                                                                  
   **Really Switch Protocol**:- There click on **Switch Protocol**.                                                                                                                         
   ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ca057636-4c49-4c92-8634-bfdae5b017f6)

6. After clicking on switch protocol there will be another information fillup.                                                                        
   **IPv4 address**: Enter the **IPv4 address** for **Ex:192.168.1.103**.                                                                          
   **IPv4 netmask**: Select **IPv4 netmask** for **Ex: 255.255.255.0**.                                                                                                          
   **IPv4 gateway**: Enter the **IPv4 gateway** for **Ex: 192.168.1.1**.                                                                                                                  
   **IPv4 broadcast**: Enter the **IPv4 broadcast**. IPv4 broadcast comes by default.                                                                  

  ![image-6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8b212010-5e8d-48fc-988d-d3202a6f708f)


# Advance setting

7. Go to **Advance setting**.                                                                                         

   ![image-7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5aed8203-bfc7-4705-a08f-84bc3919102b)

8. A new window will open there. Add **Use custom DNS servers** there, enter and click on the **+** icon, and it will be added.              

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
    ![image-14](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b6c3c0f1-5d40-44c2-a49e-054ab7e0d7a0)

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

21. Fill up the details to create an **IP Address**.                         
    **Name**: Enter the **Name** for **Ex:eth0**.                                                                             
    **Address**: Enter the **Address** for **Ex:192.168.1.101**.                                                            
    **Device**: Enter the **Device** for **Ex:eth0**.                                                                           
    **Virtual Device Label** Enter the **Virtual Device Label** for **Ex: ha**.                                   
    **Scope**: Enter the **Scope** for **Ex:Link**.                                                   

    ![image-21](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/601c3a94-58e9-41c0-b19d-47166855f9c5)

22. Click on the **Save** button.     

     ![image-22](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/40bbad2f-1c6c-49ad-b7f2-4f65f409f111)


23. Add and create an **eth3 IP Address** in the same way as you created an interface for eth0.                      
   **Name**: Enter the **Name** for **ex eth3**.                                                                         
   **Address**: Enter the **Address** for **ex 172.30.2.254**.                                                                       
   **Device**: Enter the **Device** for **ex eth3**.                                                                          
   **Virtual Device Label**:- Enter the **Virtual Device Label** for **ex: ha**.                                                    
   **Scope**:- Enter the **Scope** for **ex: link**.                                                                                    
24. After filling details click on **Save** button.                                                   

    ![image-44](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7a615af7-b834-49eb-896a-117e7eb1397b)


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


29. Same step for **eth1**. And after clicking **Save & Apply**.

    ![image-27](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/479abd3f-6a8f-4433-83a3-283121d933e4)

# Add Backup_node as a peer

30. Click on **Peers** tab.

    ![image-28](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a16dc2b3-d709-48c4-9c03-7c0507e70fe2)

31. Click on **Add** button.

    ![image-29](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c1b614e0-1b97-4fec-9678-697fc1b5c48c)

32. Fill the details.               
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
    **Disable Preempt**: Enter the **Disable Preempt** for **Ex:na**.                       
    **Virtual IP Address**: Select the **Virtual IP Address**. Navigate Select **eth0,eth2**.               

    ![image-34](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c082e605-9218-4127-b223-6b2abc14828a)              

37. Click on **Save** button.

    ![image-35](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/07976a49-be73-474e-b78c-7db7833bf6db)                                

38. Go to the **Peer** and fill in the details.                
    **Unicast Source IP**: Navigate and Select **100.100.0.30**.               
    **Peer**: Peer select **Master_node**.               
    **HA Authentication Type**: Select **Simple Password**.             
    **Password**: Enter **Password** for **Ex:admin**.           

    ![image-36](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/09a8cda8-4d2c-4930-9097-bef150c61c61)

39. Click on **Save** button.

    ![image-37](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/60d4bbe2-f974-4ee0-9a55-38a09bd2ebf0)

40. Go to the **Track** and fill the details.
    **Track Interfaces**: Select eth0_ha and eth1_ha

    ![image-38](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5a628b56-287c-455c-ae0b-8c6b02e0220d)

41. Click on **Save** button.

    ![image-39](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ad03e3a1-2fe9-466b-9fc2-27f9e201a723)

42. Go to **System** menu of Backup_node.

    ![image-40](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4241620c-e323-45b4-b30c-55e92eed0e1b)

43. Go to **Startup** menu.

   ![image-41](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/27798e9c-578d-4d71-a96a-e7970cf3ad20)
   
44. Click on the **ENABLED** button to keepalive service and click on **RESTART** button Service.

    ![image-42](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4fd4e511-555d-40de-a067-22e31d04feba)

45. Check service status in CE Command line **ps | grep keep**.
```
root@Master_node:~# ps | grep keep
3643 root      2188 S    /bin/sh /usr/bin/keepalived-rsync-inotify Backup Mas
4783 root      3428 S    {keepalive.sh} /bin/sh /usr/bin/keepalive.sh
11648 root      5812 S    /usr/sbin/keepalived -n -f /tmp/keepalived.conf
11649 root      5816 S    {keepalived_vrrp} /usr/sbin/keepalived -n -f /tmp/ke
30512 root      1120 R    grep keep
```
46. Verify Overview Status. Check if the status on both Master_node and Backup_node matches the expected status as provided.
47. Now go to **Services** menu and click on **Keepalived**.

    ![image-43](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/dd7c7691-431b-48e7-aa58-4c8d5be78c05)

48. turn off the master node  and check the status of the backup node. When we turn off the master node, everything will be moved to the backup node. When we turn on the master node, it will move to the master node and the place of master/backup will be replaced by backup/backup.

    ![image-43](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/761f945b-1d27-4102-87e0-341453b1702f)

49. After turning off the **Master_node**, Verify the updated IP addresses using the IP addr show command on **Backup_node's** terminal.

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



    

    
