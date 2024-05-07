# External Authentication 

## What is External Authentication 
External Authentication refers to the process of verifying the identity of users accessing a system or application by relying on an external source for authentication. This method allows users to log in using credentials from another trusted service provider.
## Why do we need an External Authentication 
External Authentication offers several benefits:
 
- **Enhanced Security**: Leveraging authentication from trusted sources strengthens security measures.
- **User Convenience**: Users can use existing credentials from familiar platforms, reducing the need to remember multiple passwords.
- **Centralized Management**: Organizations can centrally manage user access and permissions.
- **Scalability**: As user bases grow, external authentication systems can handle increased loads effectively.

## How to Create External Authentication

1. Go to **(https://devic.elemprin.com/#/login)** and fill out the necessary information before clicking on the **Login** button.

    ![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e54f820d-0a0e-4bb6-be51-93898175ba6d)

2. Upon logging in, access the Dashboard and proceed to the **Settings** menu.

    ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ced71884-fd14-4fe3-90e7-5794ada4a12c)


3. Navigate to the **Settings** menu and select your organization there first.

   ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/28417dde-d085-4ef7-930d-925347217cef)

4. click on the button that **Add New**.

    ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/0491cb5c-1233-43d6-95ec-4707b9391934)


5. Clicking on the “Add New” button will open a new window where you can input the necessary details. 
  - **Provider**: -  Enter Provider **For example Gwc-beta-exernal-authentication**.
  - **Organization**- Select Organization **for example: demo**.
  - **App id**: - Enter the application key. **For example 6F3csOpDAdBmtVii**.
  - **Secret Key**: - Enter the secret key. **For example T4XdHlWwmJ7XEwwU**.
  - **Callback Url**: - Enter the config URL in the Callback URL. **For example < APPLICATION_URL >/auth/gwc-authentication/callback**.
  - **Login Url**: - Enter the login url. Login URL/externalAuth must be entered. **For example < APPLICATION_URL >/externalAuth**.
  - **Verification Url**: - Enter the verification URL. config URL and verify URL are required. **For example < APPLICATION_URL >/verifyUrl**.
  - **Whitelist domains**: - Add domains. Domain needs to be added. For example:              
    **1. stackpath.bootstrapcdn.com                               
    2. cdn.jsdelivr.net                        
    3. code.jquery.com                      
    4. maxcdn.bootstrapcdn.com                     
    5. fonts.googleapis.com
    6. devichotspot.elemprin.com                                       
    7. betaextauth.infiniteclouds.com**                                  

    ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9ca890d8-b6d4-425f-9cfe-e7f770e23522)


5. And then, simply click on the **Save** button.

    ![image-6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f661e23f-11af-481d-96bb-89b5e9fcd31d)

6. After Clicking the save button, you will get a message on the screen that **Config is created successfully**.

   ![image-7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6d84d293-33c8-4c5f-b747-2b463af07c1a)

## How to configure External Authentication

1. Go to the **Captive portal** menu. 
   ` note:- Before that, it is necessary to keep in mind that your external authentication and the organization of your device must be the same.`

    ![image-8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/625f362f-8195-47a8-8d69-6ea8fd5f5591)

2. After going to the Captive portal click on your device's **Edit** button.

    ![image-9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ce90a5d4-9209-447c-bce5-aa5539667db4)

3. After clicking, a window will open and you will scroll a little there, you will see the **login method**, and from there you can add. And if you add, that method will be shown on the screen.

   ![image-10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/952cd89a-92b2-4447-b339-70f359827a73)

4. After clicking on the **update** button.

   ![image-11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1f5eb1d6-7be8-4a0f-8de5-19449d6faf13)


5. After Clicking the Update button, you will get a message on the screen that **Captive portal details are updated successfully**.

   ![image-12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/11be81fc-0e7a-4a58-82bd-e9c38663abba)


## How to Connect External Authentication in Android

1. Start by connecting to the **SSID** on your device, then proceed to click on **sign in with Gwc-beta-external-authentication**.

   ![image-20](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1fd2ec51-e145-41d2-ae9c-6aeb6cb5ee37)

2. Clicking will open a new window. Then, click on Continue anyway via the browser.

   ![image-21](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/721c7fb3-f80c-43b2-b724-133aa66357fc)


3. Next, it will be redirected to the server and there you should click on Gwc-beta-external-authentication.

    ![image-22](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ff28490d-fafb-4b0d-9364-d06ebbf43487)


4. Fill in your **username and password**, and then select the **login** option.

   ![image-23](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5f497579-9d16-43f6-9f5c-772cd8e31f70)


5. A confirmation message will follow. Please click on the **yes** option over there

   ![image-24](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4f5eaa23-f5fd-4c34-895e-16dd65a62e64)

6. After that, a new window will open for connecting

   ![image-25](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6e374b59-14cd-40e6-958c-694b838d8bbe)

7. After that it will be redirected to the browser.

   ![image-26](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d1537e38-4c53-452e-9aa7-d46e991936b8)

## How to Connect External Authentication in iPhone

1. Start by connecting to the **SSID** on your device, then proceed to click on **sign in with Gwc-beta-external-authentication**.

   ![image-27](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1f5ad980-1fae-4958-8e52-e4a755e6efce)


2. Open a new window where you’ll find a link. Visit the link and click cancel.

   ![image-32](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/babfd40e-94bb-4049-9a04-85315b689f69)

3. After clicking on the **cancel** button. A new window will appear, prompting permission to use the network.

   ![image-28](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f4dc3c75-4ef2-4143-80eb-2683601fc8f2)

4. Then it will show that your connection is not private and click on **back to safety**.

   ![image-29](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ba89f414-eb93-4391-96f0-d669894ef00c)

5.  A confirmation message will appear, asking if you want to proceed. Click on **Continue anyway**.

    ![image-30](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ff9bd6b4-8486-4735-9ba8-97630e080f4c)

6. Fill in your **username and password**, and then select the **login** option.

   ![image-31](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8fd17a7e-f978-419a-afb8-7d3c38471990)

7. A confirmation message will follow. Please click on the **yes** option over there

   ![image-24](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4f5eaa23-f5fd-4c34-895e-16dd65a62e64)

8. After that, a new window will open for connecting

   ![image-25](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6e374b59-14cd-40e6-958c-694b838d8bbe)

9. After that it will be redirected to the browser.

   ![image-26](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d1537e38-4c53-452e-9aa7-d46e991936b8)



## How to Edit External Authentication

   
1. Go to the **API Config** you want to edit.
2. Click on the Edit Located on the right side of your **API Config**.

   ![image-13](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/18e0e27f-9344-456f-afe1-8a7aa0ba0381)


3. After clicking, a new window will open. From here you can change **Provider, App ID, Secret Key, Callback Url, Login Url, Verify Url, and Whitelist domain**.

   ![image-14](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/595ccfac-bec8-408c-a07c-5803cf0cd6a2)

4. After clicking on the **Update** button.

    ![image-15](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fc4a317d-0f89-4b4a-9e26-343ecfcef273)

5. As soon as you click the Update button, you will get a message on the screen that the **Confing is updated successfully**.

   ![image-16](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1cbd5505-3246-4622-b640-dce258649720)


## How to delete External Authentication

1. Click on the delete located on the right side.

    ![image-17](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/32b2a715-9110-4e63-b803-87fb0df4a448)

2. After click, a new window will open. There you will get a confirmation message. Click on the Delete button.

    ![image-18](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d4d26909-1f49-4593-a524-ae3517908324)

3. As soon as you click on Delete, you will get a message on the screen that the **Config is deleted successfully**.

   ![image-19](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e4e3f9a9-a111-401d-99f7-92c353028026)


