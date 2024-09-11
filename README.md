# 🌱 Plant and Weather Monitoring System 🌦️

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
The ESP32 processes data from the soil moisture sensors, DHT sensor, and rain sensor. When the soil moisture is below a set threshold and no rain is detected, the water pump is activated to irrigate the plants. The system continuously displays sensor data on an LCD for easy monitoring.

## Installation
Clone the repository:

