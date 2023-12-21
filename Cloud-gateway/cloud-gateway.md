# CGW
<!-- TOC -->

- [CGW](#cgw)
    - [What is a CGW](#what-is-a-cgw)
    - [Why do need a CGW](#why-do-need-a-cgw)
    - [CGW Enable](#cgw-enabled)  
    - [How to CGW Enable](#how-to-cgw-enabled)
    - [How to Global mode, Full mode, and Selective mode in CGW](#how-to-global-mode-full-mode-and-selective-mode-in-cgw)
        - [Global mode in CGW](#global-mode-in-cgw)
        - [Full mode in CGW](#full-mode-in-cgw)
        - [Selective mode in CGW](#selective-mode-in-cgw)
    - [How to Disable CGW](#how-to-disable-cgw)


<!-- /TOC -->

## What is a CGW
A gateway is a network point that acts as access to another network. With the help of the CLOUDS gateway, you can Enable and Disable your gateway. You can also select different modes.
It has different modes (1) Global mode: As much as there will be global traffic. Global means that whatever traffic outside will be through the CGW. (2) Full mode: Full mode means all global, local, and domain traffic will be through the CGW. and (3) Selective mode: The website and domain you select will use the CGW and the rest will use the local.
## Why do we need a CGW
Gateways play a crucial role in CLOUD computing by facilitating communication and data transfer between disparate networks, making it possible for different systems to work together seamlessly. A Gateway can enable communication between different networks, facilitating data transfer and integration.
## CGW Enable
Before enabling the cloud gateway, it is necessary to connect the CE and PE. So first check if CE and PE are connected or not. If the CE and PE are not connected then what to do is explained below.
1. Go to beta1. hi-clouds (https://beta1.hi-clouds.com/login) and sign in there by entering your username, and password.
  ![login](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8fecde6f-66ce-42a3-ade9-67dd2ef2c81b)
2. After login you will see a window summary displayed.
   ![window](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0857f615-0099-40e5-a591-08927edbac40)
3. Click on the **CE Devices** menu located right side.
   ![CE device](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/961c3947-168e-418c-826e-5f9292cba9c9)
4. After clicking on the **CE Devices** menu, the CE device list will be displayed.
   ![CE devices 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/36638aef-4edc-4cc9-a71b-fba2af35e679)
5. There you will see different Devices IDs. Go to the right-side search tab to search for your own ID.
   ![search](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f3fb9a0f-4652-4a80-ac30-f9d152b12014)
6. After going to the search tab, search the ID name there. for **Ex: jaymin**.
   ![search1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ebbdb163-1272-48e0-a9b2-e8a0d3539989)
7. Click where you will find the device ID. For **EX here is jaymin-home-new-x86**.
   ![search2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/595f532b-2338-4fa5-9397-51dc35c38250)
8. If you click, you will get a summary like this.
   ![summary](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0ab6aa5d-5c1d-4139-8c2e-8ba739dc11fd)
9. Click on the **VPN** tab there.
   ![vpn](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cc75e6c6-7bd6-4149-b2cf-bc16857d2925)

10. After clicking on **VPN**, a new window will open, there is a **Link PE** tab on the right side, click on it.

    ![link pe](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bc24a4f2-1168-468e-a373-3acbd34c6d7a)

11. Clicking on **Link PE** will again open a new window.

     ![link pe1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e308e841-d4da-4d50-8ff8-6d92ebec10a5)

12. Select **Region** and **PE Device IP**. The region has an **IND** code for India.

    ![link pe2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4ac74928-c1e6-443b-bab7-5e0003103cf6)

13. Click on the given arrow. Select **PE Device IP**.

    ![link pe3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/379f8c15-44b0-4b24-ada1-fc26703fb4e2)

14. Then click on **Assign**.

     ![link pe4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/eb7d677d-bc95-4332-a96d-53de10c4e4dd)

15. The device will be linked. There you will get the Device is linked successfully message.

     ![link pe5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/3009a032-a0ff-46e3-9889-68e18d956f4c)

16. Verify that the device ID is linked. Wait 5 to 10 minutes for the red pin to turn green. If it turns green, it is connected.

    ![link pe6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4808f1d7-25fd-4b7c-afb5-9c6b2929133d)

## How to CGW Enable
1. Go to beta1. hi-clouds (https://beta1.hi-clouds.com/login) and sign in there by entering your username, and password.
  ![login](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8fecde6f-66ce-42a3-ade9-67dd2ef2c81b)
2. After login you will see a window summary displayed.
   ![window](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0857f615-0099-40e5-a591-08927edbac40)
3. Click on the **CE Devices** menu located right side..
   ![CE device](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/961c3947-168e-418c-826e-5f9292cba9c9)
4. After clicking on the **CE Devices** menu, the CE device list will be displayed.
   ![CE devices 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/36638aef-4edc-4cc9-a71b-fba2af35e679)
5. There you will see different Devices IDs. Go to the right-side search tab to search for your own ID.
   ![search](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f3fb9a0f-4652-4a80-ac30-f9d152b12014)
6. After going to the search tab, search the ID name there. for **Ex: jaymin**.
   ![search1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ebbdb163-1272-48e0-a9b2-e8a0d3539989)
7. Click where you will find the device ID. For **EX here is jaymin-home-new-x86**.
   ![search2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/595f532b-2338-4fa5-9397-51dc35c38250)
8. If you click, you will get a summary like this.
   ![summary](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0ab6aa5d-5c1d-4139-8c2e-8ba739dc11fd)
9. On the left side you will find various tabs. Click on the **GATEWAY** tab there.
   ![CGW enable](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5253a12d-4731-4bac-898c-026ddaa58df3)

10. After Clicking on GATEWAY a new window will appear.

     ![CGW enable1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5aecedbc-fec6-486e-bed3-18ea3af5f1df)
11. Click on **Cloud Gateway**.
    ![CGW enable2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d441e84d-bd4b-4e78-ad2d-beffabf750a0)

12. Click on Cloud Gateway and scroll down a little, there you will find Save Config. Click on **Save Config** there.
    ![CGW enable3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/70b2576c-58b2-4147-b2e1-e423504586aa)

13. Click on **Save Config**, and you will get the Cloud gateway is enabled Successfully message.
    ![CGW enable4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6441f23a-042b-4c06-b5a1-0a3d7b98f18a)

## How to Global mode, Full mode, and Selective mode in CGW
### Global mode in CGW
1. You will find various menus on the right side. Click on the **CE Devices** menu there.
   ![CE device](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/961c3947-168e-418c-826e-5f9292cba9c9)
2. After clicking on the **CE Devices** menu, the CE device list will be displayed.
   ![CE devices 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/36638aef-4edc-4cc9-a71b-fba2af35e679)
3. There you will see different Devices IDs. Go to the right-side search tab to search for your own ID.
   ![search](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f3fb9a0f-4652-4a80-ac30-f9d152b12014)  
4. After going to the search tab, search the ID name there. for **Ex: jaymin**.
   ![search1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ebbdb163-1272-48e0-a9b2-e8a0d3539989)   
5. Click where you will find the device ID. For **EX here is jaymin-home-new-x86**.
    ![search2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/595f532b-2338-4fa5-9397-51dc35c38250)  
6. If you click, you will get a summary like this.
   ![summary](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0ab6aa5d-5c1d-4139-8c2e-8ba739dc11fd)  
7. On the left side you will find various tabs. Click on the **GATEWAY** tab there.
    ![CGW enable](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5253a12d-4731-4bac-898c-026ddaa58df3)   
8. After Clicking on GATEWAY a new window will appear.
   ![CGW enable1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5aecedbc-fec6-486e-bed3-18ea3af5f1df)  
9. Click on **Cloud Gateway**.
    ![CGW enable2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d441e84d-bd4b-4e78-ad2d-beffabf750a0)  
10. Then select masquerade in select customer public IP or if there is an IP ID, you select that ID.
    ![global 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a9fa5772-9d17-47c9-91a9-1ab2fa15495a)   
11. Then select **global** in select mode.
    ![global 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c6204fa3-0c29-467f-b009-f1fa66069dd1)   
12. Click on Cloud Gateway and scroll down a little, there you will find Save Config. Click on **Save Config** there.
    ![CGW enable3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/70b2576c-58b2-4147-b2e1-e423504586aa)

### Full mode in CGW
1. You will find various menus on the right side. Click on the **CE Devices** menu there.
   ![CE device](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/961c3947-168e-418c-826e-5f9292cba9c9)
2. After clicking on the **CE Devices** menu, the CE device list will be displayed.
   ![CE devices 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/36638aef-4edc-4cc9-a71b-fba2af35e679)
3. There you will see different Devices IDs. Go to the right-side search tab to search for your own ID.
   ![search](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f3fb9a0f-4652-4a80-ac30-f9d152b12014)
4. After going to the search tab, search the ID name there. for **Ex: jaymin**.
   ![search1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ebbdb163-1272-48e0-a9b2-e8a0d3539989)   
5. Click where you will find the device ID. For **EX here is jaymin-home-new-x86**.
    ![search2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/595f532b-2338-4fa5-9397-51dc35c38250)  
6. If you click, you will get a summary like this.
   ![summary](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0ab6aa5d-5c1d-4139-8c2e-8ba739dc11fd)  
7. On the left side you will find various tabs. Click on the **GATEWAY** tab there.
    ![CGW enable](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5253a12d-4731-4bac-898c-026ddaa58df3)   
8. After Clicking on GATEWAY a new window will appear.
   ![CGW enable1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5aecedbc-fec6-486e-bed3-18ea3af5f1df)  
9. Click on Cloud Gateway.
    ![CGW enable2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d441e84d-bd4b-4e78-ad2d-beffabf750a0)  
10. Then select masquerade in select customer public IP or if there is an IP ID, you select that ID.
    ![global 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a9fa5772-9d17-47c9-91a9-1ab2fa15495a)  
11. Then select **full** in select mode.
   ![full 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b4f1b842-0132-4548-ba92-b33ebd786534)
12. Click on Cloud Gateway and scroll down a little, there you will find Save Config. Click on **Save Config** there.
   ![CGW enable3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/70b2576c-58b2-4147-b2e1-e423504586aa)

### Selective mode in CGW
1. You will find various menus on the right side. Click on the **CE Devices** menu there.
   ![CE device](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/961c3947-168e-418c-826e-5f9292cba9c9)
2. After clicking on the **CE Devices** menu, the CE device list will be displayed.
   ![CE devices 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/36638aef-4edc-4cc9-a71b-fba2af35e679)
3. There you will see different Devices IDs. Go to the right-side search tab to search for your own ID.
   ![search](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f3fb9a0f-4652-4a80-ac30-f9d152b12014)
4. After going to the search tab, search the ID name there. for **Ex: jaymin**.
   ![search1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ebbdb163-1272-48e0-a9b2-e8a0d3539989)   
5. Click where you will find the device ID. For **EX here is jaymin-home-new-x86**.
    ![search2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/595f532b-2338-4fa5-9397-51dc35c38250)  
6. If you click, you will get a summary like this.
   ![summary](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0ab6aa5d-5c1d-4139-8c2e-8ba739dc11fd)  
7. On the left side you will find various tabs. Click on the **GATEWAY** tab there.
    ![CGW enable](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5253a12d-4731-4bac-898c-026ddaa58df3)   
8. After Clicking on GATEWAY a new window will appear.
   ![CGW enable1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5aecedbc-fec6-486e-bed3-18ea3af5f1df)  
9. Click on **Cloud Gateway**.
    ![CGW enable2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d441e84d-bd4b-4e78-ad2d-beffabf750a0)  
10. Then select masquerade in select customer public IP or if there is an IP ID, you select that ID.
    ![global 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a9fa5772-9d17-47c9-91a9-1ab2fa15495a)
11. Then select **selective** in select mode.
    ![selective 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5988cef4-e874-4f3a-99a4-6baf0137dbb5)
12. After selecting selective mode, enter here the domain you want to select, for example, **Google.com**
13. Here, Whatever you type in the allowed domain, the domain will work.
    ![selective 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d57ea93e-c8bc-422d-a9a9-8840e8be6c69)
14. Click on Cloud Gateway and scroll down a little, there you will find Save Config. Click on **Save Config** there.
   ![CGW enable3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/70b2576c-58b2-4147-b2e1-e423504586aa)

## How to Disable CGW
1. Go to the CE Device menu and click on your own device.
   ![window](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0857f615-0099-40e5-a591-08927edbac40)
2. Click on the **CE Devices** menu located right side.
   ![CE device](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/961c3947-168e-418c-826e-5f9292cba9c9)
3. After clicking on the **CE Devices** menu, the CE device list will be displayed.
   ![CE devices 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/36638aef-4edc-4cc9-a71b-fba2af35e679)
4. There you will see different Devices IDs. Go to the right-side search tab to search for your own ID.
   ![search](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f3fb9a0f-4652-4a80-ac30-f9d152b12014)
5. After going to the search tab, search the ID name there. for **Ex: jaymin**.
   ![search1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ebbdb163-1272-48e0-a9b2-e8a0d3539989)   
6. Click where you will find the device ID. For **EX here is jaymin-home-new-x86**.
    ![search2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/595f532b-2338-4fa5-9397-51dc35c38250)  
7. If you click, you will get a summary like this.
   ![summary](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0ab6aa5d-5c1d-4139-8c2e-8ba739dc11fd)  
8. On the left side you will find various tabs. Click on the **GATEWAY** tab there.
    ![CGW enable](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5253a12d-4731-4bac-898c-026ddaa58df3)   
9. After Clicking on GATEWAY a new window will appear.
   ![CGW enable1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5aecedbc-fec6-486e-bed3-18ea3af5f1df)  
10. Click on **Cloud Gateway**.
    ![CGW enable2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d441e84d-bd4b-4e78-ad2d-beffabf750a0)
11. When you click on Cloud Gateway you will get such a window.
    ![cloud disable 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/43d039e0-6893-4276-9150-ea2979ab5791)
12. Now click on **Save Config**.
    ![disable 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/53cc6b39-b3e4-42d4-9f80-c54f25fd3a4e)
13. As soon as you click on Save Config, you will get a message on the screen that the cloud gateway is disabled successfully.
    ![disable 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d8696ebe-c3de-4984-b86a-944404f7b19d)

   
