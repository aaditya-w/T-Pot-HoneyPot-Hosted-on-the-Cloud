# HoneyPot-Hosted-on-Cloud

Deployed T-Pot, an open-source honeypot, in a cloud environment. The project utilizes Azure Cloud services, Debian GNU/Linux for T-Pot, and additional tools such as Putty for smooth installation and operation.



#### Prerequisites for T-Pot Installation:

- Microsoft Azure Cloud Platform 
- Debian 11 "Bullseye" (x64) Image 
- Recommended RAM Size: 8-16 GB 
- Putty


#### T-Pot Installation Commands 
```bash
sudo apt update 
```
```bash
sudo apt upgrade -y 
```
```bash
sudo apt install git 
```
```bash
sudo git clone https://github.com/telekom-security/tpotce
```
```bash
sudo cd tpotce/iso/installer/ 
```
```bash
sudo ./install.sh --type=user
```

![App Screenshot](https://imgur.com/a/qYD8cvc)

