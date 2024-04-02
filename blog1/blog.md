# Custom Social Media Redirect

## So there below is a chart throw


 ![redirectionFlow](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7d793824-4d42-41f1-ac24-1d10a88cdea0)   

### Step 1: Accessing the GWC URL
Users begin the journey by utilizing their preferred web browser to navigate to the GWC (Gateway Controller) URL. This URL is where you start the process of creating a custom social media redirection.

### Step 2: Setting Up a Custom Redirect
Users are given the opportunity to start a custom redirect when they visit the GWC URL. Clicking the "Custom" option causes visitors to be redirected to a custom service along with the necessary parameters needed for additional processing.

[image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/670814db-6f3f-4532-a79d-52493b86d32b)       

### Step 3: User Verification
An essential component of the authentication process is user verification, which makes sure that only authorized users may access the services they want. To authenticate themselves, users are required to provide the password and username linked to the chosen social networking network.
[i.e => /auth/custom-data/callback code=1234567&state=eyJnd19pZCI6IjY0ZmVkZWFiNGQ2MjIxM2Y0NDMzYmNjNiIsImNsaWVudF9tYWMiOiJjNDo0YjpkMjowMDo3ZjpkOCIsInNzaWQiOiJuZXdTU0lEIiwiaXAiOiIxOTIuMTY4LjEuMjA1IiwiaWQiOiI2NTAwMmZlNzMzMTc3MzJkNTFlNDgyMjIiLCJnd19hZGRyZXNzIjoiMTkyLjE2OC4xLjEiLCJnd19wb3J0IjoiMjA2MCIsInJlZGlyZWN0X3VybCI6Imh0dHAlM0ElMkYlMkYxOTIuMTY4LjEuMSUzQTIwNjAlMkZ3aWZpZG9nJTJGYXV0aCUzRnRva2VuJTNEIiwibW9kZSI6ImN1c3RvbS1kYXRhIn0= ]

![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e0abee1d-5e5e-4caa-acd3-da38c1bae28c)

### Step 4: Consent Confirmation
After a successful user authentication process, the custom service asks users for permission to access any data or capabilities that the application wants to use. In addition to ensuring openness, this consent confirmation step gives consumers the opportunity to decide with knowledge what information can be accessed.

 ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f52987bd-f1ec-4a7f-b731-beb64341b773)

### Step 5: Redirect and Authentication
After consent terms are accepted, the authentication process moves on to a crucial step where token exchange and redirection take place. In order to enable seamless access to desired services and to facilitate authentication, the client application sends users to a callback URL along with a service token.
code=1234567&state=eyJnd19pZCI6IjY0ZmVkZWFiNGQ2MjIxM2Y0NDMzYmNjNiIsImNsaWVudF9tYWMiOiJjNDo0YjpkMjowMDo3ZjpkOCIsInNzaWQiOiJuZXdTU0lEIiwiaXAiOiIxOTIuMTY4LjEuMjA1IiwiaWQiOiI2NTAwMmZlNzMzMTc3MzJkNTFlNDgyMjIiLCJnd19hZGRyZXNzIjoiMTkyLjE2OC4xLjEiLCJnd19wb3J0IjoiMjA2MCIsInJlZGlyZWN0X3VybCI6Imh0dHAlM0ElMkYlMkYxOTIuMTY4LjEuMSUzQTIwNjAlMkZ3aWZpZG9nJTJGYXV0aCUzRnRva2VuJTNEIiwibW9kZSI6ImN1c3RvbS1kYXRhIn0%3D]

### Step 6: User Details Verification
After the token exchange is finished, the emphasis turns to gathering and confirming user data. In order to verify validity and eligibility for further action, the custom service sends user data to the host service, which then returns verified user data.
[i.e. => http://192.168.1.1:2060/wifidog/auth? token=c22b1e142a0275a569eeb665ca5553b9f96f9629953e7e12b153017775974f65].     

![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6a6c831b-949e-438e-9a23-f0275ff3dffd)

### Step 7: Finalization and Feedback

Giving people feedback on the process's results is the ultimate goal of the authentication process. Users see a feedback screen in their browser that shows the status of their access request, whether it is granted or denied.

![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/29a2e43d-9ce2-4357-9134-c060c4b5f3c8)

### Conclusion
Finally, while upholding strong authentication measures, customized social media redirection provides users with an easy and safe approach to access desired services. Users can expedite their online authentication process and access services with confidence by comprehending the nuances of the redirection flow and carefully traversing each step. Custom social media redirection is evidence of the continuous efforts to improve user experience and security in the digital sphere as technology advances.
