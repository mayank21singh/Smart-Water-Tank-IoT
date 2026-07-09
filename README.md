# Smart Water Tank: Real-Time Monitoring and Remote Pump Control

**Duration:** March 2025 - April 2025  
**Course Project:** IIT Gandhinagar (Prof. Arup Lal Chakraborty)  

## 📌 Project Overview
An IoT-based smart water management system designed to monitor tank fill levels and flow rates in real-time. The system processes sensor data to compute fill percentages and estimated fill times, streaming live updates to a mobile dashboard via Wi-Fi using Blynk.

## 🎥 Video Demonstration
*(Click the image below to watch the physical hardware and dashboard in action)*

[![Smart Water Tank Demo](https://img.youtube.com/vi/EnUoBJifRrM/0.jpg)](https://www.youtube.com/watch?v=EnUoBJifRrM)

## 📂 Project Documentation
* **[Final Project Report](./docs/smart_water_tank.pdf):** Detailed documentation covering the hardware schematics, sensor calibration, data processing logic, and final outcomes.

## ⚙️ Hardware & Software Architecture
* **Microcontroller:** ESP32 (Wi-Fi enabled)
* **Sensors:** HC-SR04 Ultrasonic Sensor (distance/fill level), YF-S201 Flow Sensor (flow rate in L/min)
* **Dashboard:** Blynk IoT Mobile App
* **Data Processing:** C/C++ (Arduino IDE) - 1-second update intervals for real-time telemetry.
