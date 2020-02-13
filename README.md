# tinyhome

Adventures in Hass.io and a tiny apartment.



This repo is to catalog my experiences in applying the Raspbery Pi 4 to my home automation setup as well as dipping into docker-style integrations.


***Raspberry Pi 4***

* 2Gb RAM and a much faster processor means "more room for activities!"
* 64gb Sandisk Ultra MicroSD
* TO DO: Upgrade to USB-Attached SSD or USB flash memory

## What hass.io currently runs:

* [zigbee2mqtt](https://www.zigbee2mqtt.io/) (currently has a device limit of 25)
* [Homebridge](https://github.com/home-assistant/homebridge-homeassistant)
* [Let's Encrypt](https://letsencrypt.org) : Free, Open, Automated SSL/TLS Certificate Authority Service
* [Node Red](https://github.com/hassio-addons/addon-node-red) : Flow-based Programming for the Internet of Things
* [ESPHome](https://esphome.io/) convenient flashing, configuration, and management of ESP-based devices
* Spotify Connect
* SSH Server, Log Viewer, Configurator, Samba Share, Hassio Google Drive Backup, Android Debug Bridge,TasmoAdmin, Mosquitto


## To implement with Hass.io:
* [Ubiquiti Unifi Controller](https://unifi-sdn.ubnt.com) 
* [Pi-Hole](https://pi-hole.net/) and its component for HA: [Sensor](https://home-assistant.io/components/sensor.pi_hole/)
* A print server?  Maybe this is possible.  (for an ex-UPS Zebra LP2844 4x6 Label Printer)
* [HASwitchPlate](https://github.com/aderusha/HASwitchPlate) Hardware done, only need to integrate this to the HASS.io configuration 


## In the future I hope to:
* Add more lighting controls and automation based on movement/presence
* Integrate CEC HDMI Control device on Raspberry Pi Zero to automate programs for media and display  on-screen messages (tools: http://www.cec-o-matic.com/ , https://github.com/michaelarnauts/cec-mqtt-bridge , http://wiki.kwikwai.com/index.php?title=The_HDMI-CEC_bus , https://github.com/nvella/mqtt-cec )
* Use BalenaCloud to manage deployment of my devices

## Hardware 
  * Networking
    * Google GFRG Fiber Converter
    * Ubiquiti Edgerouter X    
    * Ubiquiti Unifi 802.11ac AP Lite
    * Cisco SG300-20 Managed PoE Switch
    * Various switches throughout the home
  * Home Control Infrastructure
    * Lutron Caseta Pro Hub
    * Zigbee USB Dev stick by TI [How to flash an inexpensive CC2531 dev device](https://www.zigbee2mqtt.io/getting_started/flashing_the_cc2531.html)
    * Broadlink RM PRo - 433mhz / RF / Infrared transmitter & receiver.  Works great with cheapo 433mhz plugs (which I have currently phased out), my rf-controlled projector screen, and IR home theater components alike.
    * Apple TV 4 - Necessary for for Apple HomeKit offsite access and automation, a capable media endpoint
    
  * Lights and Switches
    * Lutron Caseta
    * Lutron IR Wireless Dimmer
    * esp8266 Plugs running Tasmota
    * Sonoff inside a Lamp
    * Sonoff Micro
    * Kesin KS-604S Dual in-wall Socket with Controllable USB [KS-604s Tasmota Device Registry](https://templates.blakadder.com/kesen_KS-604S.html)
    * SP 201 Dual Socket w/Power Monitoring [Tasmota Device Registry](https://templates.blakadder.com/sp201dual.html)
    
  * Security & Presence Detection
    * iOS Presence Detection
    * XaioMi Aqara Motion & Sensors
    * XaioMi Aqara Door/Window Sensors
 
    
  * Media
    * [Plex](https://www.plex.tv/) The glue that binds all media together
    * Apple TV 4
    * Apple Airport Express - Four zones additional to the Home Theater, not particularly integrated into my HA setup, but useful for music in the kitchen, dining room, and shower.
    * Pioneer Connected HTR
    * Epson HT Projector
    * FAVI drop
    * Google Chromecast 2, Audio
    * Amazon Fire TV Stick
## Hardware and Build Wishlist
* Inobtrusive "status lights" for security, weather, etc (In Progress)
* [Abode home security](https://home-assistant.io/components/alarm_control_panel.abode/)








## Hardware used in my previous setup:
  
  * Networking
    * Google GFRG Fiber Converter
    * Ubiquiti Edgerouter X    
    * Ubiquiti Unifi 802.11ac AP Lite
    * Cisco SG300-20 Managed PoE Switch
    * Various switches throughout the home
  * Home Control Infrastructure
    * Wink Hub Ver 1 (I, as of yet, have been too cheap to pick up a Lutron Caseta Hub Pro, but my wink hub facilitates communication with the Caseta dimmers and the Wink Relay)
    * Broadlink RM PRo - 433mhz / RF / Infrared transmitter & receiver.  Works great with cheapo 433mhz plugs, my rf-controlled projector screen, and IR home theater components alike.
    * Apple TV 4 - Necessary for for Apple HomeKit offsite access and automation

  * Lights and Switches
    * Lutron Caseta
    * Lutron IR Wireless Dimmer
    * Wink Relay (two gang on/off switch and dashboard that was purchased as a Cyber Monday closeout deal)
    * esp8266 Plugs running Tasmota
    * Sonoff Original inside a Lamp
    
  * Security & Presence Detection
    * iOS Presence Detection
    * XaioMi Aqara Motion & Sensors
    * XaioMi Aqara Door/Window Sensors
 
    
  * Media
    * [Plex](https://www.plex.tv/) The glue that binds all media together
    * Apple TV 4
    * Apple Airport Express - Four zones additional to the Home Theater, not particularly integrated into my HA setup, but useful for music in the kitchen, dining room, and shower.
    * Pioneer Connected HTR
    * Epson HT Projector
    * FAVI drop
    * Google Chromecast 2, Audio
    * Amazon Fire TV Stick
 
