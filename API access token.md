# API Access Token
<!-- TOC -->
[API Access Token](#api-access-token)   
    - [What is an API access token?](#what-is-an-api-access-token)   
    - [Why do we need an API token?](#why-do-we-need-an-api-token)    
    - [How to use an API token](#how-to-use-an-api-token)        
        - [How to create a new API token](#how-to-create-a-new-api-token)       
        - [API Tour](#api-tour)           
            - [Main window](#main-window)       
        - [How to allow API](#how-to-allow-api)   
    - [EXAMPLES](#--examples)   
        - [How to block API](#how-to-block-api)        
        - [How to allow IP](#how-to-allow-ip)   
        - [How to block IP](#how-to-block-ip)     
        - [What is token expiry?](#what-is-token-expiry)      
        - [How to token Expiry](#how-to-token-expiry)               
        - [How to update the token](#how-to-update-the-token)        
        - [How to delete the token](#how-to-delete-the-token)           
     - [How to use API access token with compliance client](#how-to-use-api-access-token-with-compliance-client)     
<!-- /TOC -->

## What is an API access token?
An access token is issued to grant access to  3rd party. Disabling ID requires an API token first, so an API token must be generated. 
It's called an API access token. 
## Why do we need an API token?
The API token is required to grant access to 3rd parties. When disabling one's device ID, an API token is required to create a compliance client profile for the first time. For that, an API token has to be generated. The API token is required for compliance with the client profile.
## How to use an API token
The ID can be disabled using an API token and an API token for the ID needs to be generated.
Following are the steps on how to generate an API token and how to use it.

### How to create a new API token
1. First, we will go to its portal which here is the dev.CLOUDS (https://dev.hi-clouds.com/login) and beta.ClOUDS (https://beta1.hi-clouds.com/login). So first go to dev.CLOUDS.
![create new API token 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f7806c48-e7b6-40c0-9da8-75d538444468)
2. If there are features, we will go there if there is a feature in the name of Manage API.
![create new API token 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5e7eb1a4-2a53-4b01-873b-3946765063cc)
3. After going to Manage API you will see a screen-like image.
  
   - **Allowed API:** What you want to give allowed API here has to be added here.
  
   - **Blocked API:** What you want to give blocked API here has to be added here.
  
   - **Allowed IP:** What you want to give allows the IP address to be added here.
  
   - **Blocked IP:** What you want to give a blocked IP address here has to be added here.

    ![create new api token 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/44cfe793-0b8f-487d-b331-43efd7603632)

4. After that click the **"save"** button here.

   ![create new API token 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/dd1640e8-0a20-4067-8f83-503a15627c87)

### API Tour
#### Main window
1. The CLOUDS dashboard is visible in the figure.
   
   ![create new API token 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f7806c48-e7b6-40c0-9da8-75d538444468)


2. There you can see CLOUDS Name, Platform version name, Time, Date, and Location on the left side.

   ![main api1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5e29d72e-d2c6-409e-b0ec-a03d3d181a23)

3. You can see how many users, how many CE, and how many sites there are.   
   ![main api2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bb5c6a1a-709f-4ca9-9c90-c1f0d510724c)

4. You can also see the map there. There on the left side, you can see different futures.
   ![main api3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d0f03881-a4d1-4dd3-86af-5e7ab8150d5f)

5. There you can edit the API by going to Manage API futures.

   ![create new API token 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5e7eb1a4-2a53-4b01-873b-3946765063cc)


### How to allow API
1. Go to API to allow Manage API. After going to manage API, click on **"Add New API Token"** shown on the right side.
   
   ![allow API 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2c6b3104-7f40-4490-8886-50a9a1ed7a84)

2. Click on add new button then you will see something as shown in the image there select the new API you want to allow here.

   ![allow api2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/46f3d81d-6043-4595-98b2-4cc54053d6a4)

   ![allow api3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/43831203-9d23-4b20-a9dd-bed264657051)

3. Then Click on the **"save"** button in the list below.

   ![allow API 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/097877fa-bf9a-4cdb-b949-4e070cb22f26)


## -EXAMPLES  
      ![allow api ex1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/68de3312-4111-4fa1-b2de-a579ecf19088)
      ![allow api ex2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/87e0a868-52c6-4d2c-91f9-cd60dbfcc9b3)
      ![allow ex1 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/623eb780-0fba-4838-9c6e-08b682730980)

 
### How to block API
1. Go to API to allow manage API after going to manage API, click on add new API token shown on the right side.

   ![allow API 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2c6b3104-7f40-4490-8886-50a9a1ed7a84)

2. Click on the add new button the you will see something as shown in the image there select the blocked API you want to allow here.

    ![block api 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d37c9488-b142-4e76-9e71-6abecd7381a9)

   ![block api 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8a219c11-77f0-4ba1-9e7c-383230f1392f)

4. Then click on the **"save"** button in the list below.
   ![block API 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ee4ef2c8-46e7-4269-97ba-5c487d0f7881)

## -EXAMPLES  
1
    ![block  api ex1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5ca36d30-10b2-4051-b94b-4d157dbfb103)  
    ![block  api ex2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/42b93c04-1fd8-456b-ae61-b3880711f6d4)  
    ![block api ex3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8e034428-d384-434f-b43b-38a26268fd4f)  
 

### How to allow IP
1. Go to the add new button as shown in **"[How to allow IP](#how-to-allow-ip)"** and **"[How to block IP](#how-to-block-ip)"**
   ![allow API 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2c6b3104-7f40-4490-8886-50a9a1ed7a84)

2. Then add the IP address you want to access as shown in the image.
   ![allow ip ](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a5d19588-ea7d-40c8-ace2-c89353aa67fc)

3. And then click on the **"save"** button in the list below.
   ![allow ip 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d64c80f5-dbbf-4e7c-b645-f3d9000532dd)

### How to block IP
1. Go to add new button as shown in **"[How to allow IP](#how-to-allow-ip)"** and **"[How to block IP](#how-to-block-ip)"**.
   ![allow API 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2c6b3104-7f40-4490-8886-50a9a1ed7a84)

2. Then add the IP address you want to access as shown in the image.
   ![block ip](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f6327e3b-fae2-4476-a4ea-b03de34b3e84)

3. And then click on the **"save"** button in the list below.
   ![block ip2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9cfb200b-dac9-48a6-8da3-f7dda2c93534)

## What is token expiry?
If the date of the given token is gone, then the API token becomes invalid, i.e. it expires. such a token is called an expired token.
### How to token Expiry
1. Go to manage API.
   ![how to token expiry 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7fb88dca-58da-4f71-9b42-7bc14c2b3f69)
2. After going to Manage API, click on the edit option of the API you want to expire.
   ![how to token expire 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b5865c59-1d9b-4151-b95f-9e4dd153ebfd)
3. After clicking on the edit option, if you scroll down a little, you will see something as shown in the image.
   ![how to token expiry 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a2d4e719-06be-4a77-bdc5-9c6bdc8fb71c)
4. And from there you can change the date of your API. And then click on the **"save"** button.
   ![how to token expiry 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/166e7248-6db6-4ff2-9c21-2c25694e4a47)

### How to update the token
1. When you want to update the given token then go to manage API as shown in the below image.
    ![how to token expiry 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7fb88dca-58da-4f71-9b42-7bc14c2b3f69)

2. Then the right side pen of the API you want to update is given an option. clicking on it and from there you can update your token.
    ![how to token expire 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b5865c59-1d9b-4151-b95f-9e4dd153ebfd)
    ![update 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/91903a6c-b365-49bb-9409-c7d7ba25a4aa)

3. Fill in your updated information and click on the **"save"** button given below.
   ![update 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/958257c8-61f0-4243-a38a-8a86630d20c0)

### How to delete the token
1. When you want to update the given token then go to manage API as shown in the below image.
   ![how to token expiry 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7fb88dca-58da-4f71-9b42-7bc14c2b3f69)

2. Click on the option as shown in the image on the right side of the API of the token you want to delete.
3. When you click on it you will see something like this.
   ![delete1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/92ffe530-9b1b-445a-8bde-6b01def0b333)

4. After that click on **"yes"**. if you click on yes, your given token will be deleted.
   ![delete2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ebdf9602-2b08-4604-bbc1-e9ad46795aae)

## How to use API access token with compliance client
How to generate API token should be generated as shown in **"how to new API token"**.
- How to use API access token with compliance client
1. The generated API has to be added inside the compliance client.
2. When you go to the compliance client's profile and go to the setting as shown in **"[How to configure the profile](#how-to-configure-the-profile)"**, you will see something as shown in the image,

   ![how to config profile](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e2dd09ca-951e-4d9c-a55b-16bc7a42c31e)

4. There you need an API token, name, language, and URL as explained in **"[How to configure the profile](#how-to-configure-the-profile)"**. Also, the newly generated API token will be added here.
5. After that click on **"save"** button.
6. There you will see a message on the screen as shown in the image that your profile is saved, click on **"ok"**.
    ![use 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6d1446ce-3a08-468c-b535-904bf6bf435e)


     


   
   

