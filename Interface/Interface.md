# Interface

## What is an Interface
A user interface acts as a contractual arrangement that specifies how different software elements should interact with each other. It defines a set of methods that a class must implement, ensuring consistency and interoperability between different parts of the system.

## Why do we need an Interface
Interfaces are essential to maintain modularity, extensibility, and code reusability in software development. By defining clear boundaries and expectations of how components communicate, interfaces facilitate collaboration between developers and enable the integration of different modules into compatible systems.

## How to Configure an Interface
1. First install Ubuntu on the virtual box. Before installing the Ubuntu server, a virtual box must be installed on your machine. So check if it is installed or not and if not how to install it is explained in the link here(https://www.virtualbox.org/wiki/Downloads). And installing Ubuntu version 22.04 version.
2. Next, download it from the Ubuntu server page. Then select option number two, and your PC will download the 1.37 GB ISO file.
3. Install Virtual Box Start with the Virtual Box Manager interface from which you will manage all your virtual machines.

    ![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7424acac-f202-4fae-ae69-05b2765a96dd)

4. Give your virtual machine a name by clicking the New button on the right side of the virtual box. Then the two drop menus will be automatically updated.

    ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c544c686-cc7b-4cc7-a70c-587c13c3fd3f)

5. Proceed by clicking Next and then the wizard will ask you to select megabytes of memory to allocate to the virtual machine. Forex:- 2GB

    ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e1fdbfe2-5237-4f13-86e1-f6414aa3d841)

6. Click on the Next button again. and will ask to add a virtual hard disk to your machine. Then make sure that Create a virtual hard disk is selected. Then click on the Create button.

    ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/879dcdd5-9f23-4fe9-b0cf-9c54a18a2c8c)

7. Select the file type for the new virtual hard disk. Make sure VDI (Virtual Disk Image) is checked or not then click on the Next button.

    ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c93b7166-2244-45da-bd90-9e30c8a62125)

8. A new window will then open and you will be asked if you want the new virtual hard disk to grow as it is used or if it should be created at its maximum size. So make sure Dynamically allocated is selected and then click on the next button.

    ![image-6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9fa01ddd-d4fc-4057-8604-d56ff119b124)

9. Then finally select the virtual hard disk size in megabytes. It should have a default size of 10GB. And increase it as it sees fit. Then click on the Create button.

    ![image-7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b5c47fa8-03d3-40a2-806c-3780419204b1)

10. Now install the Ubuntu server on the virtual machine. While installing make sure your virtual machine is selected or not. And then click on the start button. The virtual box manager lets you choose a virtual optical disk file or a physical optical file to start the virtual machine. Click the folder with the arrow located on the right side of the dialog select the previously downloaded IOS file and click the Start button. Then the installation process of Ubuntu will start.

    ![image-8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7cc7ad8b-c15f-40e3-81b4-360c2f7c1a57)

11. A new window will open where you will see all the different languages. Select the language from there. For Ex:- English

    ![image-9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/eacf8a98-cbf6-4001-b82d-896336481cfd)

12. Next if the installer is updated then choose to install or ignore it for ex:- choose to install the update.
13. Install after update.

    ![image-10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bf0c9646-32eb-400f-8ffa-dfc7d39b6c10)

14. Next select the keyboard layout for ex:- Here German keyboard is selected. Then click on the OK button.

    ![image-11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/31de024b-095b-4996-add8-3837f9278aa0)

15. Then you have to choose default among them. In which a small runtime footprint is customized. Select default and click on the done button.

    ![image-12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/9bc72874-e467-4ee6-ad84-38a31650a99d)

16. Click Done then it will try to configure the Ubuntu standard network interface. It can only accept default and then click on the done button.

    ![image-13](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7abfa309-b205-411f-8ba4-1ef2abb321ba)

17. If the system requires a proxy to connect to the Internet, add its details in the next dialog and click on the done button.

    ![image-14](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8c2145ec-0923-4478-be34-949de9ce1167)

18. If you want to use an alternative mirror for Ubuntu you can enter its details here else select Full and accept the default.

    ![image-15](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/dd0cc996-1807-499a-9c53-984c62eaa632)

19. The installer can give you complete information. Here you have to select a custom storage layout. LVM does not support groups.

    ![image-16](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6411031a-aa2d-46b9-a4ec-ca51689a6d5b)

20. A new window will open in which the profile has to be set up. Fill in the details by entering your name, your server name, your username, and password, and then click on the done button.

    ![image-19](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c59a0d5f-a678-43f7-8ba7-97eacb9150a4)

21. Then there will be an opportunity to select an OpenSSH server. It will be needed to connect to the virtual machine via SSH. So make sure it is selected or not. There is an option to import SSH keys for Git Hub and Launchpad. Then click on Done.

    ![image-20](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f49a8752-90ce-451b-b7fd-401476033834)

22. Here you can select from a list of popular snaps to install on your system. Snaps are self-contained software packages that work across a range of Linux distributions. Then click on the Done button

    ![image-21](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/95fefb04-cac2-49b1-93d7-5c66f3738255)

23. And that's it, the installer will now install Ubuntu server version 22.04. Once it finishes reboot now should be selected.

    ![image-22](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/780ad35f-dee6-4328-a75c-e889330db5c8)

24. Once Ubuntu is installed, open a terminal and run the update and package upgrade command.
    ```
    sudo apt update
    sudo apt upgrade
    ```

25. Then connect to your Ubuntu server.
    ```
    ssh username@ip_address
    ```


26. After Ubuntu is installed, go into the terminal and issue a command. Keep the username added in Ubuntu in the Ubuntu server username.
    ```
     sudo vi /etc/sudoers.d/<ubuntu_server_username>
    ```

    ![image-23](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b4989321-47a7-4d38-b477-8fc2f8208070)


27. Next, enter the username and do all, and give the command which is given here, enter your username instead of **herry**.
     ```
    herry ALL=(ALL) NOPASSWD: ALL
     ```
    ![image-24](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1d2fa4bb-a468-4a2c-8c9f-678a2865f96b)
 

28. Next, run the cd on-premise command.
    ```
    cd on-premise/
    ```
    ![image-25](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1d355c92-3cca-48d6-9205-9011e2b9d67f)

29. `Note:- Make sure that Docker and Doctor Compose are installed on the Ubuntu server and if not install them first you will not be able to run the docker command.` Then run the docker-compose command.
    ```
     docker-compose up --build -d
    ```
30.  Wait for some time after entering the command. It will pull the server image from the repository.
    
31. Give the command given here for the image.
    ```
    docker image ls
    ```
32. Then give the command to check if the server is running correctly or not.
    ```
    docker ps
    ```
    ![image-26](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/561e0ca9-5b9d-4227-bcfc-b8e361598d49)


33. After installing docker create a folder named on-premise in your machine. Then add the file inside the source from the scp command. In the etc file, add the file with the name of the user inside Sudo. For Example Command `scp on-premise.zip herry@192.168.29.209/home/herry/on-premise`

34. Enter the following command to run the application.
    ```
    npm run start:on-premise-controller
    ```
    ![image-27](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/e3940e89-43f1-4f32-976c-79b100da000b)

35. When the application runs, you will see the **Nest application successfully started** message there.

    ![image-28](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a2442c61-205f-4f0f-ad38-39084e8357a7)

36. After successfully running login your application using the IP address used on Ubuntu. **For ex:- 198.168.29.206:3000**. Enter **Username and Password** (username:- admin@example.com, Password:admin@123) there and click on the **Login** button.
 
    ![image-29](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f8c74843-3e4f-4dd4-a5f0-e35479897cd8)

37. After login **Wizard Configuration** page will open enter the External URL there and click on the **Next** button.

    ![image-30](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/49cae9cd-3a9b-496b-87cc-506edd7b9533)

38. Next, do you want to enable the Grafrana URL? If you want to do it then click on yes otherwise click on no and click on the **Next** button.
39. Next, do you want to enable the Kafka URL? If you want to do it then click on yes otherwise click on no and click on the **Next** button.
40. After that reset cardantile will open and enter the password and password then click on the **Finish** button.

    ![image-31](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/601869d6-c659-42c7-9f78-a876f037c77d)

41. Click finish and it will land on the URL you entered. Open the Dashboard and go to the **Setting** menu.
42. If you go to the **Setting** menu, Then go to the Interface tab. By default something like this will appear. Click on the **Edit** button there.
  
    ![image-32](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/84067113-2a37-4826-b779-f74d0f7c6451)

43. If you click on edit, a new window will open where you will see the interface name, IP address, subnet mask, and Gateway IP. By default the name of the interface will appear as shown in the image. which comes from the Ubuntu Server. Also enter the IP address, subnet mask, and Gateway IP as shown in the image. After that click on the **Update** button.
    `Note:- Here the range of your IP address will be the same as the IP address and the same will be in the subnet mask. Here you will not be able to give any IP address or subnet mask, here the IP address given in your range will come and the subnet mask will come.`

    ![image-33](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/62648f4a-0c2c-467c-b25c-5cd3e1f04b92)

44. After clicking on the update button, you will see a **Successfully** No message in your terminal.
45. As soon as the successful message is received, every process running on this IP will be stopped and it will move to another IP that you have entered here. It means that the application will run on the IP given by you in the IP then check whether the application is running on the IP given by you or not.
46. Run the command given here to bring up the application as explained further.
    ```
    npm run start:on-premise-controller
    ```
47. After running the command you can see in the image that it has moved to another IP address.
48. Login by entering your username and password and clicking on the **login** button.

    ![image-34](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5646efa2-c56e-40c5-976e-7634e2ecad80)

49. And if the license is expired then click on **login** then you will get an error show as shown in the image. if you are getting error this message then your license expires please contact to support team.

    ![image-35](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bfc9bb15-46ff-48a6-8938-a636c27d5c7d)





