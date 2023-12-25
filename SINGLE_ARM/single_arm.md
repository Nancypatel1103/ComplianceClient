# Single Arm
<!-- TOC -->

- [Single Arm](#single-arm)
    - [What is Single Arm](#what-is-single-arm)
    - [Why do need Single Arm](#why-do-need-single-arm)
    - [How to Enable Single Arm](#how-to-enable-single-arm)
    - [How to Disable Single Arm](#how-to-disable-single-arm)

<!-- /TOC -->

## What is Single Arm
- A single arm is something that once you have set something and you want to change something without removing it, is called a single arm.
- A one-armed router is the name for a router that routes traffic between one or more virtual local area networks (LAN). These routers work basically the same way as a normal router; they take in information and send it out to the correct location. In the case of a one-armed router, the networks that they route between are on the same physical network. Virtual LANs, and the routers that connect them, are primarily used as security devices.
## Why do need Single Arm
The use of a single-arm router is required when the setup in an office is not to be disturbed, then a single-arm router should be used. For that, configure the CE in the same LAN of the office and give the gateway of the CE in the DHCP server. Now internet or VPN will be directly through the gateway of CE.

## How to Enable Single Arm 
1. Go to beta1. hi-clouds (https://beta1.hi-clouds.com/login) and **SIGN IN** by entering the admin permission username and password.                                                                        
  ![image 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7e56d207-0bca-4580-bb81-baf34d5b642e)
2. When you **SIGN IN**, you will reach the dashboard by default.
  ![image 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/39f094f0-56a6-49ab-888a-4951c4eb042d)
3. Then Click on the **CE Devices** menu located on the left side.
  ![image 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/64543fc9-9f6d-4eb2-8c84-a175b499b3f5)

4. You will click on **CE Devices**, there you will see a list of **Devices**.
  ![image 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/205221fd-0958-4b18-ab5d-8f6fcc40f9eb)

5. Go to the search tab located on the right side. 
   ![image 5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8d98c687-76ff-4b38-87b4-7888a0fdacf7)

6. Go there and search your Device name. For **example: jaymin-home-new-x86**.
  ![image 6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fcb2066f-4d44-40ad-9664-ce943d82065e)

7. After that you will enter, and there you will find your Device, Click on it.
 ![image 7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/104defef-5197-45ef-b832-2a0c27adc8a6)

8. By clicking there you will see a summary of the **CE Device**.
   ![image 8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6ca7b888-0689-4836-9ef3-83035058a871)
9. Click on the **GATEWAY** menu located on the left side.
   ![image 9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/aa15c76d-4882-4007-b7a8-935a9b6cb01a)
10. After clicking on the **GATEWAY** menu, a new window will appear.
    ![image 10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d1bac712-8674-4cee-8a91-9117456f787d)

11. Click on the box of **Cloud Gateway**.
    ![image 11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/108f0a4e-75af-480d-9c03-c9cd91b1559d) 
12. After that **Select Customer Public IP** has to be selected. If you have Public IP then select it and if not then select **Masquerade**.
   ![image 12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/68f99a2f-7d53-4220-92b3-05160cc8f966)  
13. Choose on select mode. Here how to choose select mode is explained in CGW.
14. Click on the box of **Single Arm**.  
    ![image 18 (2)](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/136a9c00-67a4-4d6f-b7a2-28a795051af6)

15. After clicking, select **IP Address** and **Subnet** below. for **Ex:106.21.242.138 / 255.255.255.255/32.**   
   ![image 19](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/3d1ad299-6ffa-4ab4-a5f7-0762c1b51cbe)

16. Click on the **Add** button.    
  ![image 20](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/06aed440-36cc-43a6-a286-c44d7a4d0a40)

17. Then the IP Address will be Address. Then click **Save Config**.   
    ![image 21](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4d42d642-0dff-4698-ad63-41f370469c1e)

18. click on **Save Config** and you will get the Cloud gateway is enabled successfully message.
  ![image 22](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5d7901d0-e770-4d35-a779-dcb1d110820e)

## How to Disable Single Arm
1. Click on the box of **Single Arm**.
   ![disbale 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f8b843ab-942a-4392-abc8-54233465f3e7)
2. Then click on the cross or click on Delete All.
   ![disable 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/aebdf1a9-49c0-4bea-aeb1-fd6666b54456)
3. Now click on **Save Config**.
   ![disable 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e87c6e1d-84c4-4ea9-8371-20c48f9705e1)
