# Custom Social Media Redirect
 
## Easy Process for Social Media Redirect

A popular method for streamlined logins is custom social media redirection. This allows users to access online services with a personalized link or login using their social media credentials.

### Thus, the chart that follows

 ![redirectionFlow](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7d793824-4d42-41f1-ac24-1d10a88cdea0)   

### Step 1: Entering the Gateway Controller URL

When connecting to a public WiFi network users often encounter the Gateway Control No page. These steps include entering the Gwc URL that they need to authenticate before gaining Internet access, usually given as The required results like gateway mean part, ID, SSID, MAC Address, and IP address are used in the URL. These results are necessary for the GWC to identify and authenticate the user's device on the network. For example, could be like URL.  [http://localhost:3005/65002fe73317732d51e48222/logingw_address=192.168.1.1&gw_port=2060&gw_id=64fedeab4d62213f4433bcc6&ssid=newSSID&ip=192.168.1.205&mac=c4:4b:d2:00:7f:d8]

- This step is the initial interaction between the user's device and the GWC that sets the stage for authentication and access to the Internet.

  ![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/670814db-6f3f-4532-a79d-52493b86d32b)

### Step 2: Social Media Popup for Authentication

After entering the GWC URL the user is often redirected to a social media authentication page asking them to log in using their social media credentials. These steps simplify the authentication process for the user to access the WiFi network and leverage existing social media accounts The popup window acts as a bridge between the GWC and the user's social media authentication system ensuring a seamless login experience.

GWC does not access the user's social media identity. It uses the social media platform's authentication system to verify the user's identity. GWC increases security for users by delegating authentication to third-party services such as Facebook and Google.  

  ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e0abee1d-5e5e-4caa-acd3-da38c1bae28c)

### Step 3: Consent and Callback URL Redirect

If social media authentication succeeds, consent is shown to the user. These prompts ask the user to access specific data or perform specific tasks. When the user accepts the consent prompt the GWC initiates the token exchange process by redirecting the callback URL.

The callback URL contains essential parameters such as a unique code and state information encrypted for security purposes. These parameters facilitate communication between the GWC and the user's device, enabling the exchange of authentication tokens. For example, the callback URL might resemble: [/auth/custom-data/callback?code=1234567&state=eyJnd19pZCI6IjY0ZmVkZWFiNGQ2MjIxM2Y0NDMzYmNjNiIsImNsaWVudF9tYWMiOiJjNDo0YjpkMjowMDo3Zjpk
OCIsInNzaWQiOiJuZXdTU0lEIiwiaXAiOiIxOTIuMTY4LjEuMjA1IiwiaWQiOiI2NTAwMmZlNzMzMTc3MzJkNTFlNDgyMjIiLCJnd19hZGRyZXNzIjoiMTkyLjE2OC4xLjEiLCJnd19wb3J0IjoiMjA2MCIsInJlZGlyZWN0X3VybCI6Imh0dHAlM0ElMkYlMkYxOTIuMTY4LjEuMSUzQTIwNjAlMkZ3aWZpZG9nJTJGYXV0aCUzRnRva2VuJTNEIiwibW9kZSI6ImN1c3RvbS1kYXRhIn0= ]

   ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f52987bd-f1ec-4a7f-b731-beb64341b773)

### Step 4: Token Verification Process

After receiving the token from the callback URL, GWC starts the verification process with the social media service. This step sends the token received with the required parameters to the verification endpoint of the social media service. The social media service validates the token to confirm the user's identity and authorization.

If the verification is successful, the social media service sends a response indicating the user's identity verification status. [ie => /verifyUrl?code=1234567&state=eyJnd19pZCI6IjY0ZmVkZWFiNGQ2MjIxM2Y0NDMzYmNjNiIsImNsaWVudF9tYWMiOiJjNDo0YjpkMjowMDo3ZjpkOCIsInNzaWQiOiJuZXdTU0lEIiwiaXAiOiIxOTIuMTY4LjEuMjA1IiwiaWQiOiI2NTAwMmZlNzMzMTc3MzJkNTFlNDgyMjIiLCJnd19hZGRyZXNzIjoiMTkyLjE2OC4xLjEiLCJnd19wb3J0IjoiMjA2MCIsInJlZGlyZWN0X3VybCI6Imh0dHAlM0ElMkYlMkYxOTIuMTY4LjEuMSUzQTIwNjAlMkZ3aWZpZG9nJTJGYXV0aCUzRnRva2VuJTNEIiwibW9kZSI6ImN1c3RvbS1kYXRhIn0%3D].


### Step 5: Identity Verification and Callback Redirection

After verifying the token, GWC authenticates the user based on the verification response. If the user's identity is successfully verified, GWC redirects the user to the previously provided callback URL otherwise returns null. The callback URL also contains more details, those details are username, email and encrypted for security.

[/auth/external/callbackuser=%7B%22name%22%3A%22John%20Doe%22%2C%22email%22%3A%22john.doe%22%7D&state=eyJnd19pZCI6IjY0ZmVkZWFiNGQ2MjIxM2Y0NDMzYmNjNiIsImNsaWVudF9tYWMiOiJjNDo0YjpkMjowMDo3ZjpkOCIsInNzaWQiOiJuZXdTU0lEIiwiaXAiOiIxOTIuMTY4LjEuMjA1IiwiaWQiOiI2NTAwMmZlNzMzMTc3MzJkNTFlNDgyMjIiLCJnd19hZGRyZXNzIjoiMTkyLjE2OC4xLjEiLCJnd19wb3J0IjoiMjA2MCIsInJlZGlyZWN0X3VybCI6Imh0dHAlM0ElMkYlMkYxOTIuMTY4LjEuMSUzQTIwNjAlMkZ3aWZpZG9nJTJGYXV0aCUzRnRva2VuJTNEIiwibW9kZSI6ImN1c3RvbS1kYXRhIn0=]

  ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6a6c831b-949e-438e-9a23-f0275ff3dffd)

### Step 6: Database Storage and Redirection

Upon receiving the user's details, the GWC stores them securely in its database for future reference. Users with verified identities are granted internet access, while those with null verification outcomes are redirected to the GWC's login page for further authentication attempts. i.e. => i.e. => http://192.168.1.1:2060/wifidog/auth? token=c22b1e142a0275a569eeb665ca5553b9f96f9629953e7e12b153017775974f65].

   ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/29a2e43d-9ce2-4357-9134-c060c4b5f3c8)

### Conclusion
Finally, while upholding strong authentication measures, customized social media redirection provides users with an easy and safe approach to accessing desired services. Users can expedite their online authentication process and access services with confidence by comprehending the nuances of the redirection flow and carefully traversing each step. Custom social media redirection is evidence of the continuous efforts to improve user experience and security in the digital sphere as technology advances.

