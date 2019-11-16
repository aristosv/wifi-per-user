# wifi-per-user
Windows 10 Per User WiFi Connectivity

01. Run the following 2 commands in a command prompt as an administrator.

- netsh wlan set allowexplicitcreds allow=no
- netsh wlan set createalluserprofile enabled=no

This will disable explicit credentials and prevent users from creating network profiles for all users.

![alt text](https://github.com/aristosv/wifi-per-user/blob/master/step01.png)

02. Go to the Control Panel and select "Network and Internet"

![alt text](https://github.com/aristosv/wifi-per-user/blob/master/step02.png)

03. Then select "Network and Sharing Center"

![alt text](https://github.com/aristosv/wifi-per-user/blob/master/step03.png)

04. Then select "Set up and new connection or network"

![alt text](https://github.com/aristosv/wifi-per-user/blob/master/step04.png)

05. Then select "Manually connect to a wireless network"

![alt text](https://github.com/aristosv/wifi-per-user/blob/master/step05.png)

06. Enter your WiFi network information and select "Save this network for me only"

![alt text](https://github.com/aristosv/wifi-per-user/blob/master/step06.png)

07. And click "Clone"

![alt text](https://github.com/aristosv/wifi-per-user/blob/master/step07.png)

This way each user can set up their own WiFi connection.
