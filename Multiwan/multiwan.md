# Multiwan

## What is a Multiwan
## Why do we need a Multiwan
## How to configure Multiwan
1. Create the first two **CEs**. Go to **LAN-CE** and then go to Settings. Go to **settings** then a window will open go to **network** and configure **Addpter-1 and Addpter-2**. Select Bridge in Attach in **Addpter-1 and Internal Network in Addpter-2**. Name **multiwan2 in the last name**.
2. Next, click on the **OK** button.

   ![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/421c0883-3452-4dff-901b-bf30a628a14e)

3. After that, go to the cloud gateway **(https://dev.hi-clouds.com/login) and (https://beta1.hi-clouds.com/login)** and login to the **CE Device** menu and select the device and then go to the **interface** menu and click on the **edit** button of its interface.
4. If you click on **edit** button, then a new page of **Update Ethernet Interface** will be opened in which zone type will be **WAN** by default and similarly by opening another **Ethernet Internet**, if zone type is not **WAN** then select **WAN** and then click on **Update** button.

   ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2ca5fb26-4ed8-46e9-99af-55ca2c05117c)

5. After clicking update button **WAN** will show in both zone type.

   ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6a7e93f5-a561-4151-99a6-225580b2add0)

## Failour Configuration

6. Go to the **MUTLIWAN** menu and click on the **Configure MultiWan checkbox** there. If you click on the check box, two options will be shown **1. Select mode and 2. Notification email**. Select Failover in select mode. Enter your email in the notification email **Example sharadbhagwat121@gmail.com**. Email can also be provided for notification. There it will show yes in **Enabled** intrface **eth0 and eth1** and then click on **Save Config** button.

   ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cd15a6eb-6d16-4f71-9364-962bb06d496d)

7. Then click on the **Web termina** of the device. And login **Luci**. After login go to **MultiWAN Manager** and there in overview **eth1 and eth2** will show you online.

   ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/57f3cb40-0c69-4419-8c8c-0fee814fc382)

8. Next, now go to **Interface** tab. There will show you the configuration interface.

   ![image-6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/48781000-0f53-4879-a3a8-2bfa9d600bdd)

```
Note:- Mwan3 requires that all interfaces have a unique metric configured in /etc/config/network.

Names must match the interface name found in /etc/config/network.

Names may contain characters A-Z, a-z, 0-9, _ and no spaces-

Interfaces may not share the same name as configured members, policies or rules.

output of /etc/config/network file.
```

6. Member creation after configuring multi van in Cloud. So for member creation, go to the interface like eth0, eth1 and enable it. And to configure the option as follows.
   - Interface name:- eth0,eth1
   - Target IP:- we use this IP 8.8.8.8/4.2.2.2
   - Failure interval:- 5 seconds
   - Recovery interval:- 5 second
   - Ping interval: ping will be done 5 times
   - Ping timeout:- If the ping is not received in 2 seconds then the timeout will occur.
   - Metrics:- 2
   - Weight:- 2
   -enabled :- click on

   ![image-7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/88e3b8f5-a78b-435e-bd71-f8391db467d8)

   ![image-8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8c067dad-9a9b-4ae4-b490-f1e45e87a6a9)

7.  
