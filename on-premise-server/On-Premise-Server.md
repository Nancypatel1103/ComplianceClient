# On-Premise-Server

## What is an On-Premise-Server 
An on-premise server is one that is physically hosted within the company and offers resources and services to users connected to the same network directly.

## Why do we need an On-Premise-Server
The benefits of on-premise servers include lower latency, more control over data, and regulatory compliance.

## How to set up On-Premise-Server

1. Before you set up an **On-Premise-Server** you need to keep in mind that you need to have **Docker** on your local machine. Install **Docker** if Docker is not there. To install Docker, please visit the following link: **https://docs.docker.com/engine/install/ubuntu/)** (Please note: This guide is specifically for Ubuntu machines. If you have a different operating system, you will need to choose accordingly.)

### Install Docker Engine on Ubuntu
2. Then run the following command in your local terminal of the machine.                 
   ```
   sudo apt-get update
   ```

3. Then run all these given commands one by one on your local machine.
   ```
   1. sudo apt-get install ca-certificates curl                                                                                                                 
   2. sudo install -m 0755 -d /etc/apt/keyrings                                                                                                                                      
   3. sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc                                                                             
   4. sudo chmod a+r /etc/apt/keyrings/docker.asc                                                                                                    
   5. echo \
   "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
   $(. /etc/os-release && echo "$VERSION_CODENAME") stable" | \
   sudo tee /etc/apt/sources.list.d/docker.list > /dev/null                                                                                                             
   6. sudo apt-get update

   ```

4. Issue this command to install **Docker** on your local machine.

   ```
   sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
   ```
5. After the **installation** is complete issue the following command to check if it runs or not. Install docker in the machine to test it. Try running the Docker Machine after it is successfully installed. And if you have all these docker commands ready then you don't need to do this step you can skip it. 
   ```
   docker ps
   ```

6. Then 3 folder files are required to run on the permission server.             
   **1. docker-compose.yml               
   2. mongo and            
   3. .env**. The **docker-compose.yml** file contains all objects and images from the local machine.            

7. If you want to use the **docker-compose.yml** file you need to log in to the local machine first and it will ask for a username and password to log in. Command to login with **Docker Hub**. After giving the command, you should see **login succeeded** as shown in the image, and if it doesn't, understand that your login is not complete.                 
   ` Note:- You have to log in with proper credentials to view the image privately. Otherwise, it cannot take the image pull.`
   ```
   docker login
   ```
     ![image-8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/84d54d44-b6ad-4f6f-9a83-c55d26cd83c7)

8. After the login is successful, **login succeeded** will be written there.

    ```
    docker-compose up --build -d
    ```
9. Wait for some time after entering the command. It will pull the server image from the repository.
 
10. Then give the command to check if the server is running correctly or not
    ```
    docker ps
    ```

11. Then check if **https//localhost:3000** is working and can login from **On-Premise-Server**. Use the username and password given here                
     **(Username: admin@example.com                                                                                                  
     Password: admin@123)** And if you want to change the default credentials, you can update the following 2 variables in the .env file.            
     **defaultuseremail=<add_user_email> (ex.system@infiniteclouds.com)                                                      
     defaultUserPassword=<updated_password> (ex. Infiniteclouds@1234)***

12. After going to localhost:3000, the login page will open, enter your username and password and log in.

    ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/48a28ed2-f447-456a-b617-feacc5b7de14)

13. After login **Wizard Configuration** page will open and enter **External URL** there and click on next.

    ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/27ac2035-a287-4400-bba4-9e32c8afc540)

14. Next, do you want to enable the Grafrana URL. If you want to do it then click on yes otherwise click on no and click on next.

    ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/af4c5795-10a2-4cdf-9e72-b5256960dd33)

15. Next, do you want to enable Kafka URL. If you want to do it then click on yes otherwise click on no and click on finish.

    ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/18e0ddd7-4c37-4e7c-bdd9-62f59a59d1ab)

16. Click finish and it will land on the URL you entered. And Open the Dashboard.

    ![image-6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9b623c85-5c10-4e23-a1d3-13d71806a901)

17. If you want to use the hotspot, you have to go to the **settings** and configure it in **social management**.
18.These details have to be filled where social management will open.
    - **Provider**: - Provider is provided by default.
    - **Application Key**: - Enter the application key. **For example 6F3csOpDAdBmtVii**.
    - **Secret Key**: - Enter the secret key. **For example T4XdHlWwmJ7XEwwU**.
    - **Callback Url**: - Enter the config URL in Callback URL. **For example Configuration URL/auth/gwc-authentication/callback**.
    - **Login Url**: - Enter the login url. Login url/externalAuth must be entered. **For example Configuration URL/externalAuth**.
    - **Verification Url**: - Enter the verification URL. config url and verify url are required. **For example Configuration URL/verifyUrl**.
    - **Whitelist domains**: - Add domains. Here it is necessary to add the domain given in the image, if not add it, the page will not load.

    ![image-9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/32f75948-1b6f-45ef-a7b7-4f4c27f69f11)

19. And after then click on **Save** button.

    ![image-10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cebbbc23-8b33-468c-aa7b-d9ec7d96db2f)


    

    

