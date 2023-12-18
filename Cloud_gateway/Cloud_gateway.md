# Cloud gateway
- CE and PE need to be connected to enable cloud gateway.
- so first check whether it is connected or not.

## How to connect CE and PE
1. First, we will go to its portal, which is the dev.CLOUDS and beta.CLOUDS. So first go to dev.CLOUDS.
2. Then go to CE device and click here.
3. Select your device ID here.
4. There you will click on device ID so you will see something like this then click on VPN.
5. After clicking on VPN you will see the link PE on the right side click on it.
6. After that you will see something like a screen where you have to select region and PE device IP.
7. If it is a region of India then type IND select PE device IP and click on assign.
8. If you click on assign, it will connect and the message successfully will come as you can see in the image.

## How to global mode in CGW
1. Go to CE device and click on your own device.
2. After that go to gateway and click on cloud gateway.
3. Then select masquerade in select customer public IP.
4. Then select global in select mode.
5. If you want to use the internet. Then click Enable NAT on the right side.
6. After that finally click on save config.

## How to full mode in CGW
1. Go to CE device and click on your own device.
2. After that go to gateway and click on cloud gateway.
3. Then select masquerade in select customer public IP.
4. Then select full in select mode.
5. If you want to use the internet. Then click Enable NAT on the right side.
6. After that finally click on save config.

## How to select mode in CGW
1. Go to CE device and click on your own device.
2. After that go to gateway and click on cloud gateway.
3. Then select masquerade in select customer public IP.
4. Then select selective in select mode.
5. After that write what you want to select here below inside the enter allowed domain for **ex**: goggle.com.
6. Here, Whatever you type in the allowed domain, the domain will work.
7. If you want to use the Internet. Then click Enable NAT on the right side.
8. After that finally click on save config.
