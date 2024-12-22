RFLink Latest Firmware Version
  
The latest firmware version can be found at:  
http://www.rflink.nl
  
Please note that the RFLink Gateway is a freeware project.   
Stuntteam is not making money in any way. We are not connected to any shops.      
This means that there are no unlimited funds to purchase test devices,   
it also means the project has to rely on you, the user, to send debug data.  
  
If you want to contribute to this project, you can send a donation which is more than welcome (see www.nemcon.nl/blog2 donation button),   
or help with sending debug data of unsupported devices (you can even write and contribute plugins and/or code fixes),  
or donate the device that you would like to see supported.  
   
For the implementation of additional 2.4Ghz protocols we could use some simple MySensor device or Milight.   
For the implementation of additional 868Mhz protocols we could use some devices as well.   
If you have anything that you do not use, send a mail to <b>frankzirrone@gmail.com</b>   
Thanks in advance!  
  
------------------------    
Debug data:   
If you have mailed debug data and your device is not implemented yet,    
then you can be sure that we are still working on it!   
We receive lots of data to analyse and on top of that also receive lots of   
support requests that all take time to answer.   

------------------------   
Changelog:   

RFLink v1.1 - R51:
- New Device: Unitec W186-F Temperature sensor
- New Device: Amazon Basics Meat Thermometer
- New Device: Valoin Wireless Digital Meat Thermometer With Dual Probe
- New Device: Atech-WS308 temperature sensor
- New Device: Auriol 4-LD5661, Auriol 4-LD5972, Auriol 4-LD6313 temperature & rain sensor
- New Device: Auriol AFT77B2 temperature sensor
- New Device: Auriol AFW2A1 temperature & humidity sensor
- New Device: Auriol AHFL 433B2 IPX4 temperature & humidity sensor
- New Device: Auriol HG02832, Auriol HG02832D temperature & humidity sensor
- New Device: Rubicson 48957 temperature & humidity sensor
- New Device: Baldr rain meter
- New Device: Rainpoint rain meter
- New Device: TFA-Dostmann-30.3222.02 Combi Sensor Thermo/Hygro/Wind
- New Device: TX141-BV3
- Fixed: Funkbus handling
- Fixed: Acurite extremely low temperature value handling
- Fixed: LightwaveRF handling
- Fixed: Milight handling
- Added: Hager additional command information
- Changed: Additional optimizations

R50
- New Device: Abalon Curtain remote (BE301) (receive)
- New Device: Lanboo Curtain remote (receive)
- New Device: Zaffer Blinds remote (receive)
- New Device: Marimex Pool Thermometer
- New Device: Gira 225500
- New Device: Deltia 8.33 - Thermostat - X2D 
- New Device: Deltia 8.03 - Thermostat - X2D REF 6050417
- New Device: Deltia 1.03 - 3 zone - X2D (including support for pairing/association)
- New Device: Calybox 220 - 3 zone - X2D
- New Device: DPM Switch sets (Thanks: Olaf)
- New Device: Universal Blyss receptor ref 582857
- Added: Acurite 899 rain meter (Thanks: Peter)
- Added: Funkbus transmit
- Added: Another Chinese screen motor set following a Dooya variant
- Added: Additional Hager support
- Added: Oregon THN129
- Added: Broadlink SmartOne S1C sensors
- Added: Tellstick Temperature and humidity sensors (Thanks: Ivan)
- Added: Viking 02038 Temperature and Humidity sensor
- Added: Viking 02042 Temperature sensor and Rain meter
- Added: option to force WH2 protocol for some sensors in case of incorrect detection
- Fixed: HomeEasy HE100
- Fixed: Froggit F007TH decoding issues
- Fixed: Viking negative temperatures
- Fixed: Alecto V4 better handling when multiple devices are used
- Fixed: Conrad Pool Thermometer recognition
- Fixed: Banggood SKU174397 allowing multiple devices
- Fixed: Various changes to RTS to improve detection
- Changed: massive overhaul of the code to clean up and free important resources
- Changed: RTS: Increased number of supported devices to 32
- Removed: QRFdebug, use RFDebug for all logging

R48:  
- New Device: British Gas RC Plus Thermostat  
- New Device: Drayton Digistat +2RF Thermostat  
- New Device: Worcester Bosch DT10RF Thermostat  
- New Device: Danfoss TP4000 Thermostat  
- New Device: Vaillant VRT 340f Thermostat  
- New Device: CalorMatic 340f Thermostat  
- New Device: Hager Flash Thermostat  
- New Device: Thermoflash Thermostat  
- New Device: Piloteco Thermostat  
- New Device: Sanfil Thermostat  
- New Device: Monomat Thermostat  
- New Device: Micromat Thermostat  
- New Device: Monotron Thermostat  
- New Device: M moprog RF Thermostat  
- New Device: Calidou Plus Thermostat  
- New Device: Radiafonte II Thermostat  
- New Device: Bellagio II Thermostat  
- New Device: Verplus Thermostat  
- New Device: Palatino Thermostat  
- New Device: Verlys Evolution Thermostat  
- New Device: Melody Evolution Thermostat  
- New Device: Millenium Triphas  Thermostat  
- New Device: Sensual SAS Thermostat  
- New Device: Sensual Bains Thermostat  
- New Device: Athena Millenium Thermostat  
- New Device: Athena Plenitude Thermostat  
- New Device: Brel (and compatible) light switch  
- New Device: Beurer BG64 (and possibly BF100) scales  
- New Device: Falmec hoods  
- Added: support for X10 Marmitec DS90/DS91 tamper switch  
- Fixed: Milight color issue  
- Fixed: Milight brightness issue  
- Fixed: Milight RGB-CCT pairing made easier with pair/unpair commands 
- Fixed: Milight CRC calculation on some of the protocol versions   
- Fixed: Improved Kerui D025/D026 handling  
- Fixed: Improved Mertik filtering  
- Fixed: bug with Europe switchset unit numbers  
- Fixed: Corrected TFA timing  
- Fixed: Improved Cresta packet filtering   

R47:  
- New Device: Micro Tybox X2D / Tybox H X2D Thermostats (works with 433 and/or 868 mhz)   
- New Device: Tybox 310 X2D Thermostat (868mhz)   
- New Device: Delta Dore - Deltia 8.03 X2D Thermostat (868mhz)    
- New Device: TYXIA 261/461 X2D micro modules (868mhz) (Receive only, more logs needed)      
- New Device: Milight RGB+CCT (a.o. 4-zone FUT092/ 8-zone FUT089)       
- New Device: Milight RGB (a.o. FUT098)    
- New Device: Bofu motor BF-301, EY1612, EY1624 and others    
- New Device: Oregon Scientific SL109   
- New Device: AR53002 / AR50055 X2D Thermostats    
- New Device: Atlantic MD-210R / Focus MD-210R - 868mhz door contact   
- New Device: Legrand CAD Radio    
- New Device: Gelia EMW100T switch set   
- New Device: ELEC EDB-40 / QH-1085TX V1.1 Quhwa doorbell    
- New Device: X10 Sensors   
- New Device: Ambient FT004T temperature sensor    
- New Device: Ambient FT004B temperature sensor    
- New Device: ASA radio technology Go-1   
- New Device: Telis 4 Modulis RTS   
- New Device: Added support for a new version of the Rubicson WT0122 pool thermometer   
- New Device: Renkforce E0190TA and compatible temperature sensors    
- New Device: Ematronic AC114-01B shutter/blinds controller   
- New Device: Yooda Melody shutter/blinds controller   
- New Device: Viking 02813 Temperature sensor  
- New Device: Marquant 943134 Temperature sensor   
- New Device: Arlec RC10 switch set   
- New Device: V2 Phoenix remote signals (Receive only)   
- New Device: IDK CAR-200 doorbell (Receive only)   
- New Feature: GPIO pin state at boot can be selected with a wire from pin 5 to ground to set the pin default to high   
- Added: X2D/X3D protocol support    
- Added: Milight RGB and RGB+CCT protocol support   
- Added: Direct dimming support for Flamingo and compatible devices    
- Added: Additional WH3 detection   
- Added: Two Additional Dooya protocol flavors   
- Added: Additional Dooya signal recognition   
- Added: Additional Blyss remote control recognition   
- Added: Additional Brell remote control recognition   
- Added: STOP command support to (first) extended RTS protocol version   
- Added: Support for second extended RTS protocol version  
- Added: Additional Pair option for Bofu motor devices   
- Added: upon request added 6 additional GPIO pin's for generic use    
         The GPIO pins are often used to 'press buttons' on incompatible devices   
- Fixed: Added pairing command for Ansluta   
- Fixed: Increased transmission duration for Ansluta   
- Fixed: corrected barometric pressure value of BTHR918   
- Fixed: UPM Esic negative temperatures   
- Fixed: Further improved X10 protocol detection   
- Fixed: 'newkaku' send command handling improved   
- Fixed: 'newkaku' group commands put at a unique switch number    
- Fixed: imrpoved newkaku filtering   
- Fixed: improved Acurite SL109 negative temperature handling     
- Fixed: CM113 ampere precision   
- Fixed: Milight: bug in unit selection   
- Fixed: bug with the number of RFCustom records   
- Fixed: removal of RFCustom records   
- Fixed: Improved Xiron sensor detection   
- Fixed: Alecto rain meter values   

R46: 
- New Device: Applidom DM82 motion sensor   
- New Device: OWL Intuition PV / CM180i     
- New Device: WH2A temperature sensors    
- New Device: WH1285 TX (WH-5) Temp & Humidity sensor    
- New Device: ABB lightswitch type 3299a-11900 (a.k.a. TX Tango) (Receive only!)   
- New Device: Velleman VM130T Motor control    
- New Device: HRC 101 Motor control   
- New Device: AC512-02 AC to RF projection screen trigger   
- New Device: 2 new Dooya protocol flavors   
- New Device: D-YA / Diya Motor control   
- New Device: Konx doorbell model 602 (Receive only!)   
- New Device: Doorman doorbell (Receive only!)   
- New Device: Acurite 3in1 3N1TXR / 3N1TXC (Thanks: JR)   
- New Device: Byron BY532E (Receive only!)    
- New Device: Stagnoli remotes   
- New Device: Blyss temperature sensors (Ref.630467) (Thanks: JD)   
- New Device: Grundig QH-831A 2010525 & Quhwa QH-831A doorbell     
- New Device: 868mhz: Woonveilig security sensors   
- New Device: 868mhz: Egardia security sensors   
- New Device: 868mhz: Alecto WS3900    
- New Device: Yale HSA3000/6000 alarm system sensors   
- New Device: Sartano 50080 (Harald Nyborg 2794) switch set   
- New Device: Astrell 85 portal motorization system   
- New Device: Philips AJ7010/12          
- New Feature: Learn RF device signals that use a standard EV1527/PT2262 protocol   
- Fixed: Some small eeprom handling issues   
- Fixed: Improved AI protocol priority handling    
- Fixed: various CC2500 issues, make sure pin 6 is wired to ground to use CC2500!   
- Fixed: Tightened Warema EWFS detection   
- Fixed: RTSlongTX command   
- Fixed: ON/OFF vs UP/DOWN command handling   
- Fixed: UPM Esic extended packet detection and increased sanity checks on data   
- Fixed: Optimized Novatys timing   
- Fixed: AlectoV3 Humidity value validation   
- Fixed: FineOffset vs Alecto improved differentiation, Note: device ID's have changed for WS1100  
- Fixed: Alecto WS-1100 humidity   
- Fixed: AlectoV4 Some packets contained an invalid temperature   
- Fixed: Globaltronics GT-WT-02 negative temperature/channel number mixup   
- Fixed: Globaltronics GT-WT-02 now always reporting a humidity   
- Fixed: Tristate send, removed debug message and fixed a timing bug   
- Fixed: WS7000 rain reporting   
- Fixed: Added additional Brel protocol variant    
- Fixed: LightwaveRF turned MOOD commands into regular switch commands so any home automation software can use them   
- Fixed: Improved Friedland doorbell signal detection   
- Fixed: Acurite 5in1 corrected wind speed, wind direction and rainfall values (Thanks: Xztraz.)   
- Fixed: Improved AcuRite 00592TXR detection   
- Fixed: Tunex zero humidity value   
- Fixed: Improved Home Confort transmit routine and added up/down support (Thanks: Geert)      
- Fixed: Battery detection in Prologue protocol   
- Fixed: Added channel number to device ID for THGR810   
- Fixed: Added channel number support to Warema devices   
- Fixed: Improved UPM ESIC protocol detection   
- Fixed: Improved SA33 detection   
- Fixed: Gaposa protocol timing   
- Added: battery status on various Alecto/Maplin devices (Thanks: Ad)  
- Added: Hardware & Software configuration via i/o pins:    
         pin  6 to ground for: CC2500 enable   
         pin  7 to ground for: disable internal pull-up on RF data in   
         pin 12 to ground for: reset of EEPROM settings   

R45: 
- New Device: Silvercrest switch set IAN276299   
- New Device: Silvercrest switch set IAN113854   
- New Device: Silvercrest switch set IAN91210   
- New Device: Quigg switch set GT-9000 (Tevion/Globaltronics/ALDI)   
- New Device: Unitec switch set 4811 model 50028 (Intertek)     
- New Device: Cotech switch set 36-6361   
- New Device: Sartano switch set, Model 50028, HN 10047    
- New Device: Electro Depot switch set, article code 940557   
- New Device: BL999 weather sensor    
- New Device: Digi-Tech 4-LD14554 Outdoor temperature sensor (Thanks: PJA)   
- New Device: PLC-T4022G X10 RF to Powerline    
- New Device: X10 UR76 E Remote Control    
- New Device: Konig Alarm system sensors    
- New Device: Alecto 1200 alternative protocol version   
- New Device: Oregon EW99   
- New Device: Smartwares RM174RF Smoke detector   
- New Device: FirstLine FWS802 Pool Thermometer (Thanks: BC)   
- New Device: Liwin Shutters / Blinds controller   
- Fixed: MiniGPIO command structure   
- Fixed: Conrad RSL pair command added    
- Fixed: Warema EWFS (Thanks: SH)   
- Fixed: Removed Ningbo debug message   
- Fixed: Mebus protocol detection for Auriol Z29536 IAN55982   
- Fixed: Removed debug messages on Atlantic protocol   
- Fixed: Milight color and brightness changing on groups   
- Fixed: DKW2012 Humidity conversion   
- Fixed: DKW2012 Wind speed conversion (Thanks: HJ)    
- Fixed: Xiron ID sometimes had an incorrect bit   
- Fixed: Blyss/Avidsen transmit    
- Fixed: Aster protocol split on/off and dim/bright into separate devices   
- Fixed: Improved detection of WH5029   
- Fixed: Improved HE800 protocol detection   
- Fixed: Improved detection of Cleverwatts, Kerui and compatible devices   
- Fixed: Proper handling of incoming serial commands for KAKU and related devices   
- Fixed: Improved Chacon EMW200 detection   
- Added: RTS protocol option to swap ON/OFF command   
- Added: RTS long TX option to extend the RTS transmit time   
- Added: "Settings reset" feature   
- Added: Extended Gaposa protocol   
- Added: Lacrosse V3 protocol support for negative temperature values   

R44: 
- New Device: Ikea Ansluta (2.4 Ghz device, CC2500 transceiver required)    
- New Device: Philips Living Colors Generation 1 (2.4 Ghz device, CC2500 transceiver required)   
- New Device: Friedland DC44   
- New Device: Warema EWFS shutters and awnings   
- New Device: Bosch DID09T951, Bosch DID09T950 and compatible ventilation units   
- New Device: Siemens SF-01 and compatible ventilation units   
- New Device: Wave Design SF-01 and compatible ventilation units   
- New Device: Visonic MCT-302 open and close signal   
- New Device: Ningbo KD-205-1 switch set     
- New Device: Steffen Power Switch (1204380 3M)       
- New Device: Bresser weather sensor     
- New Device: RFTech 210TX weather sensor   
- New Feature: Bluetooth LE Advertisement packet sniffing *experimental* (NRF24L01 required, needs to be wired for MiLight)   
- New Feature: MySensors packet sniffing *experimental* (NRF24L01 required, needs to be wired for MiLight)   
- New Device: MySensors temperature and humidity devices (more types to follow) (NRF24L01 required, needs to be wired for MiLight)      
- Fixed: Improved OWL CM130 recognition    
- Fixed: Revolt power reporting corrected   
- Fixed: RFmeter values presented in hexadecimal      
- Fixed: Improved Baldr signal recognition      
- Added: Friedland PIR checksum calculation   
- Added: GPIO 4 input and 4 output pins can be used as on/off or push button devices      

R43:
- New Device: MiLight WW/CW remote & Bulbs   
- New Device: WH3 temperature sensors   
- New Device: Alecto 1300 Wireless Plant Monitor   
- New Device: Unitec W235 Climate sensor   
- New Device: Jula / Marquant 943134 temperature sensor   
- New Device: Inovalley SM200   
- New Device: DC250 motor controller   
- New Device: Maplin Weather Station N96GY, Fine Offset WH1080, Fine Offset WH1081, Watson W-8681,    
              Digitech XC0348 Weather Station, PCE-FWS 20, Elecsa AstroTouch 6975, Froggit WH1080   
- New Device: Loh Electronics 02812 Temperature and Humidity sensor     
- New Device: Excelvan weather station   
- New Device: Master Electrician RC-012-1-TR-009    
- New Device: Home Confort STHI 100 temperature/humidity sensor   
- New Device: Ditec Garage Door remote control   
- New Device: Acurite 609TXC (alternative protocol)   
- New Device: WS7000-27, WS7000-28 Thermometer   
- New Device: WS7000-25 Thermo/Humidity, WS7000-22 Thermo/Humidity    
- New Device: WS7000-19 Brightness Luxmeter   
- New Device: Holtek HT6P20 (and compatible) Door, Window and PIR sensors (Thanks: Douglas Gazineu)   
- New Device: Ambient Weather / Frogit F007TH   
- New Device: Ambient Weather / Frogit F007T   
- New Device: Ambient Weather / Frogit F007PF   
- New Device: SelectPower switchset   
- New Device: Profile led dasegno   
- New Device: KERUI D026 Door Window Sensor   
- New Device: LaCrosse TXT141-BV2   
- New Device: Baldr B0317   
- New Device: Atlantic MC-335 PIR   
- New Device: RTS sensor protocol / Soliris   
- New Device: RTS Extended protocol / Eolis 3D   
- Fixed: Removed slash (/) from device names   
- Fixed: Removed RTS and other debug data   
- Fixed: Avidsen switch issue   
- Fixed: Avidsen temperature data detection   
- Fixed: Blyss & Avidsen pairing working correctly    
- Fixed: AB440R signal detection     
- Fixed: Chuango signal detection    
- Fixed: Improved Promax detection      
- Fixed: Additional check to make sure Milight send is not used when Milight support is disabled    
- Fixed: WS2500-19 now correctly reporting Lux value   
- Fixed: Milight RGBW Remote and WW/CW (Dual) Remote Control operating simultaneously with RGBW   
- Fixed: Livolo On/Off state     
- Fixed: Brel timing     
- Fixed: Novatys detection    
- Fixed: AMST606 detection issues   
- Fixed: SelectRemote doorbell retransmission     
- Fixed: Byron SX doorbell retransmissions   
- Fixed: Byron SX doorbell recognition   
- Fixed: Further improved the RF Environment Optimization System   
- Fixed: improved the detection of Acurite devices   
- Fixed: improved the detection of Cresta devices   
- Fixed: improved the detection of Atlantic devices   
- Added: NRF24L01 hardware detection, activating MiLight without NRF will result in MiLight being disabled      
- Added: Smarthome YC-4000B protocol variant    
- Added: New Brel protocol version     
- Added: WS7000 protocol variant   

R42: 
- New Device: Mi-Light/LimitlessLED/Applamp/Easybulb bridge functionality (2.4 Ghz, NRF24L01 with Milight wiring required)
- New Device: Hama SD-UN5-RF switch set    
- New Device: Acurite Tower sensors    
- New Device: Pollin PFR-130 Temperature & Rain meter   
- New Device: Gaposa Blind/Shutter control (a.o. model QCT3S)      
- New Device: Byron BY35 / BY301    
- Added: Command "echo" function to auto create devices without the need of remote controls   
- Added: Command "rtsrecclean 9" function to clean a single rolling code table entry   
- Added: Command to invert the ON/OFF handling of the Tristate protocol   
- Fixed: improved Atlantic MD-210R detection   
- Fixed: improved DKW2012 detection to cover variations of the signal   
- Fixed: Smarthome YC-4000B detection   
- Fixed: improved RTS packet detection to prevent false positives   
- Fixed: improved FA500 packet detection to prevent false positives   
- Fixed: Modified X10 security sensor packet detection    
- Fixed: Modified maximum humidity limit   
- Fixed: Improved signal ARC detection   
- Fixed: Chacon EMW200 detection    
- Fixed: Nexa WST-512 detection   
- Fixed: Oregon UV800  
- Fixed: CM113 ID     
- Added: Support for another MiLight remote variant   
- Added: PAIR/UNPAIR commands for MiLight

R41:  
- Added: support for up to 3 OWL devices operating at the same time   
- Fixed: Fine Offset without humidity value issue   
- Fixed: Issue with some sensor types blocking other sensor types    
- improved stability      

R40:  
- New Device: Oregon Scientific RTHN318     
- New Device: Halemeier HA-RHX-M2   
- New Device: LaCrosse WS2315   
- New Device: Lightwave Contact Switch   
- New Device: Acurite 5in1    
- New Device: XH110 temperature sensor   
- New Device: Cresta WXR710XL   
- New Device: Revolt NC-5461 Energy Meter, Otio, Profitec Funk Energiekosten Messgeraet   
- New Device: Dooya RF Roller blinds (ao. AC123-16 and others)   
- New Device: Envivo PO-1413 doorbell    
- New Device: Synapse SN-1613 doorbell   
- New Device: OWL +USB   
- New Device: OWL Micro CM130   
- New Device: Starlux ST101 PIR   
- Fixed: Forrinx doorbell   
- Fixed: WS2310 Windspeed issue with higher wind speeds   
- Fixed: Livolo, Increased number of transmits   
- Fixed: Conrad signal detection from Telstick Duo   
- Fixed: Some LightwaveRF transmit cases   
- Fixed: Keeloq, added button support   
- Fixed: Extended XT200 signal range   
- Fixed: Improved XT200/XH110, FineOffset & Alecto packet handling   
- Fixed: Some Oregon sensor packets were missed   
- Fixed: Oregon Humidity issue   
- Fixed: Changed protocol name AOK to Dooya   
- Fixed: added Dooya (and AOK) packet checksum   
- Fixed: Mebus and compatible sensors  
- Fixed: Cresta UV sensor temperature and extra data   
- Fixed: CM119 total values    
- Fixed: AlectoV1 Rain, Wind and Humidity values   
- Changed: WH5029, Added battery state, fixed negative temperature, wind speed and wind direction values      

R39: 
- New Device: Fine Offset / Viking / WMS Mk3     
- Fixed: Modified X10 security sensor pulse ranges   
- Changed: Removed some "extra debug" information at the end of valid packets because Jeedom was skipping data   

R38:   
- Added: Nodo 3.8 slave support   
- Added: Catching of anti-tampering for Atlantic sensors   
- Added: Oregon, extra checks for out of range values   
- Added: Tunex MF-0211 temperature sensor   
- Added: Alecto V3 Rain - Alternative version of WS1200   
- Added: Byron SX21   
- Added: MC145026 based sensors   
- Added: FunkBus RF detection (Insta/Berker/Gira/Jung) (receive only)   
- Added: Kingpin motor controls (send+receive)   
- Added: Livolo (send+receive)   
- Added: Koch remote controls (receive only)   
- Added: Additional X10 protocol devices   
- Added: Forest "Touch Sense Motors" Curtains (Thanks: JPe)   
- Added: Logipark   
- Fixed: Oregon Rain sensors (PCR800 and others) (Thanks: D.)   
- Fixed: Esic WT450H detection   
- Fixed: Alecto V1 wind speed values   
- Fixed: Alecto V3 Rain values and added battery level support (Thanks: D.)   
- Fixed: EverFlourish EMW203T detection   
- Changed: improved incoming command parsing   
- Regrouped plugins so others can be added more easily  

R37:   
- Added: RTS transmit   
- Added: ProMax 75.0006.14 (Sold at Action)    
- Added: Novatys wall switches   
- Added: Perel 4 channel switch set   
- Added: Atlantic MD-210R   
- Fixed: KD101 detected   
- Fixed: GlobalTronics GT-WT-01, GT-WT-02   
- Fixed: Alecto V4   
- Fixed: Silvercrest switches   
- Fixed: UPM/Esic negative temperature values   
- Fixed: Oregon data processing speed improvement   
- Fixed: Oregon V2 data processing and crc checks     
- Fixed: Oregon RTGN318    
- Fixed: Oregon wind speed    
- Fixed: Humidity for BTHR918, BTHGN129, etc.   
- Fixed: filtering out invalid packets for BTHR918, BTHGN129, etc.   
- Fixed: Chacon remote control   

R36:   
Note: Due to some internal code changes:   
Brel motor control might have a new ID    
Some Alarm devices have moved to a new product group and also got a new ID   
   
- Added: RF Environment Optimization System (Thanks: Snips)   
- Added: Maclean Energy MCE04 & 07 remote control and switches   
- Added: Brel DC90   
- Added: Medion MD 16179 doorbell (Receive only)   
- Added: Remote 546   
- Added: X10 security sensor protocol (a.o. Marmitek)   
- Added: Everflourish EMW100 / Cotech EMW100R (Thanks: J)   
- Added: Home Easy support for direct dim values    
- Added: SelectPlus Black Bell Button (non-A model)   
- Added: Silvercrest ian7443 type 10164 R RC202   
- Added: Atlantic's security sensors (receive only)   
- Added: (initial support for) FAAC TM signals (receive only)   
- Added: Oregon Scientific RTGN318   
- Added: WT0122 pool thermometer   
- Added: GlobalTronics GT-WT-01, GT-WT-02  
- Added: Rohrmotor24    
- Changed: Removed temperature limits on LaCrosse/TFA    
- Changed: Alecto V1 ID split (rolling code & channel number) for wind sensors   
- Fixed: Ikea Koppla signal detection    
- Fixed: Ikea Koppla dimming    
- Fixed: Cresta sensor reporting period when there is low traffic   
- Fixed: EMW200 transmit function   
- Fixed: Lightwave RF transmit function   
- Fixed: UPM/Esic minus temperature handling   
- Fixed: OWL CM180 (Big thanks to Snips)   
- Fixed: Various Oregon sensor optimizations (Big thanks to Snips)   
- Fixed: WS3600 rounding of rain values for precision   
- Fixed: WS3600 wind speed only passes one value at a time, Domoticz needs both. RFlink now passes the last know value for the non-received data   
- Fixed: Improved Alecto V4 signal detection   
- Fixed: Brel motor send command handling    
- Fixed: BofuMotor send command handling   
- Fixed: Elro Doorbell detection (among others: DB200Z, DB270)   

R35: 
- Added: Full A OK Controller/Motor support   
- Added: Brel motor support   
- Added: Krippl temperature/humidity sensor support   
- Added: Elro DB270 doorbell  
- Added: InoValley SM302 Temperature&Humidity sensor (Thanks: Pirion)   
- Added: EZ6 Temperature&Humidity sensor   
- Added: Alecto SA30 & SA33 Smoke Alarm  
- Added: Xiron RS8751E3 Weather sensor   
- Added: LightwaveRF (initial support, testers needed)   
- Added: support for Oregon sensor simulator   
- Fixed: Oregon OWL CM119, CM160, CM180  
- Fixed: Oregon UV800 uv index value   
- Fixed: Corrected WH440 temperature values    
- Fixed: Improved Philips SBC   
- Fixed: Improved Chacon EMW200   
- Fixed: Improved FA500 false positive detection   
- Fixed: Removed a slash in the UPM/Esic name   
- Fixed: Mertik transmit improved   
- Fixed: Optimized the Auriol/Xiron plugin   
- Fixed: LaCrosse negative temperatures and extended allowed pulse range (Thanks: VeryBitter)   
- Fixed: Alecto v1 Windspeed value   
- Fixed: Improved Otio remote signal handling   
- Fixed: corrected WH2 handling for Tesa WH1150 sensor (Thanks: Pirion)   
- Fixed: Lacrosse rain - wind needs some more work (Thanks: Arie)   
- Tested: tested and working: Lidl / Libra TR502MSV switches   
- Tested: tested and working: Avidsen door contact 102539   
      
R34:   
- Added: Heidemann HX Silverline 70290   
- Added: Eurochron EAS 301Z / EAS 302   
- Added: Znane-01 switch set sold at Biedronka (Impuls clone)   
- Added: HomeEasy HE800 protocol support   
- Added: Fine Offset Electronics WH2, Agimex Rosenborg 66796, ClimeMET CM9088   
- Added: Somfy Smoove Origin RTS (433mhz) (receive)   
- Tested: Eurodomest 972086 (Sold at Action in Belgium)   
- Added: Eurodomest revised protocol (full autodetection)  
- Added: Prologue temperature sensor support   
- Tested: tested and working: Home Confort, Smart Home PRF-100 switch set     
- Fixed: Auto detection of "Emil Lux"/LUX-Tools remote control/switch set (Sold at Obi.de Art.Nr. 2087971) (Impuls clone)    
- Fixed: Alecto WS1100 working properly again (Adjusted pulse range and displayed humidity value)   
- Fixed: Byron SX receive and send commands   
- Fixed: Ikea Koppla Send routines   
- Fixed: Improved the Impuls remote detection   
- Fixed: Impuls transmit   
- Changed: added checks for valid temperatures in various plugins   
   
R33:   
- Updated RFlink loader to version 1.03 to include a serial log option with command sending ability!    
   
- Added: Full automatic 'Flamingo FA500/SilverCrest 91210/60494 RCS AAA3680/Mumbi M-FS300/Toom 1919384' protocol support! (send & receive!)  
         Note: re-learn your FA500 Remote in Domoticz   
- Added: Unitec 48111/48112 (receive)   
- Added: Avidsen   
- Added: Somfy Telis (433mhz) (receive)   
- Fixed: Extreme temperature value rejection for various sensor types (TFA/LaCrosse)   
- Fixed: Improved Blyss send routines   
- Added: Support for old Xiron temperature sensor in Cresta plugin (Temperature only sensor was not handled)   
- Added: Biowin meteo sensor   
- Fixed: Imagintronix humidity and temperature values were sometimes incorrect   
- Fixed: AB4400/Sartano/Phenix detection corrected   
- Fixed: Modification to allow EMW200/203 to work better   
- Changed: ARC (and compatible) remote and switch handling improved   
- Fixed: Improved Impuls handling   
- Fixed: Auriol V3 minus temperature handling    
- Fixed: TRC02RGB send   
- Fixed: Oregon OWL180 data   
- Changed: Aster signal detection so that L^Home model 32311T is recognized as well   
- Changed: ID for Nodo Slave 'Wind direction/Wind gust' combined so that Domoticz can handle the data   
- Changed: Protocol handling order for 'multi-protocol' transmitting devices   
   
R32: 
- Added: Europe RS-200, Conrad TR-200  
- Added: Bofu motor transmit   
- Added: ARC group command support  
- Added: support for ARC based tri-state protocol  
- Tested and working: Hormann (868mhz) receive
- Changed: Bofu motor signal repetition detection improved  
- Fixed: Aster transmit routines  
- Fixed: plugin 003 output was not processed correctly by Domoticz  
- Changed: Chacon/Powerfix/Mandolyn/Quigg transmit routine and optimized timing  
- Changed: Increased the number of re-transmits in the Home Easy protocol to improve signal reception and distance  
- Changed: Sensor plugins now suppressing ARC derived protocols a bit better  
   
R31:  
- New Device: Forrinx Wireless Doorbell  
- New Device: TRC02 RGB controller  
- New Device: OWL CM180  
- New Device: ELMES CTX3H and CTX4H contact sensor  
- New Device: Bofu Motor (receive)  
- New Device: Aster / GEMINI   EMC/99/STI/037   
- Changed: EV1527 based sensors were reported as X10, now they are reported as EV1527. Note that it might be needed to re-add the devices to Domoticz  
- Changed: increased number of retransmits for ARC and AC protocols  
- Fixed: Koppla switch number was incorrect  
- Fixed: Powerfix/Mandolyn/Chacon Parity calculation in send routines  
- Fixed: Powerfix/Mandolyn/Chacon timing  
- Fixed Windspeed value for WS2300  
- Fixed: Home Easy HE300 ON/OFF signal was reversed  
- Changed: HomeEasy suppressing additional protocol data to avoid reporting the same event multiple times under different protocols  
- Fixed: More fixes to avoid duplicate reporting of the same event (various protocols)  
  
R30:  
- New Device: Conrad 9771 Pool Thermometer  
- New Device: SilverCrest Z31370-TX Doorbell  
- New Device: Smartwares remote controls (among others: SH5-TDR-K 10.037.17)   
- New Device: Chuango Alarm devices Motion/Door/Window etc. (among others: CG-105S)  
- New Device: Oregon Scientific NR868 PIR/night light  
- New Device: Oregon Scientific MSR939 PIR  
- New Device: Imagintronix Temperature/Soil humidity sensor  
- New Device: Ikea Koppla  
- New Device: Chacon (TR-502MSV, NR.RC402)
- Fixed: Arc protocol send  
- Fixed: Impuls. Note: pair devices with the KAKU protocol, the remote is recognized separately  
- Changed: Plugin 3 send method, combined routines  
- Changed: HomeConfort was recognized as Impuls, now using GDR2 name  
- Changed: HomeEasy remotes can deliver various signals, now skipping KAKU compatible signals and just reporting the HomeEasy code when both codes are transmitted  
- Fixed: HomeEasy group on/off command was reversed for HE8xx devices, now correctly detects differences between HE3xx and HE8xx  
- Fixed: HomeEasy was not able to control HE87x switches, changed the entire transmit routine  
- Changed: stretched Xiron timing checks  
- Changed: Various timing modifications (NewKaku/AC, Blyss) due to the new timing introduced at version R26  
- Changed: Plugin 61, Chinese Alarm devices, reversed bits as it seemed to correspond better to bit settings, increased address range  
- Fixed: Flamingo Smokedetector packet detection tightened up to prevent false positives  
- Fixed: Corrected Conrad RSL command interpretation  
- Added: Extended Nodo Slave support to support separate and combined sensors  
- Added: Extended Nodo Slave support to support pulse meters  
   
R29:  
- Fixed: AC/NewKaku high unit numbers were incorrect.   
         If you already have devices with high unit numbers in Domoticz, just throw them away and let them be recognized again  

R28:  
- Fixed: FA20RF smoke detector transmit from Domoticz  

R27:  
- Added: OSV1 battery status   
- Fixed: OSV1 boundaries and removed some debug info   
- Fixed: Some plugins set an incorrect sampling rate divider value   
- Changed: AlectoV1 false positives filter was too agressive  
  
R26:
- Added: QRFDEBUG command to do faster logging of undecoded data  
- Added: VERSION command  
- Added: Powerfix/Quigg switches  
- Added: proper Lacrosse V3 WS7000 sensor support  
- Changed: config file and plugin integration  
- Changed: timeout and divider value  
- Changed: Lacrosse V2 WS2300/WS3600 plugin number to get faster processing, changed various other parts as well  
- Changed: Lacrosse V1 pulse duration checks  
- Changed: various parts to improve speed  
- Changed: Flamingo Smoke detector signal re-transmits from 8 to 10 times  
- Added: Additional tests on Alecto V1 and Alecto V4 to filter out false positives  
- Fixed: AC (NewKaku) protocol send for some device numbers  
- Fixed: little bug in UPM code  
- Fixed: Oregon wind speed reporting  
- Fixed: Wind speed calculations  
- Fixed: Wind direction reporting in all plugins  
- Fixed: AlectoV3 humidity value displaying out of range values  
- Fixed: OregonV1 decoding  
    
R25:  
- Fixed: Eurodomest address range check  
- Fixed: Alecto V1 and V3 humidity handling  
- Fixed: Lacrosse WS2300/WS3600 and labelled as LacrosseV2  
  
R24:  
- Fixed: Flamingo Smoke Detector timings and device address usage  
- Fixed: Timing for Nexa/Jula Anslut  

R23:  
- Changed: Alecto V1 temperature data filtering  
- Added: Alecto V1 battery status now shown for temperature sensors  

R22:  
- Various additional tests and fixes after intensive tests  
- Added: Home Confort send and recognition by Domoticz  
  
R21:   
- Re-Activated PIR & Door/Window sensors (plugin 60/61)  
  
R20:  
- Switched to Arduino 1.6.5  
  
R19:  
- Complete rewrite  
- Added: Home Confort Smart Home - TEL-010  
- Added: RGB LED Controller  
- Added: RL-02 Digital Doorbell  
- Added: Deltronic Doorbell  
- Added: Sartano 2606 remote & switch  
  
r18:
- Added Banggood SKU174397, Sako CH113, Homemart/Onemall FD030 and Blokker (Dake) 1730796 outdoor temperature sensor  
- Tested Okay: Promax RSL366T, Profile PR-44N & PR-47N  
- Fixed: LaCrosse humidity values are correctly displayed  
- Fixed: Humidity values that originate from slave Nodos are correctly displayed  
- Fixed: UPM/Esic insane temperature values are skipped  
- Removed Xiron & Auriol debug data  
- Tightened pulse range on various protocols to prevent false positives  

r17:  
- Modified Oregon THGR228N code  
- Modified Newkaku(AC) dim values  
- Corrected support for KAKU door switches  
- Fixed Nodo Slave sensors  
- Improved speed and priorities so that group commands are properly transmitting  

r16:  
- Fixed Aleco V1 temperature ID to match wind sensors  
- Fixed HomeEasy transmit  
- Added AC(NewKaku) dimmer support  

r15:  
- Improved large packet translation  

r14:  
- Changed Motion sensors (60/61)  

r13:  
- Flamingo Smoke detector fix  
- Added Xiron sensor support  

r11/12:  
- Mertik / Dru Send added  

r10:  
- Added Auriol Z32171A  

r9:  
- Fixed Kaku send with high device id's (P1 M1 etc)  

r8:  
- Improved descriptions  

r7:  
- Fixed Oregon RTGR328N ID and humidity format  
- Fixed UPM/Esic humidity format  
- Fixed Alecto humidity format  

r6:  
- Fixed Auriol V2 plugin  
- Updated Auriol plugin  
- Fixed Lacrosse Humidity  

r1/2/3/4/5:  
- Added X10 receive/transmit plugin  
- Minor changes & improvements  
   
Special thanks to everyone who contributed with feedback, suggestions, debug data, tests, code snippets and more.   
