ansible-raspyAP
===================

Ansible deployment of raspberry pi based WIFI AP



Requirements:

- Raspbery Pi with Wheezy Minimal Image installed (http://www.linuxsystems.it/raspbian-wheezy-armhf-raspberry-pi-minimal-image/)
- Ralink USB WIFI with AP mode (tested with RT2800/2870 and RT5370 )
- Python (apt-get install python)
- connected to DHCP internet connection (uplink)

Once deployed, Raspberry pi will function as a wifi AP. Change SSID in groupvars/all . No encryption/security, AP will be open.
