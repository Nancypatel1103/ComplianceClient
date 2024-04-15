# On-Premise-Server

## What is an On-Premise-Server 
An on-premise server is one that is physically housed within the company and offers resources and services to users connected to the same network directly.

## Why do we need an On-Premise-Server
The benefits of on-premise servers include lower latency, more control over data, and regulatory compliance.

## How to set up On-Premise-Server

1. Before you set up an **On-Premise-Server** you need to keep in mind that you need to have **Docker** on your local machine. Install **Docker** if Docker is not there. To install Doctor you can install Doctor by clicking on this **(https://docs.docker.com/engine/install/ubuntu/)** link.

### Install Docker Engine on Ubuntu
2. Then issue the command in the local terminal in your local machine.                 
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

6. Then 3 folder files are required to run on the permission server. **1. Doctor Compose.yml 2. Mongo and 3. .env**. The **Doctor Compose.yml** file contains all objects and images from the local machine.
7. If you want to use the **Docker Compose.yml** file you need to log in to the local machine first and it will ask for a username and password to log in. Command to login with **Docker Hub**.
   ```
   docker login
   ```
8. After the login is successful, **login succeeded** will be written there.
9. Next, create a **Deploy Folder** Create a **DB.file** inside the deploy folder.
10. After creating the **Deploy Folder**, open your local terminal and issue commands to pull the **Mongo image into the Mongo DB**.
    ```
    docker-compose up --build -d
    ```
11. Wait for some time after entering the command. It will pull the server image from the repository extract the file and download it from **Mongo**.
12. Next local db mount has to be changed if you want to store in a different location then that **db mount path** has to be changed which will be the path of the **db store**. If you don't change the db mount path it will crash the db and if the db crashes you won't be able to do any work.
13. Then give the command to check if the server is running correctly or not
    ```
    docker ps
    ```
14. Then check whether **local host:3000** is working or not and can log in from the **On-Premise-Server** if you want to log in with the default user and password then change in the file and use the password username by giving the `docker login` command have to do.

