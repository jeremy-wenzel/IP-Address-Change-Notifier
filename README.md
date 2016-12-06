# IP Address Change Notifier
A simple script that emails me when my public IP Address has changed. Runs every hour checking my public ip against the ip address it has on file.

### Requirements
1. A computer or raspberry pi that can run 24/7
2. Python 2
3. A google email address
4. A desire to be so cheap that you would rather do a complete hack than pay someone else to host your website.

### How to run
1. Make sure you have root privileges
2. Find your current ip address and set it as the savedIpAddress
3. Set the email address that you want to send *from* as fromAddress
4. Set the password for the fromAddress in pswd
5. Set the email address that you want to email *to* as toAddress
6. To run, enter the following
```
sudo ./notifier.py
```
