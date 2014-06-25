ansible-raspyrouter
===================

Ansible deployment of raspberry pi based wifi router



Requirements:

- Raspbery Pi with Wheezy Minimal Image installed (http://www.linuxsystems.it/raspbian-wheezy-armhf-raspberry-pi-minimal-image/)
- Ralink USB wifi with AP mode (tested with RT2800/2870 and RT5370 )
- Python (apt-get install python)
- connected to DHCP internet connection (uplink)

Once deployed, Raspberry pi will function as a wifi AP. Change SSID in groupvars/all
