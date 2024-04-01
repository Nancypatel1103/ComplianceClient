
1. The first user will go to the **Browser**.
2. Enter the **GWC URL** there.
3. Then click on the **Custom** button.
4. The query will redirect to a custom service with **parameters State, client secret, client, and callback URL**.
5. Enter their **username and password** for user verification.
6. And if you log in from an application. Then privacy will ask whether to save your details or not. For **ex:- Facebook will ask for privacy**.
7. The custom service will verify the user's details and if verified they will seek consent to the scope of the user's details.
8. If they accept the consent then the client application will redirect to the **callback URL** with the service token.
9. Our service will send a token with a callback URL to the verification URL of the custom service.
10. The custom service passes the user's details to the host service and returns the user's details if verified and verification is complete. Otherwise null will be returned as user details.
11. After authentication, the server will send the user details
12. The custom service will return the user details to the callback URL with the state parameter
13. The GWC service will check the user details, redirect to success if the user details are there, store the details in the database, and allow the user to use the internet otherwise go back to the login screen again.
14. Return to the browser's success or failure screen
