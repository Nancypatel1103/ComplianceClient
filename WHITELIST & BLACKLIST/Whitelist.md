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
1. First you have to link CE with PE. How to link CE with PE is explained here ((https://github.com/Nancypatel1103/ComplianceClient/blob/47065fc2162d3f32cd5b7ef4fd9305a950ace780/CLOUD_GATEWAY/CLOUD_GATEWAY.MD)). 
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
# CGW
<!-- TOC -->

- [CGW](#cgw)
    - [What is CGW](#what-is-cgw)
    - [Why do we need a CGW](#why-do-we-need-a-cgw)
    - [How Enable CGW](#how-enable-cgw)
    - [How to Disable CGW](#how-to-disable-cgw)
    - [Conclusion](#conclusion)

<!-- /TOC -->

## What is CGW
A gateway is a network point that acts as access to another network. With the help of the CLOUDS gateway, you can Enable and Disable your gateway. You can also select different modes. It has different modes (1) Global mode: As much as there will be global traffic. Global means that whatever traffic outside will be through the CGW. (2) Full mode: Full mode means all global, local, and domain traffic will be through the CGW. and (3) Selective mode: The website and domain you select will use the CGW and the rest will use the local.

## Why do we need a CGW
Gateways play a crucial role in CLOUD computing by facilitating communication and data transfer between disparate networks, making it possible for different systems to work together seamlessly. A Gateway can enable communication between different networks, facilitating data transfer and integration.

## How Enable CGW
Before enabling the cloud gateway, it is necessary to connect the CE and PE. So first check if CE and PE are connected or not. If the CE and PE are not connected then what to do is explained below.

1. Go to beta1. hi-clouds (https://beta1.hi-clouds.com/login) and **SIGN IN** by entering the admin permission username and password.                                                                        
   ![image 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7d46c233-5c85-4da1-a60e-ab01b3dc2240)

2. When you **SIGN IN**, you will reach the dashboard by default.
   ![image 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5658f1a5-44c8-458b-9d04-fd4af5421a25)

3. Then Click on the **CE Devices** menu located on the left side.
   ![image 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/90053de6-32c5-4989-bd39-654c60870d42)

4. You will click on **CE Devices**, there you will see a list of **Devices**.
   ![image 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d297ed51-e631-4dcb-a18a-0bf837b421fd)

5. Go to the search tab located on the right side. 
   ![image 5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/774d6eec-dfae-4cca-9668-6096e63c1345)

6. Go there and search your Device name. For **example: jaymin-home-new-x86**.
   ![image 6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8ddb4d09-25ce-4327-9182-265924f200e1)

7. After that you will enter, and there you will find your Device, Click on it.
   ![image 7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/49fe9b4a-ff9b-4a23-b379-4e546bcb9a87)

8. By clicking there you will see a summary of the **CE Device**.
   ![image 8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5fb4f255-8b4a-46c8-a5bf-ef36e206feb0) 

9. Click on **VPN** there. Which is located in the INTERFACES menu of the Device.
   ![image 9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/93085c6e-6f66-4988-b37b-0cbe68ac2b59)

10. After clicking on **VPN**, a new window will open, there is **Link PE** tab on the right side, click on it.
   
       ![image 10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/48ad5254-91e5-4ef0-8e67-7f703fa3530b)

11. After click on the **Link PE**, there a new window will open.

       ![image 11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5139159d-9bc8-4bb1-8de1-8d68eecf70dd)

12. Select **Region** and **PE Device IP**.To select the region you have to write the code which is different country-wise. For **Example: there is IND for India**.
       
     ![image 12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b9a11745-1c78-4b24-8abf-4b9b19691f32)

13. Click on the navigation. And then select **PE Device IP**.
          
     ![image 13](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bc9f5d5b-0ade-44a6-8964-16cbcd563adb)

14. Then click on the **Assign** button.
      
       ![image 14](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d8948dfe-6e1a-4f63-ac65-86d3b7cd948c)

15. The device will be linked. There you will get the Device linked successfully message.
    ![image 15](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bdbbfa70-1577-4962-8de4-14d55600b2c7)

16. After linking CE to PE successfully. Wait 5 to 10 minutes vtun4_2 interface is showing green which means the VPN Tunnel is connected.
    ![image 16](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fb2b0e36-1625-4257-a100-91dac9ae0ed0) 

17. Click on the **GATEWAY** menu located on the left side.
    ![image 17](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a33ca996-9691-4fdc-ba73-7b645a6229c3)

18. After clicking on the **GATEWAY** menu, a new window will appear.
    ![image 18](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b25c6e3f-b4f7-4c24-bfe1-aa240ee44021)

19. Click on the box of **Cloud Gateway**.
    ![image 19](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/75a570d9-ad50-4f85-9af2-f169625d9fd5)

20. After that **Select Customer Public IP** has to be selected. If you have Public IP then select it and if not then select **Masquerade**.
    ![image 20](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b81483d9-5a21-4a96-8320-74bd211e8b0e)

21. Then choose **Select Mode**. There you will find (1)Global (2)Full and (3)Selective three modes.
    ![image 21](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f7276c6f-5bb9-4e58-b59e-077307a44999)

22. Click on **Global** mode if you want to use **Global** mode.
    ![image 22](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6f6f88c4-4a23-47c0-8e3e-3b41e3913448)

23. Click on **Full** mode if you want to use **Full** mode.
    ![image 23](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1c79c42d-3181-450d-b57f-62ce87713424)

24. Click on **Selective** mode if you want to use **Selective** mode.
    ![image 24](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/32058616-812a-4945-b983-386968d75901)

25. After choosing the **Selective** mode, type the domain you want to use here in **Enter Allowed Domains**, for **Ex: www.google.com.**
26. Here, Whatever you type in the Allowed Domains, the Domain will work.
    ![image 25](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a3e654ec-a004-49f6-9bae-c4f6498a44e8)

27. After selecting the mode, scroll down a bit and you will find the **Save Config**. Click on the **Save Config** button.
    ![image 26](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9152d813-a28e-4f33-b8da-fefff43be3b0)

28. click on **Save Config** and you will get the Cloud gateway is enabled successfully message.
    ![image 27](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9ed9ccd4-815e-4968-a600-37087673995d) 

29. Now you should be able to access Allowed Domains, i.e. google.com through a Selective Cloud Gateway.

## How to Disable CGW 

1. Click on the box of **Cloud Gateway**.
   ![disable1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/633c7a28-3087-4eca-8d91-07c931251faa)

2. When you click on **Cloud Gateway** you will get such a window.
   ![disable 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4eed8511-70ff-424f-8873-9b6ebb3da268)

3. Now click on **Save Config**.
   ![disable 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b0f1f257-958d-4154-b198-62f7b51de9bf)

4. As soon as you click on **Save Config**, you will get a message on the screen that the Cloud gateway is disabled successfully.
   ![disable 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6c189c71-d1de-4c8d-9a9b-c312f70ced3a)


## Conclusion
As the most important network component of cloud computing, a Cloud Gateway (CGW) provides important capabilities for simplifying and managing the network-to-network link. The CGW enables versatility in routing traffic based on specific needs by allowing users to enable and disable the router and select among Global, Full, and Selective modes.
