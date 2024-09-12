# 🌱 Plant and Weather Monitoring System 🌦️

<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=700&height=100&duration=4000&lines=Plant+and+Weather+Monitoring+System!+🌿;&color=28a745" />
</h1>


## Features
- **Capacitive and Resistive Soil Moisture Sensors:** Monitor soil moisture levels for efficient watering.
- **DHT Sensor:** Tracks temperature and humidity around plants.
- **Rain Sensor:** Detects rainfall to prevent overwatering.
- **LCD Display:** Provides real-time data visualization.
- **Automated Watering:** Waters plants based on sensor readings.

## Components Used
- ESP32 (Microcontroller)
- Capacitive and Resistive Soil Moisture Sensors
- DHT11/DHT22 Sensor (Temperature and Humidity)
- Rain Sensor
- LCD Display
- Water Pump
- Relay Module
- Jumper Wires
- Power Supply

## How It Works

The ESP32 processes data from the soil moisture sensors, DHT sensor, and rain sensor. When the soil moisture is below a set threshold and no rain is detected, the water pump is activated to irrigate the plants. The system continuously displays sensor data on an LCD for easy monitoring. Additionally, the system can be controlled and monitored remotely using Blynk IoT.


## Installation
Clone the repository:
<div align="center">
    <a href="https://github.com/TechArcanist/Plant-and-Weather-Monitoring-System.git">
        <img src="https://img.shields.io/badge/Clone_Repository-007ACC?style=for-the-badge&logo=github&logoColor=white" />
    </a>
</div>

Connect the components as per the [circuit diagram](#circuit-diagram) and upload the code to your ESP32 using the Arduino IDE or PlatformIO.

## Usage
- Set up the ESP32 with your preferred IDE.
- Connect all sensors (soil moisture, DHT, rain, LCD) and peripherals like the water pump.
- Adjust the soil moisture threshold in the code to suit the plant type.
- Power on the system, and it will automatically monitor and water the plants based on real-time sensor data, displayed on the LCD.

## Circuit Diagram
![Circuit Diagram](circuit-diagram.png)


https://github.com/user-attachments/assets/beede9d0-3db9-44d0-98c8-99d0d8b1370f

https://github.com/user-attachments/assets/6d3a23de-8c67-4e39-ac2e-8680bff6a703

## Developed by
**Lavitra Sahu**. Feel free to contribute!

## Future Improvements

- Develop a dedicated mobile app for seamless user interaction and system management.
- Implement data logging and analysis features within the mobile app for optimizing plant care based on historical data.


---

<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Thanks+for+Visiting!+👋;&color=28a745" />
</h1>
