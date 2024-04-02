# Custom Social Media Redirect

## Easy Process for Social Media Redirects
In the digital age, navigating authentication processes across various platforms is commonplace. One such procedure involves custom social media redirection, a method allowing users to access services via a personalized path. Let's delve into the intricate steps of this process.

## So there below is a chart throw


 ![redirectionFlow](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7d793824-4d42-41f1-ac24-1d10a88cdea0)   


### Step 1: Accessing the GWC URL
Users start the journey by using their preferred web browser to enter the GWC URL. The process of beginning the personalized social media redirection begins with this URL. It serves as a doorway via a customized pathway to obtain the required services.

**1.** The first user will go to the **Browser**.         
**2.** Enter the **GWC URL** there.

### Step 2: Setting Up a Custom Redirect

Users can leverage features from their preferred social networking site to start a custom redirect once they arrive at the GWC URL. Users can divert to a custom service by clicking on the custom button. There, parameters like callback URL, client secret, status, and client are sent for additional processing.


**1.** Then click on the **Custom** button. [i.e. => http://localhost:3005/65002fe73317732d51e48222/logingw_address=192.168.1.1&gw_port=2060&gw_id=64fedeab4d62213f4433bcc6&ssid=newSSID&ip=192.168.1.205&mac=c4:4b:d2:00:7f:d8]      


   ![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/670814db-6f3f-4532-a79d-52493b86d32b)       

**2.** When this action is taken, custom service is redirected, and there, parameters like the **callback URL, client secret, state, and client are sent for additional processing**.


### Step 3: User Verification

The first step in the authentication process is user verification, which guarantees authorized access to the services you want. Users are required to provide their password and username for the chosen social media platform in order to authenticate themselves. By taking this step, security protections are strengthened and user validity is confirmed.


**1.** Enter their **Username and Password** for user verification. To verify their identity, the user is prompted to input their username and password associated with the selected social media platform [i.e => /auth/custom-data/callback code=1234567&state=eyJnd19pZCI6IjY0ZmVkZWFiNGQ2MjIxM2Y0NDMzYmNjNiIsImNsaWVudF9tYWMiOiJjNDo0YjpkMjowMDo3ZjpkOCIsInNzaWQiOiJuZXdTU0lEIiwiaXAiOiIxOTIuMTY4LjEuMjA1IiwiaWQiOiI2NTAwMmZlNzMzMTc3MzJkNTFlNDgyMjIiLCJnd19hZGRyZXNzIjoiMTkyLjE2OC4xLjEiLCJnd19wb3J0IjoiMjA2MCIsInJlZGlyZWN0X3VybCI6Imh0dHAlM0ElMkYlMkYxOTIuMTY4LjEuMSUzQTIwNjAlMkZ3aWZpZG9nJTJGYXV0aCUzRnRva2VuJTNEIiwibW9kZSI6ImN1c3RvbS1kYXRhIn0= ]


   ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e0abee1d-5e5e-4caa-acd3-da38c1bae28c)


### Step 4: Consent Confirmation

After a successful user verification process, the custom service asks users for permission to increase the amount of information they can access. A consent popup outlining the precise information or features the program wants to access is shown to users. This guarantees openness and gives people the choice to decide how much data to share with others.
              

**1**. The custom service validates the user's details, ensuring their authenticity and eligibility to proceed further.
**2.** After verification, the user is shown a consent prompt that details the precise data or features the application wants to access.

   ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f52987bd-f1ec-4a7f-b731-beb64341b773)

### Step 5: Redirect and Authentication

After consent terms are accepted, redirection and token exchange are important steps in the authentication process. The client application reroutes to the callback URL with a service token if the user grants permission. This interchange makes authentication easier and permits easy access to the services you want.

**1.** If the user accepts the consent terms, the client application redirects to the callback URL along with a service token. [i.e. => /verifyUrl code=1234567&state=eyJnd19pZCI6IjY0ZmVkZWFiNGQ2MjIxM2Y0NDMzYmNjNiIsImNsaWVudF9tYWMiOiJjNDo0YjpkMjowMDo3ZjpkOCIsInNzaWQiOiJuZXdTU0lEIiwiaXAiOiIxOTIuMTY4LjEuMjA1IiwiaWQiOiI2NTAwMmZlNzMzMTc3MzJkNTFlNDgyMjIiLCJnd19hZGRyZXNzIjoiMTkyLjE2OC4xLjEiLCJnd19wb3J0IjoiMjA2MCIsInJlZGlyZWN0X3VybCI6Imh0dHAlM0ElMkYlMkYxOTIuMTY4LjEuMSUzQTIwNjAlMkZ3aWZpZG9nJTJGYXV0aCUzRnRva2VuJTNEIiwibW9kZSI6ImN1c3RvbS1kYXRhIn0%3D].                                                         
**2.** Our service will send a token with a callback URL to the verification URL of the custom service.

### Step 6: User Details Verification

After token exchange and authentication are finished, the emphasis switches to acquiring and confirming user data. If authentication is successful, the custom service returns verified user information after forwarding it to the host service. By taking this step, user data management accuracy and integrity are guaranteed.

**1.** The custom service passes the user's details to the host service and returns the user's details if verified and verification is complete. Otherwise null will be returned as user details.            
**2.** After authentication, the server will send the user details.           
**3.** The custom service will return the user details to the callback URL with the state parameter.             
**4.** The GWC service will check the user details, redirect to success if the user details are there, store the details in the database, and allow the user to use the internet otherwise go back to the login screen again. [i.e. => http://192.168.1.1:2060/wifidog/auth? token=c22b1e142a0275a569eeb665ca5553b9f96f9629953e7e12b153017775974f65].                 
 
   ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6a6c831b-949e-438e-9a23-f0275ff3dffd)

### Step 7: Finalization and Feedback

Giving users feedback on the results of the authentication process is the last step. Regardless of the outcome, users are notified through the browser screen, guaranteeing transparency and empowering them to take appropriate action.


**1.** Return to the **Browser's** success or failure screen. The user is shown a success or failure screen, depending on the result, letting them know if they were able to access the services they wanted or if there was a problem that needed more attention.


   ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/29a2e43d-9ce2-4357-9134-c060c4b5f3c8)

### Conclusion
Finally, while upholding strong authentication measures, customized social media redirection provides users with an easy and safe approach to access desired services. Users can expedite their online authentication process and access services with confidence by comprehending the nuances of the redirection flow and carefully traversing each step. Custom social media redirection is evidence of the continuous efforts to improve user experience and security in the digital sphere as technology advances.

