Android UsbSerialArduino1
=========================

Android app which control the LED and button on Arduino.

## Feature
This app send the command and recieve the message using USB serial.<br>
And display analog values on graph. <br>

Command : Android -> Arduino<br>
"L0" : trun off LED<br>
"L1" : trun on LED<br>
"Pxxx" : control the brightness of LED<br>
　xxx ; three digits 000 - 255<br>

Message : Android <- Arduino<br>
"B0" : buton is off<br>
"B1" : buton is pushed<br>
"Axxxx" : analog value<br>
　xxxx ; one to three digits 0 - 1023<br>

This app is used with Arduino skech.<br>
Arduino_SerialControl1<br>
https://github.com/ohwada/Arduino_SerialControl1

## blog (in Japanese)
http://android.ohwada.jp/archives/5117

## Screenshot
![screenshot](https://raw.githubusercontent.com/ohwada/Android_UsbSerialArduino1/master/usb_serial_arduino.png)
