#  MultiWAN

## What is a MultiWAN
A MultiWAN configuration enables a network to use multiple Internet connections simultaneously. It is designed to improve the reliability and efficiency of Internet connections by distributing network traffic over multiple WAN links. MultiWAN routers have the ability to balance load, provide fault tolerance for fail-safe backup connections, and pool bandwidth from different sources for improved performance. This is especially useful for companies and industries where internet access is essential.

## Why do we need a MultiWAN
We need a MultiWAN network to maintain our internet connection. MultiWAN provides redundancy by switching to an alternate Internet connection in case of failure, minimizing downtime. Its load balancing helps the network make more use of its available bandwidth by evenly distributing traffic across multiple connections. Improved usability, faster speeds, and efficient use of network resources are the primary benefits for businesses that rely on stable Internet connections.

## Set the configuration MultiWAN

1. After that, go to the cloud gateway **(https://dev.hi-clouds.com/login) and (https://beta1.hi-clouds.com/login)** and login to the **CE Device** menu and select the device and then go to the **interface** menu and click on the **edit** button of its interface.

   ![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/72876f7b-3cb8-4716-b6cb-a2853245fdbb)

2. If you click on the **edit** button, then a new page of **Update Ethernet Interface** will be opened in which the zone type will be **WAN** by default and similarly by opening another **Ethernet Internet**, if the zone type is not **WAN** then select **WAN** and then click on **Update** button.

   ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2ca5fb26-4ed8-46e9-99af-55ca2c05117c)

5. After clicking the update button **WAN** will show in both zone types.

   ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d60b1e87-ecc1-45f9-b2db-1409960eedc1)


### Failour Configuration

6. Go to the **MUTLIWAN** menu and click on the **Configure MultiWan checkbox** there. 

   ![image-16](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4588fd5e-1260-4134-96e6-a52ddb51c3fe)

7. If you click on the check box, two options will be shown **1. Select mode and 2. Notification email**. Select Failover in select mode. Enter your email in the notification email **Example demo123@gmail.com**. Email can also be provided for notification. There it will show yes in **Enabled** interface **eth0 and eth1** and then click on the **Save Config** button.

   ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ac8a2a9a-0eeb-4ad8-8ffc-ddc5ee824c4e)


8. Then click on the **Web terminal** of the device. And login **Luci**. After login go to **MultiWAN Manager** and there in the overview **eth1 and eth2** will show you online.

   ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4b1d4311-7251-4f7c-9de3-afe76e1327f9)

9. Next, now go to the **Interface** tab. It will show you the configuration interface.

   ![image-6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f41bdd91-0443-4201-9721-ce0577a05bcf)


10. Member creation after configuring MultiWAN in the Cloud. So for member creation, go to the interface like eth0, eth1 and enable it. And to configure the option as follows. eth0 and eth1 will fail after 5 seconds. Then recovery will be tried for 5 seconds. And then after 2 seconds or minutes, it will ping time out.
   - Interface name:- eth0,eth1
   - Target IP:- we use this IP 8.8.8.8/4.2.2.2
   - Failure interval:- 5 seconds
   - Recovery interval:- 5 second
   - Ping interval: ping will be done 5 times
   - Ping timeout:- If the ping is not received in 2 seconds then the timeout will occur.
   - Metrics:- 2
   - Weight:- 2                                       
   - enabled:- click on

   ![image-7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/197108d3-3ec3-4984-8d7d-d6aa116739d1)

   ![image-8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/982b39d1-65bd-488c-8fb4-4f3d2644fe12)


11. Then go to Luci go to **MultiWAN Manager** and click on Member tab. If you go to the **Member** tab, you will be shown two members that have been created in the cloud. Here the value of Metrics will be less. Its priority will be first. Metrics means route path.
   - Name: eth1_m1_w1             
   - Interface: eth1              
   - Metrics: 1                   
   - Weight: 1                     
` Note:- Members are profiles attaching a metric and weight to an MWAN interface. Names may contain characters A-Z, a-z, 0-9, _, and no spaces.
Members may not share the same name as configured interfaces, policies, or rules.`

     ![image-9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7d3cc9c0-14b5-4459-9a89-c23784156924)


11. Next go to the **Policies** tab. There you will see failover policies. When a **CE** is closed with the help of policies, it automatically converts to its other CE. It is shown in the policies.

   ![image-10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0d2b30ed-21c7-4f17-bd60-4d3f344338a5)

12. Then navigate to the **Rules** tab. There you will find the rules. In the rules, its **name, protocol, source address, source port, destination address, destination port, and policy assigned** will be found, which specifies the rules. And will use the traffic in a specific way.

    ![image-11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cbb1307e-b8d2-49bf-a9d6-add0eba5abab)

### Load Balance Configuration

1. Go to the **MUTLIWAN** menu and click on the **Configure MultiWan checkbox** there. If you click on the check box, two options will be shown **1. Select mode and 2. Notification email**. Select Failover in select mode. Enter your email in the notification email **Example demo123@gmail.com**. Email can also be provided for notification. There it will show yes in **Enabled** interface **eth0 and eth1** and then click on the **Save Config** button. There is no need to edit here as it is already configured and if not done then you can configure it by clicking edit. For that you can follow the above failure steps.

   ![image-12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d09ff77e-f5da-4638-9c8c-9bba4e0859bf)

2. After creating the **load balance policy** in the cloud, then go to Luci and navigate to **MultiWAN Manager** The entry in Member will appear in Luci. Which is shown in the screenshot. In which the weight is 2, it is possible to have the same weight across interfaces. Otherwise, the load will not balance. A member in **Luci** is named eth1_m1_w2 and eth0_m1_w2.

   ![image-13](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/436cb6b9-e036-4acc-81b6-15c7ab1047ee)


3. After navigating to the **Policies** tab. You will see the You will see the entry of the load balance in the multi-wan manager's policy menu inside Luci.

   ![image-14](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/75c491e4-1cbd-4862-8c86-d649e3184264)


4. But, then go to the **Rules** tab, there you will find the rules. In the rules, its **name, protocol, source address, source port, destination address, destination port, and assigned policy** will be found, which specifies the rules. and will use the traffic in a specific way. Rules for load balancing are created in the Rules menu of Lucy Multi-Van Manager.

   ![image-15](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1e1bfc2c-0cba-469d-bd0f-f5eddfc1d15c)





