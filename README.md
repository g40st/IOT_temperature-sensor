# IOT_temperature sensor

This is a small IOT project. We use an ESP8266 microcontroller and a SHT-21 temperature sensor. The ESP8266 have to be conntected to a wlan network. Every ESP8266 has a webserver installed. You can access the temperatur over this webserver. Only type the ip-address in your favorite webbrowser. The ESP8266 automatically saves the temperatur every hour. 

![iot](https://user-images.githubusercontent.com/7523395/34325414-3c8cf33a-e891-11e7-9ebe-704ee01d4611.gif)

![breadboard](https://user-images.githubusercontent.com/7523395/34325420-64f3a724-e891-11e7-927f-6de80581c57d.jpg)

## short overview:

![projektimple2](https://user-images.githubusercontent.com/7523395/34325423-6deb6f1a-e891-11e7-921c-029fe44807e9.png)

## Dependencies

### ESP8266
* [Arduino core for ESP8266 WiFi chip](https://github.com/esp8266/Arduino)
* [temperature and humidity sensor SHT21](https://github.com/markbeee/SHT21)
* [Websocket Server](https://github.com/morrissinger/ESP8266-Websocket)
* [WiFiManager](https://github.com/tzapu/WiFiManager)

### JavaScript
* [Bootstrap](http://getbootstrap.com/)
* [jQuery](https://jquery.com/)
* [Chart.js](https://github.com/chartjs/Chart.js)

## Installing / Getting started

Flash the .ino file to an ESP8266. Connect the SHT-21 temperatur sensor to the ESP8266. At the first startup the ESP8266 uses the [WiFiManager](https://github.com/tzapu/WiFiManager). Look in this repository under "How It Works". 

## Author
Christian Högerle and Thomas Buck

## Licensing
The code in this project is licensed under MIT license.
