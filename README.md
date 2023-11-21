# T-Pot-HoneyPot-Hosted-on-the-Cloud

Description:
Deployed T-Pot, an open-source honeypot, in a cloud environment. The project utilizes Azure Cloud services, Debian GNU/Linux for T-Pot, and additional tools such as Putty for smooth installation and operation.

Prerequisites for T-Pot Installation:

Microsoft Azure Cloud Platform
Debian 11 "Bullseye" (x64) Image
Recommended RAM Size: 8-16 GB
Putty

T-Pot Installation Commands
sudo apt update
sudo apt upgrade -y
sudo apt install git
sudo git clone https://github.com/telekom-security/tpotce
sudo cd tpotce/iso/installer/
sudo ./install.sh --type=user

To access T-Pot's Web Interface, navigate to:
https://(AzurePublicIP):64297

