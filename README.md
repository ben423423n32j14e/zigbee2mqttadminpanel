# Zigbee2MQTT Admin Panel
[Node-Red-Dashboard](https://github.com/node-red/node-red-dashboard) web interface for controlling [Zigbee2MQTT](https://github.com/Koenkk/zigbee2mqtt)

Features:
* Popup notifications indicating device pairing status (if pairing devices).
* Rename devices
* Remove devices
* Permit join
* Set the console logging level
* See if the Zigbee2MQTT bridge is online
* Display devices

Instructions:

1) Install [Node-Red](https://nodered.org/)
2) Create a Flow called "Zigbee2MQTT Admin Panel"
3) Settings > "Manage palette" > Install, search for and install "node-red-dashboard"
4) Import flow into "Zigbee2MQTT Admin Panel" flow
5) Visit: http://ipaddress:1880/ui

Notes:
Currently in beta, some features may or may not work correctly.

![Screenshot](screenshot.png)
