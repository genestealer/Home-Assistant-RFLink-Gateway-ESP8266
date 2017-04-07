# Home-Assistant-RFLink-Gateway-ESP8266
Home Assistant to RFLink Gateway using a NodeMCU (ESP8266 Wifi module)

## My Setup
My [Home Assistant Config](https://github.com/Genestealer/Home-Assistant-Configuration)
  
## Detail

[Home Assistant](https://home-assistant.io/) to [Arduino RFLink gateway](http://www.nemcon.nl/blog2/) using the [RFLink component](https://home-assistant.io/components/rflink/).

Serial data is sent via the [esp-link V2.2.3](https://github.com/jeelabs/esp-link/releases/tag/v2.2.3) Wi-Fi serial bridge running on a NodeMCU (ESP8266 Wifi module) with ESP8266 TXD0 (pin D10) and RXD0 (pin D9) connected to Arduino MEGA 2560 RX (Pin 2) and TX (Pin 3) respectively. 

Wiring of transmitter and receiver is as per [Arduino Wiring](http://www.nemcon.nl/blog2/wiring) on RFLink Gatway.

### List of Parts
 - NodeMCU ESP8266 Wifi module [E.G.](https://www.aliexpress.com/item/V3-Wireless-module-NodeMcu-4M-bytes-Lua-WIFI-Internet-of-Things-development-board-based-ESP8266-esp/32647542733.html)
 - BSS138 bidirectional logic level converter (For serial pins) [E.G.](https://www.aliexpress.com/item/IIC-I2C-Logic-Level-Converter-Bi-Directional-Module-5V-to-3-3V-For-Arduino-Upgrade-to/32669684009.html)
 - Resistor based logic level converter (For CC2500) [E.G.](https://www.aliexpress.com/item/8CH-IIC-I2C-Logic-Level-Converter-Bi-Directional-Module-DC-DC-5V-to-3-3V-Setp/32238089139.html)
 
### Voltage Level Shifters
Due to different logic levels, a voltage level shifter is required between the 3.3V NodeMCU and 5V Arduino MEGA 2560 pins. The BSS138 bidirectional logic level converter has been tested for serial pins

### esp-link Configuration
WiFi mode:	STA
esp-link pin assignment:
- Reset: GPIO5 (Connected to Arduino reset pin)
- Conn LED: GPIO2/TX1 (LED on ESP module)
- Serial LED: GPIO4 (With external LED connected)
- UART pins: Normal
- RX pull-up: enabled

## Supporting Links
- [Home Assistant](https://home-assistant.io/)
- [Arduino RFLink gateway](http://www.nemcon.nl/blog2/)
- [RFLink component](https://home-assistant.io/components/rflink/)
- [Jeelabs esp-link](https://github.com/jeelabs/esp-link)


My setup, wiring:
![Diagram](https://raw.githubusercontent.com/Genestealer/Home-Assistant-RFLink-Gateway-ESP8266/master/RFLink_Gatway_bb.jpg)

My setup, photo:
![Diagram](https://raw.githubusercontent.com/Genestealer/Home-Assistant-RFLink-Gateway-ESP8266/master/Home-Assistant-RFLink-Gateway-ESP8266.jpg)
