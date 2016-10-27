# homebridge-openweathermap-temperature

Supports Openweathermap-API as temperature-device.
This version only supports temperature, nothing else.

# Installation

1. Install homebridge using: npm install -g homebridge
2. Install this plugin using: npm install -g homebridge-openweathermap-temperature

# Configuration


Configuration sample:

 ```
 "accessories": [
     {
         "accessory": "OpenweathermapTemperature",
         "name": "Outside Temperature",
         "url": "http://api.openweathermap.org/data/2.5/weather?q=Karlsruhe,DE&APPID=APITOKEN"
     }
 ]

```

This plugin acts as an interface between openweathermap and homebridge only. You will need an account on homebridge.
