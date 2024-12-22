RFLink Loader 					Version 1.10

The RFLink Loader program runs on Windows and can program an Arduino Mega 2560 board
with the RFLink software. 
You do not need any Arduino IDE/Compiler etc.


Steps:
------
- Launch the program
- Select the file you want to program (rflink.cpp.hex)
- Select the serial port to which the Arduino is connected.
- Hit the "program" button and wait for the process to finish.


History:
--------
1.10 Fixed some bugs and added timestamp option
1.09 Added: Support for LivingColors, Ansluta, GPIO, BLE 2.4Ghz devices
1.08 Added: Support for MiLight 2.4Ghz devices
1.07 Fixed: Sometime opening the serial port fails, now will clean up and retry silently
1.06 Added: Log mode for unhandled RF Packets  
     Added: buttons to enable/disable NodoNRF support (2.4Ghz NodoNRF sensors using NRF24L01)    
     Fixed: Log length for very long packets  
1.05 Fixed: Log length  
1.04 Fixed: Serial port log option making a mess when text was selected  
     Fixed: handling in case of serial port errors  
1.03 Added: Serial port log option  
1.02 Fixed: could not use serial ports > 9  
1.01 Fixed: could not load the hex file if the path name contained a space   
     Added: test serial port availability before trying to program the Arduino  
1.00 Initial Release  


Note:
-----
In some cases anti-virus software gives a warning on the RFLink Loader file.
This warning appears to be based on the fact that the loader program uses a "console" window 
plus that it launches and external program and is compiled with a fairly new Visual Studio 2015 compiler. 
This external program is the actual program that writes the firmware to the Arduino. 
There is no virus warning when scanned with the main virus scanners.
If you downloaded the firmware and latest RFlink Loader from our sourceforge page you can be sure the file is clean!
