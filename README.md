# VPN-Instructions

* Change region to Frankfurt
* Click on EC2
* Launch Instance
* AWS marketplace  -> OpenVPN (Free tier (2 clients for free)!)
* Pick t2.micro (Free tier)
* Create and download a new key pair
* Connect to the machine as root
* Enter to everything
* Connect as openvpnas
* Change passwd (sudo passwd openvpn) → admin and client password
* Go to IPv4:943/admin
* Login with openvpn and password of 4
* Change VPN setting to route all traffic through the VPN 
* Save settings
* Update running server
* Go to IPv4:943
* Login with same openvpn/password
* Download the configuration
