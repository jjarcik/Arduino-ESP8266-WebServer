# Arduino-ESP8266 WebServer

## You need
- ESP8266 - ESP-01
- Arduino Uno
- 3.3V regulator (I used to AMS1117)


## Wiring ESP8266 + Arduino

| ESP8266 | Arduino | 
| ------- |:-------:|
| RX | 3 |
| TX | 2 |

| ESP8266 | AMS1117 | 
| ------- |:-------:|
| VCC | out |
| CH_PD | out |
| GND | GND |


| AMS1117 | Arduino | 
| ------- |:-------:|
| in | Vin |
| GND | GND |

## In photos

<img src="https://raw.githubusercontent.com/jjarcik/Arduino-ESP8266-WebServer/master/IMG_20161227_211430.jpg" width="450">
<img src="https://raw.githubusercontent.com/jjarcik/Arduino-ESP8266-WebServer/master/IMG_20161227_211438.jpg" width="450">

AMS1117

<img src="https://raw.githubusercontent.com/jjarcik/Arduino-ESP8266-WebServer/master/SKU246891a.jpg" width="450"/>
