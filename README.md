# SurfShark VPN GUI

A GUI client for connecting to the SurfShark VPN.

![surfshark-vpn-gui](https://user-images.githubusercontent.com/554899/79599601-c6247200-80b3-11ea-9cbb-ef31ed8d18b8.png)

### About
There is currently no official GUI client for the SurfShark VPN on Linux, so this is to fill the need! This client uses OpenVPN to setup the connection, so the surfshark-vpn package is not required.

### Instructions

0. (Prep) Install Dependencies:
  ```
   sudo apt install git openvpn python3 python3-pip
   sudo pip3 install wxwidgets
  ```
1. Clone the surfshark-vpn-gui repo:
  ```
   git clone --depth 1 https://github.com/jakeday/surfshark-vpn-gui.git ~/surfshark-vpn-gui
  ```
2. Change directory to surfshark-vpn-gui repo:
  ```
   cd ~/surfshark-vpn-gui
  ```
3. Run the client:
  ```
   python3 surfshark.py
  ```
4. With the client open, be sure to enter your SurfShark credentials by clicking File and then Enter Credentials.

### Donations Appreciated!

PayPal: https://www.paypal.me/jakeday42

Bitcoin: 1AH7ByeJBjMoAwsgi9oeNvVLmZHvGoQg68
