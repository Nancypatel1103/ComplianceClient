# Single Arm

## What is Single Arm
- A single arm is something that once you have set something and you want to change something without removing it, is called a single arm.
- A one-armed router is the name for a router that routes traffic between one or more virtual local area networks (LAN). These routers work basically the same way as a normal router; they take in information and send it out to the correct location. In the case of a one-armed router, the networks that they route between are on the same physical network. Virtual LANs, and the routers that connect them, are primarily used as security devices.
## Why do need Single Arm
The use of a single-arm router is required when the setup in an office is not to be disturbed, then a single-arm router should be used. For that, configure the CE in the same LAN of the office and give the gateway of the CE in the DHCP server. Now internet or VPN will be directly through the gateway of CE.

## HOW to Single Arm 
1. Go to beta1. hi-clouds (https://beta1.hi-clouds.com/login) and **SIGN IN** by entering the admin permission username and password.                                                                        
  ![image 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/af942b40-bbb0-4b0a-8476-e5189f989a99)

2. When you **SIGN IN**, you will reach the dashboard by default.
  ![image 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fd613766-abfb-4710-8f16-bcfe8044766d)

3. Then Click on the **CE Devices** menu located on the left side.
  ![image 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9a24453b-d501-415f-86a3-19618f2083f5)

4. You will click on **CE Devices**, there you will see a list of **Devices**.
  ![image 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7a1434c0-f0b3-4b51-91fc-b2173ff92adb)

5. Go to the search tab located on the right side. 
   ![image 5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2642bf66-8873-4baa-b994-cb0cafc85946)

6. Go there and search your Device name. For **example: jaymin-home-new-x86**.
  ![image 6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4de5c123-531c-47d3-9adc-f4d0876a02bf)

7. After that you will enter, and there you will find your Device, Click on it.
  ![image 7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/3cbe2c38-5789-4003-8d85-ca903033871b)

8. By clicking there you will see a summary of the **CE Device**.
   ![image 8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7629f387-7389-4f17-b5df-5c2c75fa2abe)

9. Click on the **GATEWAY** menu located on the left side.
    ![image 9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b8988798-361f-43b3-9fba-75b94f4fb34e)

10. After clicking on the **GATEWAY** menu, a new window will appear.
    ![image 10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d1bac712-8674-4cee-8a91-9117456f787d)

11. Click on the box of **Cloud Gateway**.
   ![image 11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9ee4eacf-ee2e-4d90-82eb-5e0283e364fc)

12. After that **Select Customer Public IP** has to be selected. If you have Public IP then select it and if not then select **Masquerade**.
    ![image 12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7908d8b6-0b89-4f34-8ad4-92f609713113)

13. Then choose **Select Mode**. There you will find (1)Global (2)Full and (3)Selective three modes.
   ![image 13](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b9359828-3048-4f06-8167-ecb3061f78d9)

14. Click on **Global** mode if you want to use **Global** mode.
    ![image 14](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/52dd5901-0230-4440-8c26-84f36994bff2)

15. Click on **Full** mode if you want to use **Full** mode.
   ![image 15](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/df92be3b-65cd-49e0-b034-e20fcae9245d)  

16. Click on **Selective** mode if you want to use **Selective** mode.
   ![image 16](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fa8d586c-c01e-4647-b3b5-b49400ca500b)

17. After choosing the **Selective** mode, type the domain you want to use here in **Enter Allowed Domains**, for **Ex: www.google.com.**
18. Here, Whatever you type in the Allowed Domains, the Domain will work.
    ![image 17](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/02af5dbc-9714-4af7-85fb-1ea2db62073f)  

19. Click on the box of **Single Arm**.  
  ![image 18 (2)](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/18513fa6-00c7-4687-939e-24635d753a4d)
20. After clicking, select **IP Address** and **Subnet** below. for **Ex:106.21.242.138 / 255.255.255.255/32.**   
    ![image 19](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/82294820-3338-4c1f-933a-8ee501796abb)

21. Click on **Add** button.    
   ![image 20](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/80ea6b2c-7401-4bf1-a092-ad0a3f663994)
22. Then the IP Address will be Address. Then click **Save Config**.   
    ![image 21](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8dfbb357-bd35-40fd-9f77-54ae846d668b)
23. click on **Save Config** and you will get the Cloud gateway is enabled successfully message.
  ![image 22](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/87dcdcdc-493a-4f24-9dee-93e68f9b0501)
