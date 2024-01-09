# WhiteList
## What is WhiteList
## Why do we need WhiteList
## How to configure WhiteList
1. First you have to link CE with PE. How to link CE with PE is explained here ([How Enable CGW](#how-enable-cgw)).
2. Click on the **GATEWAY** menu located on the left side.
   ![image 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/715bcfbe-4b79-4b43-a0d4-862b00dfcc84)

3. After clicking on the **GATEWAY** menu, a new window will appear.
   ![image 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/72a1aaed-6e7b-4b86-b231-a5b7873b8410)

4. Click on the box of **Cloud Gateway**. How to Select a Customer Public IP after clicking on the cloud gateway box is explained here ([How Enable CGW](#how-enable-cgw)).
   ![image 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c09c5495-5f09-4456-8c2f-eb8e1aae7852)

5. Then choose select mode. There you will find **1. Global 2. Full 3. Selective** three modes.
   ![image 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/97aa0db1-43dd-4764-8153-cfa0100e1ed1)

6. Click on **Global** mode if you want to use **Global** mode. **Global** mode includes all types of websites.
7. Click on **Full** mode if you want to use **Full** mode. **Full** mode includes all types of Domains. After selecting **Full** mode, type the subdomain you don't want to allow in the enter block domain.
8. Click on **Selective** mode if you want to use **Selective** mode. In selective mode, you have to enter the domain you want to run through the gateway in Allow Domains and the domains you don't want to allow in Block Domains.
9. After that **Enter Allowed Domains**, if you have run a local website from a **Cloud Gateway**, write here in **Enter Allowed Domains**. For **Ex: if there is a local website of the government, you have to enter it here if you run it from the **gateway**.H ere for **Ex: www.google.com**.
   ![image 5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/cd527079-5dc4-466e-9d25-642dc642717f)
   
10. Then **Enter Blocked Domains**, if you do not want to run the subdomain of the domain you have allowed from the gateway, you have to write it here in **Enter Blocked Domains** for **Ex: www.facebook.com**.
   ![image 6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c0839aac-78fc-4e8b-8383-e4fdf22a0517)

11. Then Enter **Allowed IP**. The Public IP you want to send the request to should be written here in the **Allowed IP**. For **Ex: 103.78.41.6**.
    ![image 7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/699ee04f-eeaa-44f1-9eb4-09622a8b4537)

12. Enter **Blocked IP**. Here in block IP type Public IP, you don't want to send public IP requests. So the request from that IP will not go through. For **Ex: 182.168.1.1**.
    ![image 8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/01d5ed2a-f41b-482a-a4d6-2fe43fff5444)

13. Now click on **Save Config**.
    ![image 9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/af9511c2-8224-42f3-a46e-e4858ef40153)

14. click on **Save Config** and you will get the Cloud gateway is enabled successfully message.
    ![image 10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2f79051d-0d6d-41a4-9585-18ccebc60703)
