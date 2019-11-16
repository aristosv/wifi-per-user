# wifi-per-user
Windows 10 Per User WiFi Connectivity

01. Run the following 2 commands in a command prompt as an administrator.

- netsh wlan set allowexplicitcreds allow=no
- netsh wlan set createalluserprofile enabled=no

This will disable explicit credentials and prevent users from creating network profiles for all users.

![alt text](https://github.com/aristosv/sdshrink/blob/master/step01.png)
