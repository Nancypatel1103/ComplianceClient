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

6. Go to the **MUTLIWAN** menu and click on the **Configure MultiWan checkbox** there. If you click on the check box, two options will be shown **1. Select mode and 2. Notification email**. Select Failover in select mode. Enter your email in the notification email **Example sharadbhagwat121@gmail.com**. Email can also be provided for notification. There it will show yes in **Enabled** interface **eth0 and eth1** and then click on the **Save Config** button.

   ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cd15a6eb-6d16-4f71-9364-962bb06d496d)

7. Then click on the **Web terminal** of the device. And login **Luci**. After login go to **MultiWAN Manager** and there in the overview **eth1 and eth2** will show you online.

   ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/57f3cb40-0c69-4419-8c8c-0fee814fc382)

8. Next, now go to the **Interface** tab. It will show you the configuration interface.

   ![image-6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/48781000-0f53-4879-a3a8-2bfa9d600bdd)


9. Member creation after configuring MultiWAN in the Cloud. So for member creation, go to the interface like eth0, eth1 and enable it. And to configure the option as follows.
   - Interface name:- eth0,eth1
   - Target IP:- we use this IP 8.8.8.8/4.2.2.2
   - Failure interval:- 5 seconds
   - Recovery interval:- 5 second
   - Ping interval: ping will be done 5 times
   - Ping timeout:- If the ping is not received in 2 seconds then the timeout will occur.
   - Metrics:- 2
   - Weight:- 2                                       
   - enabled:- click on

   ![image-7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/88e3b8f5-a78b-435e-bd71-f8391db467d8)

   ![image-8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8c067dad-9a9b-4ae4-b490-f1e45e87a6a9)

10. Then go to Luci go to **MultiWAN Manager** and click on Member tab. If you go to the **Member** tab, you will be shown two members that have been created in the cloud. Here the value of Metrics will be less. Its priority will be first. Metrics means route path.
   - Name: eth1_m1_w1             
   - Interface: eth1              
   - Metrics: 1                   
   - Weight: 1                     
` Note:- Members are profiles attaching a metric and weight to an MWAN interface. Names may contain characters A-Z, a-z, 0-9, _, and no spaces.
Members may not share the same name as configured interfaces, policies, or rules.`

     ![image-9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/673869d8-1b1e-41ba-911c-bfc6dcc6c704)

11. Next go to the **Policies** tab. There you will see failover policies. When a **CE** is closed with the help of policies, it automatically converts to its other CE. It is shown in the policies.

   ![image-10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/65805448-aabb-4222-8fcb-bba10a1797d4)

12. Then navigate to the **Rules** tab. There you will find the rules. In the rules, its **name, protocol, source address, source port, destination address, destination port, and policy assigned** will be found, which specifies the rules. And will use the traffic in a specific way.

    ![image-11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1e5daffc-754d-4fd4-be9f-31be8bfd23d0)

### Load Balance Configuration

1. Go to the **MUTLIWAN** menu and click on the **Configure MultiWan checkbox** there. If you click on the check box, two options will be shown **1. Select mode and 2. Notification email**. Select Failover in select mode. Enter your email in the notification email **Example sharadbhagwat121@gmail.com**. Email can also be provided for notification. There it will show yes in **Enabled** interface **eth0 and eth1** and then click on the **Save Config** button.

   ![image-12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b38bd002-9e28-43fb-b01b-0dcff9727534)

2. After creating the **load balance policy** in the cloud, then go to Luci and navigate to **MultiWAN Manager** The entry in Member will appear in Luci. Which is shown in the screenshot. In which the weight is 2, it is possible to have the same weight across interfaces. Otherwise, the load will not balance. A member in **Luci** is named eth1_m1_w2 and eth0_m1_w2.

   ![image-13](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b096c1a4-e04a-4de1-911b-7aad5f927e7e)

3. After navigating to the **Policies** tab. You will see the You will see the entry of the load balance in the multi-wan manager's policy menu inside Luci.

   ![image-14](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/edf5c441-4793-4ac1-82a6-f72e4fcd4fbc)

4. But, then go to the **Rules** tab, there you will find the rules. In the rules, its **name, protocol, source address, source port, destination address, destination port, and assigned policy** will be found, which specifies the rules. and will use the traffic in a specific way. Rules for load balancing are created in the Rules menu of Lucy Multi-Van Manager.

   ![image-15](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/180034ce-163b-4e6a-8ed3-194178f3a4af)

5. The details of the mwan3 configuration can be checked in the following files.`/etc/config/mwan3`, `/etc/config/network`,`last_config_response.json.`
``` sh
root@manual-test:~# cat /etc/config/mwan3

  

config globals 'globals'

option mmx_mask '0x3F00'

option local_source 'lan'

option mode 'LOAD_BALANCE'

option enabled '1'

  

config rule 'DEFAULT_HTTPS'

option family 'ipv4'

option sticky '1'

option proto 'tcp'

option dest_ip '0.0.0.0/0'

option dest_port '443'

option use_policy 'LOAD_BALANCE'

  

config rule 'DEFAULT_ANY'

option family 'ipv4'

option dest_ip '0.0.0.0/0'

option use_policy 'LOAD_BALANCE'

  

config interface 'eth1'

option enabled '1'

list track_ip '8.8.8.8'

list track_ip '4.2.2.2'

option interval '5'

option timeout '2'

option failure_interval '5'

option recovery_interval '5'

option down '1'

option up '3'

option initial_state 'online'

option track_method 'ping'

option reliability '1'

option count '1'

option size '56'

option max_ttl '60'

option check_quality '0'

  

config member 'eth1_m1_w1'

option interface 'eth1'

option metric '1'

option weight '1'

  

config policy 'FAIL_OVER'

list use_member 'eth1_m1_w1'

list use_member 'eth0_m2_w1'

  

config interface 'eth0'

option enabled '1'

list track_ip '8.8.8.8'

list track_ip '4.2.2.2'

option interval '5'

option timeout '2'

option failure_interval '5'

option recovery_interval '5'

option down '1'

option up '3'

option initial_state 'online'

option track_method 'ping'

option reliability '1'

option count '1'

option size '56'

option max_ttl '60'

option check_quality '0'

  

config member 'eth0_m2_w1'

option interface 'eth0'

option metric '2'

option weight '1'

  

config interface 'wlm0'

option enabled '0'

list track_ip '8.8.8.8'

list track_ip '4.2.2.2'

option interval '5'

option timeout '2'

option failure_interval '5'

option recovery_interval '5'

option down '1'

option up '3'

option initial_state 'online'

option track_method 'ping'

option reliability '1'

option count '1'

option size '56'

option max_ttl '60'

option check_quality '0'

  

config member 'eth1_m1_w2'

option interface 'eth1'

option metric '1'

option weight '2'

  

config policy 'LOAD_BALANCE'

list use_member 'eth1_m1_w2'

list use_member 'eth0_m1_w2'

  

config member 'eth0_m1_w2'

option interface 'eth0'

option metric '1'

option weight '2'

```

  

output of `/etc/config/netwrok`

  

  

```sh

root@manual-test:/tmp# cat /etc/config/network

  

config interface 'loopback'

option device 'lo'

option proto 'static'

option ipaddr '127.0.0.1'

option netmask '255.0.0.0'

  

config globals

option packet_steering '1'

  

config interface 'eth0'

option device 'eth0'

option proto 'dhcp'

option metric '1'

option ip4table '1'

option peerdns '0'

option default_wan '1'

list dns '8.8.8.8'

list dns '4.2.2.2'

option disabled '0'

option mtu '1500'

  

config interface 'eth2'

option device 'eth2'

option disabled '0'

option mtu '1500'

option proto 'static'

option ipaddr '172.1.30.3'

option netmask '255.255.255.0'

  

config rule

option priority '901'

option lookup 'main'

  

config interface 'eth1'

option disabled '0'

option device 'eth1'

option proto 'dhcp'

option metric '2'

option ip4table '2'

option mtu '1500'

  

config interface 'wlm0'

option disabled '1'

option proto '3g'

option pppname 'wlm0'

option device 'ttyUSB0'

option apn 'comgt'

option ipv6 '0'

option delegate '0'

option metric '3'

option ip4table '3'

  

config route '4f8253ad3b144cfca9f81e3223664117'

option target '172.1.30.3'

option netmask '255.255.255.0'

option gateway '172.1.30.1'

option metric '0'

option proto 'static'

option interface 'eth2'

  

```
output of `last_config_response.json`

```sh
root@manual-test:/tmp# cat last_config_response.json | jq .multiWanV2

{

"enable": true,

"mode": "LOAD_BALANCE",

"notificationEmails": [],

"wanInterfaces": null,

"wanInterfacesConfig": {

"pppoe0": {

"interfaceName": "pppoe0",

"targetIps": [

"8.8.8.8",

"4.2.2.2"

],

"failureInterval": 5,

"recoveryInterval": 5,

"pingInterval": 5,

"pingTimeout": 2,

"multiWANMetric": 3,

"multiWANWeight": 2,

"enable": false

},

"eth1": {

"interfaceName": "eth1",

"targetIps": [

"8.8.8.8",

"4.2.2.2"

],

"failureInterval": 5,

"recoveryInterval": 5,

"pingInterval": 5,

"pingTimeout": 2,

"multiWANMetric": 1,

"multiWANWeight": 2,

"enable": true

},

"eth0": {

"interfaceName": "eth0",

"targetIps": [

"8.8.8.8",

"4.2.2.2"

],

"failureInterval": 5,

"recoveryInterval": 5,

"pingInterval": 5,

"pingTimeout": 2,

"multiWANMetric": 2,

"multiWANWeight": 2,

"enable": true

},

"wlm0": {

"interfaceName": "wlm0",

"targetIps": [

"8.8.8.8",

"4.2.2.2"

],

"failureInterval": 5,

"recoveryInterval": 5,

"pingInterval": 5,

"pingTimeout": 2,

"multiWANMetric": 2,

"multiWANWeight": 2,

"enable": false

}

}

}

```

### Backend

- mwan3 The entire process passes through the mwan3 service.

`/etc/init.d/mwan3 start,stop,restart`

```sh
root@manual-test:/tmp# /etc/init.d/mwan3 status

running

```

- you can also check by CLI with the mwan3 command.


```sh

root@manual-test:~# mwan3

Syntax: mwan3 [command]

Available commands:

start Load iptables rules, ip rules and ip routes

stop Unload iptables rules, ip rules and ip routes

restart Reload iptables rules, ip rules and ip routes

ifup <iface> Load rules and routes for specific interface

ifdown <iface> Unload rules and routes for specific interface

interfaces Show interfaces status

policies Show currently active policy

connected Show directly connected networks

rules Show active rules

status Show all status

internal <ipv4|ipv6> Show internal configuration <default: ipv4>

use <iface> <cmd> Run a command bound to <iface> and avoid mwan3 rules

```

```sh

root@manual-test:~# mwan3 status

Interface status:

interface eth1 is online 00h:25m:17s, uptime 00h:25m:24s and tracking is active

interface eth0 is online 00h:25m:25s, uptime 00h:25m:37s and tracking is active

interface wlm0 is offline and tracking is down

  

Current ipv4 policies:

FAIL_OVER:

eth1 (100%)

LOAD_BALANCE:

eth0 (50%)

eth1 (50%)

  

Current ipv6 policies:

FAIL_OVER:

unreachable

LOAD_BALANCE:

unreachable

  

Directly connected ipv4 networks:

172.1.30.255

192.168.1.0

192.168.1.255

172.1.30.3

172.30.4.165

127.0.0.0/8

192.168.1.4

127.0.0.0

172.1.30.0

172.30.4.0

172.30.4.255

127.0.0.1

172.1.30.0/24

224.0.0.0/3

127.255.255.255

  

Directly connected ipv6 networks:

  

Active ipv4 user rules:

185 11100 S DEFAULT_HTTPS tcp -- * * 0.0.0.0/0 0.0.0.0/0 multiport dports 443

163 12612 - LOAD_BALANCE all -- * * 0.0.0.0/0 0.0.0.0/0

  

Active ipv6 user rules:

```

the output shows mwan3 status in Details. 

- ping use with command `mwan3 use eth0 ping -4 google.com` output will be like this.

```sh

root@manual-test:~# mwan3 use eth0 ping -4 google.com

could not find family for eth0. Using ipv4.

Running 'ping -4 google.com' with DEVICE=eth0 SRCIP=192.168.1.4 FWMARK=0x3f00 FAMILY=ipv4

PING google.com (142.250.76.206): 56 data bytes

64 bytes from 142.250.76.206: seq=0 ttl=60 time=14.012 ms

64 bytes from 142.250.76.206: seq=1 ttl=60 time=13.390 ms

64 bytes from 142.250.76.206: seq=2 ttl=60 time=14.927 ms

64 bytes from 142.250.76.206: seq=3 ttl=60 time=14.979 ms

64 bytes from 142.250.76.206: seq=4 ttl=60 time=12.831 ms

64 bytes from 142.250.76.206: seq=5 ttl=60 time=14.128 ms

^C

--- google.com ping statistics ---

6 packets transmitted, 6 packets received, 0% packet loss

round-trip min/avg/max = 12.831/14.044/14.979 ms

```

  


