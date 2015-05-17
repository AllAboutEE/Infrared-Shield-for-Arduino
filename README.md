# Infared Remote Control Shield for Arduino Development Board

![Infrared remote control shield for Arduino](https://raw.github.com/AllAboutEE/Infrared-Shield-for-Arduino/master/Hardware/Arduino-Infrared-Shield-Remote-Control-Angle-View.jpg)

## Compatibility:

* The Arduino board you use needs to have the two I2C pins SCL and SDA above the AREF pin. See photos [Uno Front](http://www.arduino.cc/en/uploads/Main/ArduinoUno_R3_Front.jpg), and [Uno Back](http://www.arduino.cc/en/uploads/Main/ArduinoUno_R3_Back.jpg) for reference.

**IMPORTANT, PLEASE READ!** Although the shield is compatiable with any duino board, the software libraries we developed for it are only compatible with Arduino Uno R3, and Arduino Mega 2560 R3. The board might be comptabile with software libraries for other boards if and only if the libraries support a receiver on digital pin 4, and a transmitter on digital pin 9.

## Hardware:

### Basic Connections:

* Receives IR signal on digital pin 4
* Transmits IR signal through digital pin 9
* Reads buttons through I2C port

### Specs:

* Tested Receive Range: approx. 29.5ft (9.0m)
* Tested Transmit Range: approx. 8ft (2.5m)

## Software Library:

See the project [Arduino Infrared Shield Library](https://github.com/AllAboutEE/Arduino-Infrared-Shield-Library/) for how to program the shield. 

