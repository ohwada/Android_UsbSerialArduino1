Android UsbSerialArduino1
=========================

Android app which control the LED and button on Arduino.

## Feature
This app send the command and recieve the message using USB serial.
And display analog values on graph. 

Command : Android -> Arduino
"L0" : trun off LED
"L1" : trun on LED
"Pxxx" : control the brightness of LED
　xxx ; three digits 000 - 255

Message : Android <- Arduino
"B0" : buton is off
"B1" : buton is pushed
"Axxxx" : analog value
　xxxx ; one to three digits 0 - 1023
