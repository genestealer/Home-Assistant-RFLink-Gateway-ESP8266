# Home-Assistant-RFLink-Gateway-ESP8266
Home Assistant to RFLink Gateway using a NodeMCU (ESP8266 Wifi module)

## My Setup
My [Home Assistant Config](https://github.com/Genestealer/Home-Assistant-Configuration)

## ToDo 
Add configuration for ESP link

List bill of materials.

Explain why two types of level converters are used
  
## Setup

[Home Assistant](https://home-assistant.io/) to [Arduino RFLink gateway](http://www.nemcon.nl/blog2/) using the [RFLink component](https://home-assistant.io/components/rflink/). Serial data is sent via the [esp-link V2.2.3](https://github.com/jeelabs/esp-link/releases/tag/v2.2.3) Wi-Fi serial bridge running on a NodeMCU (ESP8266 Wifi module) with ESP8266 TXD0 (pin D10) and RXD0 (pin D9) connected to Arduino MEGA 2560 RX (Pin 2) and TX (Pin 3) respectively. 

Wiring of transmitter and receiver is as per [Arduino Wiring](http://www.nemcon.nl/blog2/wiring)

## Supporting Links
- [Home Assistant](https://home-assistant.io/)
- [Arduino RFLink gateway](http://www.nemcon.nl/blog2/)
- [RFLink component](https://home-assistant.io/components/rflink/)
- [esp-link V2.2.3](https://github.com/jeelabs/esp-link/releases/tag/v2.2.3)

![Diagram](https://raw.githubusercontent.com/Genestealer/Home-Assistant-RFLink-Gateway-ESP8266/master/RFLink_Gatway_bb.jpg)

My setup:
![Diagram](https://raw.githubusercontent.com/Genestealer/Home-Assistant-RFLink-Gateway-ESP8266/master/Home-Assistant-RFLink-Gateway-ESP8266.jpg)
