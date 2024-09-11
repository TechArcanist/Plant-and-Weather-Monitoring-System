<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plant and Weather Monitoring System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
            color: #333;
        }
        h1 {
            font-size: 3em;
            text-align: center;
            color: #4CAF50;
            animation: slidein 3s infinite alternate;
        }
        h2 {
            color: #4CAF50;
        }
        @keyframes slidein {
            from {
                transform: translateX(0);
            }
            to {
                transform: translateX(20px);
            }
        }
        .section {
            margin: 20px 0;
        }
        .features, .components, .usage {
            padding: 10px;
            border-left: 4px solid #4CAF50;
            background-color: #e8f5e9;
        }
        code {
            background-color: #eee;
            padding: 5px;
            border-radius: 5px;
            font-size: 1.1em;
        }
        .install-btn {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.2em;
            display: inline-block;
            margin-top: 20px;
        }
        .install-btn:hover {
            background-color: #45a049;
        }
        .diagram {
            text-align: center;
            margin-top: 30px;
        }
        .diagram img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

    <h1>🌱 Plant and Weather Monitoring System 🌦️</h1>

    <section class="section">
        <h2>Features</h2>
        <div class="features">
            <ul>
                <li><strong>Capacitive and Resistive Soil Moisture Sensors:</strong> Monitor soil moisture levels for efficient watering.</li>
                <li><strong>DHT Sensor:</strong> Tracks temperature and humidity around plants.</li>
                <li><strong>Rain Sensor:</strong> Detects rainfall to prevent overwatering.</li>
                <li><strong>LCD Display:</strong> Provides real-time data visualization.</li>
                <li><strong>Automated Watering:</strong> Waters plants based on sensor readings.</li>
            </ul>
        </div>
    </section>

    <section class="section">
        <h2>Components Used</h2>
        <div class="components">
            <ul>
                <li>ESP32 (Microcontroller)</li>
                <li>Capacitive and Resistive Soil Moisture Sensors</li>
                <li>DHT11/DHT22 Sensor (Temperature and Humidity)</li>
                <li>Rain Sensor</li>
                <li>LCD Display</li>
                <li>Water Pump</li>
                <li>Relay Module</li>
                <li>Jumper Wires</li>
                <li>Power Supply</li>
            </ul>
        </div>
    </section>

    <section class="section">
        <h2>How It Works</h2>
        <div>
            <p>
                The ESP32 processes data from the soil moisture sensors, DHT sensor, and rain sensor. When the soil moisture is below a set threshold and no rain is detected, the water pump is activated to irrigate the plants. The system continuously displays sensor data on an LCD for easy monitoring.
            </p>
        </div>
    </section>

    <section class="section">
        <h2>Installation</h2>
        <p>Clone the repository:</p>
        <code>git clone https://github.com/yourusername/plant-weather-monitoring-system.git</code>

        <p>Connect the components as per the <a href="#diagram">circuit diagram</a> and upload the code to your ESP32 using the Arduino IDE or PlatformIO.</p>
        <button class="install-btn">Clone Repository</button>
    </section>

    <section class="section">
        <h2>Usage</h2>
        <div class="usage">
            <ul>
                <li>Set up the ESP32 with your preferred IDE.</li>
                <li>Connect all sensors (soil moisture, DHT, rain, LCD) and peripherals like the water pump.</li>
                <li>Adjust the soil moisture threshold in the code to suit the plant type.</li>
                <li>Power on the system, and it will automatically monitor and water the plants based on real-time sensor data, displayed on the LCD.</li>
            </ul>
        </div>
    </section>

    <section id="diagram" class="diagram">
        <h2>Circuit Diagram</h2>
        <img src="circuit-diagram.png" alt="Circuit Diagram">
    </section>

    <footer>
        <p>Developed by <strong>Your Name</strong>. Feel free to contribute!</p>
    </footer>

</body>
</html>
