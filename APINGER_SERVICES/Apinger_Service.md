# Apinger Services
## What is Apinger
Apinger is a network monitoring service that tracks the availability and connectivity of IP addresses. It requires configuration on two customer edge (CE) routers and connects them through a provider edge (PE) router. When successfully connected, it shows "1/1" in the peer's states, indicating one reachable peer.

## Why need Apinger
Apinger is used to connect two CEs to one PE. Apinger is required for IP tracking when configuring devices. it shows "1/1" in the peer's states, indicating one reachable peer.

## How to Apinger Service
1. Go to beta1. hi-clouds (https://beta1.hi-clouds.com/login) and **SIGN IN** by entering the admin permission username and password.

   ![image 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2cc0e784-0192-4715-867d-f61a6e99dfb6)

2. When you **SIGN IN**, you will reach the dashboard by default.                                                         

    ![image 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fe76c624-cb89-439a-8568-08dcf4d70185)

3. Then Click on the **CE Devices** menu located on the left side.                                                    

   ![image 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2c605c5d-5b66-4a7a-ad35-dc671b0f7e1a)

4. You will click on **CE Devices**, and there you will see a list of Devices.                                             

    ![image 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f4b86a92-01a6-49b9-be08-2c3624d80c4e)

5. Link two CE with one PE. For **Ex: CE Hub and Manual-testing**. How linking anyway is  https://github.com/Nancypatel1103/ComplianceClient/blob/a0b03084bc4112196a649933c960ef1504cb5767/CLOUD_GATEWAY/CLOUD_GATEWAY.MD understood here 

   ![image 5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1f738ecc-ba99-4eba-98fa-d8bc5783f506)

6. Then go to your **Device**.
  
   ![image 6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/89c77d41-ce0d-4ebd-a65c-dcdba90f4d32)

7. Click on **Terminal** located on the right side.
  
   ![image 7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/48eb1b56-7008-40a1-902c-4b0620bb33cd)

8. After clicking, a new window will open.
  
   ![image 8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/bbd0889a-8c39-4c3f-b856-85f2b3c1615f)

9. Type the command there. Type this **(cat /etc/config/apinger)** command there.

     ![image 9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/24b25099-ee6e-4156-a203-97b3a527f257)

10. After giving the command, press enter and it will show its information.

     ![image 10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f0927b92-beab-48f7-853e-c28da712ab53)

11. There will be a **BRIDGE**.
12. After that go to your device and click on **BRIDGE**.

    ![image 11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6f1aec90-9442-4f42-977c-e1637494f3a6)

13. After clicking, a new page will open and you will see the created **BRIDGE**.

    ![image 12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4649da6e-5e6a-4860-8659-6d976799a6ba)

14. Use command **/etc/init.d/apinger** start to stop-start apinger service.
15. Then to check the connected device, go to the **web terminal** located on the right side of your device.

     ![image 14](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/805a9437-96a8-4f5f-8582-9f9185a80bb6)

16. After clicking on the **web terminal**, a new window will open.

     ![image 15](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/663351d1-5781-46be-8ad8-e0f6106136b7)

17. Enter your **Username** there. For **Ex: hiclouds**.

    ![image 16](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/943a3914-f99e-45c5-ac81-0b56302750ba)

18. Enter your **Password** there. For **Ex: hicloudss&n-2019**.

     ![image 17](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/058615b6-c739-4eeb-8b93-99e97d9192c4)

19. Click on the **LOGIN** button.

    ![image 18](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/49c53eae-6315-46a1-820e-678215af76f2)

20. After clicking on **LOGIN**, a new window will open.

    ![image 19](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f6398da5-da30-4973-a9be-7d29ff73be12)

21. There you click on the menu on located the left side.

    ![image 20](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f2276b6c-715a-4e0e-bea5-6ebf4015f421)

22. Click on located **Services** on the left.

    ![image 21](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/736c0784-2ac2-4e8c-9c42-21f71fa20d69)

23. Then click on **Apinger**.

     ![image 22](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/17d79741-a687-4bf0-a100-ac64381b514f)

24. After clicking on **Apinger**, a new window will open. There you will see your connected device.
    
    ![image 23](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f3dc52e4-4f59-4482-8fd4-93b4bb1b9223)
