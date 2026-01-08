# 🌦️ WEATHER-INTELLIGENCE-FORECASTING

> **🏆 Winner: Best Product Award** > *Recognized for excellence in IoT innovation and practical utility in a recent tech competition.*

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Category](https://img.shields.io/badge/Category-IoT-blue)
![Power](https://img.shields.io/badge/Power-Solar%20%2B%20Battery-green)
![Dashboard](https://img.shields.io/badge/Dashboard-Grafana-orange)

## 📖 Overview

**Weather Intelligence Forecasting** is an advanced IoT-based mini weather station designed to monitor environmental conditions in real-time. Unlike traditional weather stations, this device is self-sustaining, operating on a hybrid power system (Solar Energy + Battery Backup).

The system collects critical weather data and visualizes it on a live **Grafana Dashboard**, making weather monitoring accessible, accurate, and visually data-driven.

## ✨ Key Features

* **Real-Time Monitoring:** continuously captures data for:
    * 🌡️ **Temperature**
    * 💧 **Humidity**
    * 🌧️ **Rain Detection**
    * 💨 **Air Quality (AQI)**
* **Eco-Friendly Power:** Fully functional using Solar Panels with a Battery Management System (BMS) for uninterrupted operation.
* **Data Visualization:** Live, interactive graphs and gauges displayed on a custom Grafana Dashboard.
* **IoT Connectivity:** Transmits sensor data wirelessly to the cloud/local server.

## 📸 Screenshots

### The Device
![Device Photo](path/to/your-device-photo.jpg)
*(Replace this line with an image of your hardware setup)*

### Grafana Dashboard
![Grafana Dashboard](path/to/grafana-screenshot.jpg)
*(Replace this line with a screenshot of your Grafana dashboard showing the gauges)*

## 🛠️ Tech Stack & Hardware

### Hardware
* **Microcontroller:** [e.g., ESP32 / ESP8266 / Arduino]
* **Sensors:**
    * Temperature & Humidity Sensor (e.g., DHT11 / DHT22 / BME280)
    * Rain Sensor Module
    * Air Quality Sensor (e.g., MQ-135)
* **Power Supply:**
    * Solar Panel (5V/12V)
    * Rechargeable Battery (Li-Ion)
    * Charging Module (e.g., TP4056)

### Software
* **Firmware:** C++ (Arduino IDE) / Python (MicroPython)
* **Database:** InfluxDB / Prometheus (for time-series data storage)
* **Visualization:** Grafana
* **Communication:** MQTT / HTTP / WiFi

## ⚙️ How It Works

1.  **Sensing:** The sensors constantly read environmental parameters.
2.  **Processing:** The microcontroller processes the raw data.
3.  **Transmission:** Data is sent via WiFi to a time-series database.
4.  **Visualization:** Grafana queries the database and updates the dashboard in real-time to show current weather conditions.
5.  **Power Management:** The solar panel charges the battery during the day, ensuring the station runs 24/7.

## 🚀 Installation & Setup

1.  **Hardware Assembly:** Connect sensors to the microcontroller as per the circuit diagram (see `circuit_diagram.png`).
2.  **Library Installation:** Install required libraries (e.g., `DHT.h`, `WiFi.h`) in your IDE.
3.  **Configuration:**
    * Update WiFi credentials in the code.
    * Set up your InfluxDB/Database URL.
4.  **Grafana Setup:**
    * Connect Grafana to your data source.
    * Import the dashboard JSON file (provided in `dashboard/` folder).
5.  **Deploy:** Upload the code and expose the device to sunlight!

## 🏆 Achievements

* **Best Product Award:** This project was judged as the best product in [Name of Competition], recognized for its sustainable design and accurate data integration.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](issues/).

## 📜 License

This project is licensed under the MIT License.

---
*Created by **[BARANINATHAN S P]***
