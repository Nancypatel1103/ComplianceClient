# Cloud gateway testing
<!-- TOC -->

- [Cloud gateway testing](#cloud-gateway-testing)
    - [What is a CLOUD gateway?](#what-is-a-cloud-gateway)   
    - [Why do need a cloud gateway?](#why-do-need-a-cloud-gateway)   
    - [What are CE and PE?](#what-are-ce-and-pe)  
    - [How to connect CE and PE](#how-to-connect-ce-and-pe)
    - [CGW Global Mode](#cgw-global-mode)
        - [How to the global mode in CGW](#how-to-the-global-mode-in-cgw)
    - [CGW Full Mode](#cgw-full-mode)
        - [How to the full mode in CGW](#how-to-full-mode-in-cgw)
    - [CGW selective Mode](#cgw-selective-mode)
        - [How to select the mode in CGW](#how-to-select-mode-in-cgw)
    - [What is a single-arm?](#what-is-a-single-arm)
    - [Why do we need single-arm?](#why-do-we-need-single-arm)
        - [How to do a single-arm](#how-to-do-a-single-arm)
    - [How to disable cloud gateway](#how-to-disable-cloud-gateway)

<!-- /TOC -->

## What is a CLOUD gateway?
A gateway is a network point that acts as access to another network.
Here the gateway accesses the compliance client's app. With the help of the CLOUDS gateway, you can enable and disable your gateway. You can also select different modes.

## Why do need a cloud gateway?
Gateways play a crucial role in cloud computing by facilitating communication and data transfer between disparate networks, making it possible for different systems to work together seamlessly. A Gateway can enable communication between different networks, facilitating data transfer and integration.

## What are CE and PE?
- CE and PE need to be connected to enable cloud gateway.
- so first check whether it is connected or not.
  
## How to connect CE and PE
1. First go to its portal. There are two portals dev.CLOUDS (https://dev.hi-clouds.com/login) and beta.CLOUDS (https://beta1.hi-clouds.com/login). Go to whatever portal you have from your build here is the dev.CLOUDS.
![CE PE 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/00ff65fa-bddf-427f-9648-1c648491dcd7)

2. Then go to the CE device menu and click.
3. Select your device ID there.
![CE PE 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8cda6821-8148-4508-9e48-569872ee22c4)

4. There you will click on the device ID so you will see something like this then click on the VPN tab like this.
![CE PE 3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a1cae77a-4af3-4402-813b-3d85e56b44a5)

5. After clicking on VPN click on the **Link PE** given on the right side.
![CE PE 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/8ba35c97-4b21-4f39-af40-c533d56b3a1a)

6. Then select Region and PE Device IP.
![CE PE 5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/a4ff5b4c-32f4-4801-bc71-16541cceab1e)

7. If it is a region of India then type IND select PE device IP and click on assign.
![CE PE 6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/347fd1cb-1bdf-4f95-af05-dc0a4816dc36)

8. Then click on assign. Then it will connect and you will get the message successfully.
![CE PE 7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1e09390c-bd99-4d0d-8b39-3bd39e9439a2)

## CGW Global Mode
By doing Global Mode which will be a local domain like VPN done in India. So India will not be able to connect to any site from a VPN, even the global site will be connected from a VPN because the local site will get fast access. However, connecting the global site with a VPN will increase the speed and encrypt data.

### How to the global mode in CGW
1. Go to the CE device menu and click on your own device.
![CE PE 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/00ff65fa-bddf-427f-9648-1c648491dcd7)

2. After that go to gateway and click on cloud gateway.
![global 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/991733cd-4306-477e-a69e-b75589f4024b)

3. Then select masquerade in select customer public IP or if there is an IP ID, you select that ID.
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
1. Go to the CE device menu and click on your own device.
![CE PE 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/00ff65fa-bddf-427f-9648-1c648491dcd7)

2. After that go to gateway and click on cloud gateway.
![global 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/991733cd-4306-477e-a69e-b75589f4024b)

3. Then select masquerade in select customer public IP or if there is an IP ID, you select that ID.
![global 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2f194765-8b8d-4db4-bb4d-9fc1f07a742d)

4. Then select full in select mode.
![full 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/b4f1b842-0132-4548-ba92-b33ebd786534)

5. If you want to use the internet. Then click Enable NAT on the right side.
![global 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/37167ecd-86fa-4002-92de-a1eb695b8de2)

6. After that finally click on save config.
![global 5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/78de39a9-e4e2-4bfd-a2fd-cc348b9211bb)

## CGW selective Mode
In Selective Mode, the domain (website) added will be connected to the VPN.

### How to select mode in CGW
1. Go to CE device menu and click on your own device.
![CE PE 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/00ff65fa-bddf-427f-9648-1c648491dcd7)

2. After that go to gateway and click on cloud gateway.
![global 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/991733cd-4306-477e-a69e-b75589f4024b)

3. Then select masquerade in select customer public IP or if there is an IP ID, you select that ID.
![global 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/2f194765-8b8d-4db4-bb4d-9fc1f07a742d)

4. Then select selective in select mode.
![selective 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c26c30df-442c-489f-b938-8446865cfdec)

5. After that write what you want to select here below inside the enter allowed domain for **ex**: goggle.com.
6. Here, Whatever you type in the allowed domain, the domain will work.
![selective 2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/99d2613c-5e2b-4b87-b3f1-3de6a12d267c)

7. If you want to use the Internet. Then click Enable NAT on the right side.
![global 4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/37167ecd-86fa-4002-92de-a1eb695b8de2)

8. After that finally click on save config.
![global 5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/78de39a9-e4e2-4bfd-a2fd-cc348b9211bb)

## What is a single-arm?
- A single arm is something that once you have set something and you want to change something without removing it, is called a single arm.
- A one-armed router is the name for a router that routes traffic between one or more virtual local area networks (LAN). These routers work basically the same way as a normal router; they take in information and send it out to the correct location. In the case of a one-armed router, the networks that they route between are on the same physical network. Virtual LANs, and the routers that connect them, are primarily used as security devices.

## Why do we need single-arm?
The use of a single-arm router is required when the setup in an office is not to be disturbed, then a single-arm router should be used. For that, configure the CE in the same LAN of the office and give the gateway of the CE in the DHCP server. Now internet or VPN will be directly through the gateway of CE.

### How to do a single-arm
1. Go to the CE device menu and click on your own device.
![CE PE 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/00ff65fa-bddf-427f-9648-1c648491dcd7)

2. After that go to gateway and click on cloud gateway.
![global 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/991733cd-4306-477e-a69e-b75589f4024b)

3. Then do as explained in **"[How to the full mode in CGW](#how-to-full-mode-in-cgw),"[How to the global mode in CGW](#how-to-the-global-mode-in-cgw)", and "[How to select the mode in CGW](#how-to-select-mode-in-cgw)"**.
4. Then click on a single arm.
![single1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4ae790e3-6424-483f-bfeb-5edc7e7d00ab)

5. After that you have to write the IP for your new setup.
![single2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/96007196-6ac8-44db-a5de-484ccd11ec05)

6. Then click on **add**.
![single3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/f1a91b76-6cdb-4b46-936b-2718aace5139)

7. After that finally click on **"save"** config.
![global 5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/78de39a9-e4e2-4bfd-a2fd-cc348b9211bb)

## How to disable cloud gateway
1. Go to CE device and click on your own device.
![CE PE 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/00ff65fa-bddf-427f-9648-1c648491dcd7)

2. After that go to gateway and click on cloud gateway.
![cloud disable](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1250ee7e-141d-4b4b-887d-48a6b2abd191)

3. After that finally click on **"save"** config.
![global 5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/78de39a9-e4e2-4bfd-a2fd-cc348b9211bb)



