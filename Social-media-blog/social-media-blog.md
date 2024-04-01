
1. The first user will go to the **Browser**.
2. Enter the **GWC URL** there.
3. Then click on the **Custom** button.

   ![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/670814db-6f3f-4532-a79d-52493b86d32b)

4. The query will redirect to a custom service with **parameters State, client secret, client, and callback URL**.

5. Enter their **Username and Password** for user verification.

    ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e0abee1d-5e5e-4caa-acd3-da38c1bae28c)


6. The custom service will verify the user's details and if verified they will seek consent to the scope of the user's details.

    ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f52987bd-f1ec-4a7f-b731-beb64341b773)

7. If they accept the consent then the client application will redirect to the **callback URL** with the service token.
8. Our service will send a token with a callback URL to the verification URL of the custom service.
9. The custom service passes the user's details to the host service and returns the user's details if verified and verification is complete. Otherwise null will be returned as user details.
10. After authentication, the server will send the user details
11. The custom service will return the user details to the callback URL with the state parameter
12. The GWC service will check the user details, redirect to success if the user details are there, store the details in the database, and allow the user to use the internet otherwise go back to the login screen again.

    ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6a6c831b-949e-438e-9a23-f0275ff3dffd)

13. Return to the browser's success or failure screen.

    ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/29a2e43d-9ce2-4357-9134-c060c4b5f3c8)

