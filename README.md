# Soil-Moisture-Sensor

![Soil moisture sensors](https://github.com/user-attachments/assets/0e114866-4ff7-47ea-9df4-eec0171d2d79)
  

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
