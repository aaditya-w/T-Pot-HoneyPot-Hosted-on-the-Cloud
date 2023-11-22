# HoneyPot-Hosted-on-Cloud
<br>

Deployed T-Pot, an open-source honeypot, in a cloud environment. The project utilizes Azure Cloud services, Debian GNU/Linux for T-Pot, and additional tools such as Putty for smooth installation and operation.

<br>

#### Prerequisites for T-Pot Installation:

- Microsoft Azure Cloud Platform 
- Debian 11 "Bullseye" (x64) Image 
- Recommended RAM Size: 8-16 GB 
- Putty


<br>

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

<br>

## Screenshots
<br>

T-Pot Web Interface
- To access T-Pot's Web Interface, navigate to:
  https://(AzurePublicIP):64297

  <br>
  
![Image Alt Text](https://i.imgur.com/n9YZMZP.jpg)

<br>
<br>

Attack Map
<br>

![Image Alt Text](https://imgur.com/9QRe0n3.jpg)

<br>
<br>

Kibana Dashboard
<br>

![Image Alt Text](https://imgur.com/OFU64vD.jpg)

<br>
<br>

Kibana Dashboard
<br>

![Image Alt Text](https://imgur.com/lnRD6sr.jpg)

<br>
<br>

AbuseIPDB
<br>

![Image Alt Text](https://imgur.com/nYo2nqE.jpg)
