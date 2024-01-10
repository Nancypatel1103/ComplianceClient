# WhiteList & BlackList
<!-- TOC -->

- [WhiteList & BlackList](#whitelist--blacklist)
    - [What is WhiteList & BlackList](#what-is-whitelist--blacklist)
    - [Why do we need WhiteList & BlackList](#why-do-we-need-whitelist--blacklist)
    - [How to configure WhiteList & BlackList](#how-to-configure-whitelist--blacklist)
    - [Conclusion](#conclusion)

<!-- /TOC -->
## What is WhiteList & BlackList
Within the Cloud Gateway, a Whitelist & Blacklist is an array of configurations that permits specific features or objects but limits the access of others. Selectively allowed objects, allowed domains, and allowed IP addresses are all instances of Whitelist settings in the context of a Cloud Gateway configuration.
## Why do we need WhiteList & BlackList
To regulate and oversee the passage of traffic to the Cloud Gateway, whitelist & Blacklist configurations are required. They provide an individual way of network access that allows users to specify which domains, IP addresses, and subdomains can be utilized or banned. Cloud Gateway services are employed effectively, securely, and in compliance thanks to the Whitelist & Blacklist.
## How to configure WhiteList & BlackList
1. First you have to link CE with PE. How to link CE with PE is explained here ([How Enable CGW](#how-enable-cgw)).
2. Click on the **GATEWAY** menu located on the left side.
   ![image 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/84bf2c8a-30ce-45b0-9c48-d2394f7609ce)

3. After clicking on the **GATEWAY** menu, a new window will appear.
  ![image 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9e2cba70-b85d-4c5f-af14-73af76531cf1)

4. Click on the box of **Cloud Gateway**. How to Select a Customer Public IP after clicking on the cloud gateway box is explained here ([How Enable CGW](#how-enable-cgw)).
   ![image 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b6785647-151b-4d2a-8f87-c13f834a8785)
   
5. Then choose select mode. There you will find **1. Global 2. Full 3. Selective** three modes.
   ![image 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cadc0257-7112-4a4f-a717-dfa9d2197bb3)

6. Click on **Global** mode if you want to use **Global** mode. **Global** mode includes all types of websites.
7. Click on **Full** mode to utilize **Full mode**. **Full** mode includes all types of Domains.
8. Click on **Selective** mode if you want to use **Selective** mode. 
9. After that **Enter Allowed Domains**, The traffic of the website you provide here will be through the cloud gateway. For **Ex: www.google.com**.
   ![image 5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/98f2b235-4e9f-44db-a69e-86e8cd9eb7f8)
   
10. Then **Enter Blocked Domains**, Enter the Blocked Domains that you do not want to allow the subdomain of the allowed domain. The website traffic you provide will not go through the cloud gateway. For **Ex: www.facebook.com**.
   ![image 6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f9023c62-e31b-4b12-885b-ce8a810351c7)

11. Then Enter **Allowed IP**. The Public IP you want to send the request to should be written here in the **Allowed IP**. For **Ex: 103.78.41.6**.
    ![image 7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/750461e3-8b07-4e79-aaa8-6db0c8bcbb23)

12. Enter **Blocked IP**. Here type the public IP you don't want to send a request to CGW in Enter **Blocked IP**. So the CGW request from that IP will not go through. For **Ex: 182.168.1.1**.
    ![image 8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bb0503b9-2346-46fb-9dac-e19cb033da64)

13. After selecting **Full** mode, type the domain don't want to allow in the enter block domain. For **Ex: www.facebook.com**.
    ![image 11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/45f6f15d-28f8-40bc-a4ce-9d5d708787cc)
14. In selective mode, you have to enter the domain you want to run through the gateway in Allow Domains and the domains you don't want to allow in Block Domains.
15. After Enter Allowed Domains for ex: 1. www.google.com 2. www.facebook.com and Enter Blocked domains for ex: www.netflix.com.
    ![image 12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7dc671dc-5b48-4be5-8c25-c3e84afd0674)

16. Now click on **Save Config**.
    ![image 9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/72d4f776-2172-4ef4-9d26-0dd49ff5b8b6)

17. click on **Save Config** and you will get the Cloud gateway is enabled successfully message.
    ![image 10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c4132a2c-f1c2-4e40-af3a-feb37379a555)

## Conclusion
As part of the Cloud Gateway, a Whitelist and Blacklist are essential options that permit access to some functions alone while limiting access to others. Restricted items, allowed domains, and approved IP addresses are all included in these setups.
