# Soil-Moisture-Sensor

![Project Image](images/your-image.png)  

## Introduction  

This project utilizes the ESP8266 with the RemoteXY library to create a remote control interface for monitoring soil moisture levels. It can be used to trigger alerts based on the moisture sensor readings.  

## Requirements  

- ESP8266  
- ESP8266WiFi library  
- RemoteXY library  

## Setup  

1. Install the required libraries via the Arduino IDE.  
2. Modify the WiFi settings in the code:  
   ```cpp  
   #define REMOTEXY_WIFI_SSID "sensor"  
   #define REMOTEXY_WIFI_PASSWORD "12345678"
