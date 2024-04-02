# Custom Social Media Redirect

### Step 1: Accessing the GWC URL
The user starts the journey by using their preferred web browser to reach the GWC URL. This URL acts as the starting point for the personalized social media redirection procedure.

**1.** The first user will go to the **Browser**.         
**2.** Enter the **GWC URL** there.

### Step 2: Setting Up a Custom Redirect

The user can choose to use the features of their preferred social networking site to start a custom redirect after accessing the GWC URL.

**1.** Then click on the **Custom** button. [i.e. => http://localhost:3005/65002fe73317732d51e48222/logingw_address=192.168.1.1&gw_port=2060&gw_id=64fedeab4d62213f4433bcc6&ssid=newSSID&ip=192.168.1.205&mac=c4:4b:d2:00:7f:d8]      


   ![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/670814db-6f3f-4532-a79d-52493b86d32b)       

**2.** The query will redirect to a custom service with **parameters State, client secret, client, and callback URL**.

### Step 3: User Verification

An essential part of the authentication process is user verification, which makes sure that only people with permission can access the services they want.

**1.** Enter their **Username and Password** for user verification. [i.e => /auth/custom-data/callback code=1234567&state=eyJnd19pZCI6IjY0ZmVkZWFiNGQ2MjIxM2Y0NDMzYmNjNiIsImNsaWVudF9tYWMiOiJjNDo0YjpkMjowMDo3ZjpkOCIsInNzaWQiOiJuZXdTU0lEIiwiaXAiOiIxOTIuMTY4LjEuMjA1IiwiaWQiOiI2NTAwMmZlNzMzMTc3MzJkNTFlNDgyMjIiLCJnd19hZGRyZXNzIjoiMTkyLjE2OC4xLjEiLCJnd19wb3J0IjoiMjA2MCIsInJlZGlyZWN0X3VybCI6Imh0dHAlM0ElMkYlMkYxOTIuMTY4LjEuMSUzQTIwNjAlMkZ3aWZpZG9nJTJGYXV0aCUzRnRva2VuJTNEIiwibW9kZSI6ImN1c3RvbS1kYXRhIn0= ]


   ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e0abee1d-5e5e-4caa-acd3-da38c1bae28c)


### Step 4: Consent Confirmation

Following a successful verification process, the customs service requests the user's permission to expand the scope of information that the application can access.              

**1.** The custom service will verify the user's details and if verified they will seek consent to the scope of the user's details.

   ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f52987bd-f1ec-4a7f-b731-beb64341b773)

### Step 5: Redirect and Authentication

Once the terms are accepted, the authentication process proceeds to a pivotal stage of redirection and token exchange.

**1.** If they accept the consent then the client application will redirect to the **callback URL** with the service token. [i.e. => /verifyUrl code=1234567&state=eyJnd19pZCI6IjY0ZmVkZWFiNGQ2MjIxM2Y0NDMzYmNjNiIsImNsaWVudF9tYWMiOiJjNDo0YjpkMjowMDo3ZjpkOCIsInNzaWQiOiJuZXdTU0lEIiwiaXAiOiIxOTIuMTY4LjEuMjA1IiwiaWQiOiI2NTAwMmZlNzMzMTc3MzJkNTFlNDgyMjIiLCJnd19hZGRyZXNzIjoiMTkyLjE2OC4xLjEiLCJnd19wb3J0IjoiMjA2MCIsInJlZGlyZWN0X3VybCI6Imh0dHAlM0ElMkYlMkYxOTIuMTY4LjEuMSUzQTIwNjAlMkZ3aWZpZG9nJTJGYXV0aCUzRnRva2VuJTNEIiwibW9kZSI6ImN1c3RvbS1kYXRhIn0%3D].                                                         
**2.** Our service will send a token with a callback URL to the verification URL of the custom service.

### Step 6: User Details Verification

After the completion of token exchange and authentication, the emphasis switches to obtaining and verifying user information.          

**1.** The custom service passes the user's details to the host service and returns the user's details if verified and verification is complete. Otherwise null will be returned as user details.            
**2.** After authentication, the server will send the user details.           
**3.** The custom service will return the user details to the callback URL with the state parameter.             
**4.** The GWC service will check the user details, redirect to success if the user details are there, store the details in the database, and allow the user to use the internet otherwise go back to the login screen again. [i.e. => http://192.168.1.1:2060/wifidog/auth? token=c22b1e142a0275a569eeb665ca5553b9f96f9629953e7e12b153017775974f65].                 
 
   ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6a6c831b-949e-438e-9a23-f0275ff3dffd)

### Step 7: Finalization and Feedback

Giving the user feedback on the results of the authentication procedure is the last stage.      

**1.** Return to the **Browser's** success or failure screen. The user is shown a success or failure screen, depending on the result, letting them know if they were able to access the services they wanted or if there was a problem that needed more attention.


   ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/29a2e43d-9ce2-4357-9134-c060c4b5f3c8)

### So there below is a chart throw


    ![redirectionFlow](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7d793824-4d42-41f1-ac24-1d10a88cdea0)   
