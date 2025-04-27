# Soil-Moisture-Sensor

A simple IoT project to monitor plant soil moisture using a soil moisture sensor, NodeMCU ESP8266 board, and the RemotXY mobile application.

<p align="center">
  <img src="images/Soil Moisture Sensor.png" alt="Project Main Image" width="500"/>
</p>

## Project Description:
- Monitor the soil's moisture status (wet or dry) in real-time.
- Send an audio notification to the smartphone via the RemotXY app if the soil is dry.
- Potential to expand the system with an automatic water pump feature.

## Hardware Components:
- NodeMCU ESP8266 Wi-Fi Development Board
- Soil Moisture Sensor (Digital Output)
- Jumper Wires (Male-to-Male)
- Breadboard (optional)
- Smartphone with RemotXY App installed

## Wiring Diagram:

| Soil Moisture Sensor Pin | NodeMCU Pin |
|:--------------------------|:------------|
| VCC                       | 3.3V        |
| GND                       | GND         |
| OUT                       | D0          |

## How It Works:
1. The soil moisture sensor sends a digital signal based on the soil moisture level.
2. If the soil is detected as dry, the NodeMCU triggers an audio alert in the RemotXY mobile app.
3. The sensor readings update continuously without delay for real-time monitoring.

## Setup Instructions:
- Upload the provided Arduino sketch (PlantMoistureMonitor.ino) to the NodeMCU board.
- Connect to the Wi-Fi access point created by NodeMCU (sensor, password 12345678).
- Open the RemotXY app and connect to the device to monitor soil moisture.

## Project Preview:

![Wiring Diagram](images/wiring_diagram.png)

## 📹 Demo video of the project

[![Watch video](images/video_thumbnail.jpg)](https://drive.google.com/file/d/1ijkmhDAPcP4Rh8S_PL73jiuvb1Kh7tLm/view?usp=sharing)


<h2 align="center">Project Images</h2>

<table align="center">
  <tr>
    <td align="center">
      <strong>IR Flame Sensor</strong><br>
      <img src="images/IR Flame Sensor.png" width="180"><br>
      Detects flame signals for fire monitoring.
    </td>
    <td align="center">
      <strong>Soil Moisture Water Sensor</strong><br>
      <img src="images/Soil Moisture Water Sensor.png" width="180"><br>
      Measures soil moisture levels accurately.
    </td>
    <td align="center">
      <strong>The NodeMCU</strong><br>
      <img src="images/The NodeMCU.png" width="180"><br>
      Wi-Fi enabled


