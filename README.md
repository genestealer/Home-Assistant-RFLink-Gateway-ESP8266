# Home-Assistant-RFLink-Gateway-ESP8266
Home Assistant to RFLink Gateway using a NodeMCU (ESP8266 Wifi module)

## My Setup
My [Home Assistant Config](https://github.com/Genestealer/Home-Assistant-Configuration)
  
## Detail

[Home Assistant](https://home-assistant.io/) to [Arduino RFLink gateway](http://www.nemcon.nl/blog2/) using the [RFLink component](https://home-assistant.io/components/rflink/).

Serial data is sent via the [esp-link V2.2.3](https://github.com/jeelabs/esp-link/releases/tag/v2.2.3) Wi-Fi serial bridge running on a NodeMCU (ESP8266 Wifi module) with ESP8266 TXD0 (pin D10) and RXD0 (pin D9) connected to Arduino MEGA 2560 RX (Pin 2) and TX (Pin 3) respectively. 

Wiring of transmitter and receiver is as per [Arduino Wiring](http://www.nemcon.nl/blog2/wiring) on RFLink Gatway.

### Example Bill Of Materials
 - [NodeMCU Amica (ESP8266)](https://www.aliexpress.com/item/V3-Wireless-module-NodeMcu-4M-bytes-Lua-WIFI-Internet-of-Things-development-board-based-ESP8266-esp/32647542733.html)
 - [BSS138 bidirectional logic level converter (For serial pins)](https://www.aliexpress.com/item/IIC-I2C-Logic-Level-Converter-Bi-Directional-Module-5V-to-3-3V-For-Arduino-Upgrade-to/32669684009.html)
 - [Resistor based logic level converter (For CC2500) E.G.](https://www.aliexpress.com/item/8CH-IIC-I2C-Logic-Level-Converter-Bi-Directional-Module-DC-DC-5V-to-3-3V-Setp/32238089139.html)
 - [CC2500 2.4GHZ Transceiver](https://www.aliexpress.com/item/Wireless-Module-CC2500-2-4G-Low-power-Consistency-Stability-Small-Size/32702148262.html)
 - [433Mhz ASK Transmitter](https://www.aliexpress.com/item/433MHz-100-Meters-Wireless-Module-Kit-ASK-Transmitter-STX882-ASK-Receiver-SRX882-2Pcs-Copper-Spring-Antenna/32637181317.html)
 - [Breadboard](https://www.aliexpress.com/item/1pcs-Quality-mini-bread-board-breadboard-8-5CM-x-5-5CM-400-holes/32803112223.html)
 - [Breadboard jumper wires](https://www.aliexpress.com/item/Packed-Breadboard-Line-Bread-Board-Jumper-140-pieces-Bread-Board-Cable/32647063474.html)
 - [Example remote control sockets](https://www.amazon.co.uk/Status-Remote-Control-Socket-Pack/dp/B003XOXAVG)
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
