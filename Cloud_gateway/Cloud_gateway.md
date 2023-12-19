# Cloud gateway testing
- CE and PE need to be connected to enable cloud gateway.
- so first check whether it is connected or not.
  
## How to connect CE and PE
1. First, we will go to its portal, which is the dev.CLOUDS and beta.CLOUDS. So first go to dev.CLOUDS.
![CE PE 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/00ff65fa-bddf-427f-9648-1c648491dcd7)

2. Then go to CE device and click here.
3. Select your device ID here.
![CE PE 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8cda6821-8148-4508-9e48-569872ee22c4)

4. There you will click on device ID so you will see something like this then click on VPN.
![CE PE 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a1cae77a-4af3-4402-813b-3d85e56b44a5)

5. After clicking on VPN you will see the link PE on the right side click on it.
![CE PE 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8ba35c97-4b21-4f39-af40-c533d56b3a1a)

6. After that you will see something like a screen where you have to select region and PE device IP.
![CE PE 5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a4ff5b4c-32f4-4801-bc71-16541cceab1e)

7. If it is a region of India then type IND select PE device IP and click on assign.
![CE PE 6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/347fd1cb-1bdf-4f95-af05-dc0a4816dc36)

8. If you click on assign, it will connect and the message successfully will come as you can see in the image.
![CE PE 7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1e09390c-bd99-4d0d-8b39-3bd39e9439a2)

## CGW Global Mode
By doing Global Mode which will be a local domain like VPN done in India. So India will not be able to connect to any site from a VPN, even the global site will be connected from a VPN because the local site will get fast access. However, connecting the global site with a VPN will increase the speed and encrypt data.

### How to the global mode in CGW
1. Go to CE device and click on your own device.
![CE PE 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/00ff65fa-bddf-427f-9648-1c648491dcd7)

2. After that go to gateway and click on cloud gateway.
![global 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/991733cd-4306-477e-a69e-b75589f4024b)

3. Then select masquerade in select customer public IP or if there is ab ID, you select that ID.
![global 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2f194765-8b8d-4db4-bb4d-9fc1f07a742d)

4. Then select global in select mode.
![global 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/25b69e5a-8680-476e-bba3-7dd0d4efcac5)

5. If you want to use the internet. Then click Enable NAT on the right side.
![global 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/37167ecd-86fa-4002-92de-a1eb695b8de2)

6. After that finally click on save config.
![global 5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/78de39a9-e4e2-4bfd-a2fd-cc348b9211bb)

## CGW Full Mode
In full mode, all local and global sites will be connected to a VPN.

### How to full mode in CGW
1. Go to CE device and click on your own device.
![CE PE 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/00ff65fa-bddf-427f-9648-1c648491dcd7)

2. After that go to gateway and click on cloud gateway.
![global 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/991733cd-4306-477e-a69e-b75589f4024b)

3. Then select masquerade in select customer public IP or if there is ab ID, you select that ID.
![global 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2f194765-8b8d-4db4-bb4d-9fc1f07a742d)

4. Then select full in select mode.
![full 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b4f1b842-0132-4548-ba92-b33ebd786534)

5. If you want to use the internet. Then click Enable NAT on the right side.
![CE PE 6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/347fd1cb-1bdf-4f95-af05-dc0a4816dc36)

6. After that finally click on save config.
![CE PE 7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1e09390c-bd99-4d0d-8b39-3bd39e9439a2)

## CGW selective Mode
In Selective Mode, the domain (website) added will be connected to the VPN.

### How to select mode in CGW
1. Go to CE device and click on your own device.
![CE PE 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/00ff65fa-bddf-427f-9648-1c648491dcd7)

2. After that go to gateway and click on cloud gateway.
![global 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/991733cd-4306-477e-a69e-b75589f4024b)

3. Then select masquerade in select customer public IP or if there is ab ID, you select that ID.
![global 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2f194765-8b8d-4db4-bb4d-9fc1f07a742d)

4. Then select selective in select mode.
![selective 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c26c30df-442c-489f-b938-8446865cfdec)

5. After that write what you want to select here below inside the enter allowed domain for **ex**: goggle.com.
6. Here, Whatever you type in the allowed domain, the domain will work.
![selective 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/99d2613c-5e2b-4b87-b3f1-3de6a12d267c)

7. If you want to use the Internet. Then click Enable NAT on the right side.
![CE PE 6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/347fd1cb-1bdf-4f95-af05-dc0a4816dc36)

8. After that finally click on save config.
![CE PE 7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1e09390c-bd99-4d0d-8b39-3bd39e9439a2)

## What is a single-arm?
A single arm is something that once you have set something and you want to change something without removing it, is called a single arm.

### How to do a single-arm
1. Go to CE device and click on your own device.
![CE PE 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/00ff65fa-bddf-427f-9648-1c648491dcd7)

2. After that go to gateway and click on cloud gateway.
![global 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/991733cd-4306-477e-a69e-b75589f4024b)

3. Then do as explained in **" how to full mode, "how to global mode", and "how to selective mode"**.
4. Then click on a single arm.
![single1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4ae790e3-6424-483f-bfeb-5edc7e7d00ab)

5. After that you have to write the IP for your new setup.
![single2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/96007196-6ac8-44db-a5de-484ccd11ec05)

6. Then click on **add**.
![single3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f1a91b76-6cdb-4b46-936b-2718aace5139)

7. After that finally click on **"save"** config.
![CE PE 7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1e09390c-bd99-4d0d-8b39-3bd39e9439a2)




