# On-Premise-Server

## What is an On-Premise-Server 
An on-premise server is one that is physically hosted within the company and offers resources and services to users connected to the same network directly.

## Why do we need an On-Premise-Server
The benefits of on-premise servers include lower latency, more control over data, and regulatory compliance.

## How to set up On-Premise-Server

1. Before you set up an **On-Premise-Server** you need to keep in mind that you need to have **Docker** on your local machine. Install **Docker** if Docker is not there. To install Docker, please visit the following link: ** https://docs.docker.com/engine/install/ubuntu/)** (Please note: This guide is specifically for Ubuntu machines. If you have a different operating system, you will need to choose accordingly.)

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
5. After the **installation** is complete issue the following command to check if it runs or not.

   ```
   docker ps
   ```

6. Then 3 folder files are required to run on the permission server.             
   **1. docker-compose.yml               
   2. mongo and            
   3. env**. The **docker Compose.yml** file contains all objects and images from the local machine.            
7. If you want to use the **docker-compose.yml** file you need to log in to the local machine first and it will ask for a username and password to log in. Command to login with **Docker Hub**.                      
   ` Note:- You have to log in with proper credentials to view the image privately. Otherwise, it cannot take the image pull.`
   ```
   docker login
   ```
8. After the login is successful, **login succeeded** will be written there.
9. Next, create a **Deploy Folder** Create a **db-file** inside the deploy folder.
10. After the **db-file** is created go back to the docker-compose.yml file open a local terminal and enter the command to pull all the on-premise server and mongo-db images there.
    ```
    docker-compose up --build -d
    ```
11. Wait for some time after entering the command. It will pull the server image from the repository.
12. Then give the command to check if the server is running correctly or not
    ```
    docker ps
    ```
14. Then check whether **https//localhost:3000** is working or not and can log in from the **On-Premise-Server** if you want to log in with the default user and password then change in the file and use the password username by giving the `docker login` command have to do.
The default organization and user given in the env file is used for it ie               
    **1. OrganizationName               
    2. OrganizationAddress                 
    3. OrganizationStatus                
    4. UserEmail                
    5. UserPassword                      
    6. UserRole                       
    7. UserStatus                  
    8. UserFirstName                        
    9. UserLastName                 
    10. UserAddress**


    ![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/34559bf9-335c-46c7-a0b7-8e19bc11fe4d)

