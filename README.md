# Minecraft-Server-May2022 (JAVA Edition)
Ansible Script to launch your own Minecraft Server for your friends.
<img src=https://almalinux.org/static/images/logo.svg>
<img src=https://www.letstechup.com/wp-content/uploads/2021/10/Minecraft-founder.jpg>

# Automation Script for Minecraft Servers - Vanilla Linux Script for AlmaLinux

This project is ongoing and will continue to be updated over time.
- Server Version 1.14

# Generating a Hashed Password For This Script:
```
sudo dnf -y install epel-release
```
```
sudo dnf install python3
```
```
python3 -c 'import crypt,getpass;pw=getpass.getpass();print(crypt.crypt(pw) if (pw==getpass.getpass("Confirm: ")) else exit())'
```
**It will immediately ask you to type in a password and then confirm it (Like The Example Below)**
```
Password: 
Confirm: 
$6$/1OFlW9yH1KHHiOm$pn2SfNgbF/rbblahjseab/p1Xb6Z29UZik.BUilZ.TLnp9yvl2HViB3fs8XdVteboeioss7o2A4g1IYxw.TFJ/
```
