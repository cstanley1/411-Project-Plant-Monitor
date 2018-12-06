# Software
In order to put software on our ATMEGA32U4 Microprocessor we first had to put a bootloader on the chip. By attatching the ATMEGA Chip to the serial output on our PCB we can put the bootloader on the chp and then upload the code directly through USB. Some helpful recorces for uploading the dootloader and code can be found here:

Guide For Uploading Bootloader and Code:
https://murchlabs.com/monday-experiment-bootloading-an-atmega32u4-with-arduino/ 

Pin Out guide from Arduino to ATMEGA 32U4 Chip:
https://www.arduino.cc/en/Hacking/PinMapping32u4

When uploading the bootloader you will first need to upload your programming arduino (if that is the programming method you choose) with ArduinoISP code. I had to make some small adjustments in order for this to work properly which is why I uploaded it for use here. The final code is titled " WaterMeWSensor.ino" in order to properly upload this you will need to use the LED Library.

Guide for soil moisture sensor:
https://learn.sparkfun.com/tutorials/soil-moisture-sensor-hookup-guide?_ga=2.78448276.1086735899.1544122994-513410383.1538784345

Guide for LED Display:
https://learn.adafruit.com/character-lcds/wiring-a-character-lcd 
