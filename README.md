# IoT Temperature and Gas Monitoring Using ESP32

## Project Overview
This project presents an ESP32-based temperature and gas monitoring system. It uses DHT22, MQ-2 and MQ-5 sensors to monitor environmental conditions and displays the sensor readings on an LCD.

The system compares the sensor values with predefined threshold levels and indicates the status as SAFE or DANGER.

## Objectives
- Monitor environmental temperature and humidity.
- Detect gas leakage and smoke levels.
- Display real-time sensor readings.
- Identify unsafe environmental conditions.
- Develop a low-cost monitoring system.

## Components Used
- ESP32 Development Board
- MQ-2 Gas Sensor
- MQ-5 Gas Sensor
- DHT22 Sensor
- LCD Display
- Connecting Wires
- Power Supply

## Software Requirements
- Arduino IDE
- ESP32 Board Package
- DHT Sensor Library
- LCD Library

## Key Features
- Temperature and humidity monitoring.
- Gas detection using MQ-2 and MQ-5.
- Real-time LCD display.
- Threshold-based SAFE and DANGER indication.
- Offline monitoring without internet connectivity.

## Working Principle
The MQ-2 and MQ-5 sensors detect gas levels in the surrounding environment. The DHT22 sensor measures temperature and humidity. The ESP32 processes the collected sensor readings and compares them with predefined threshold values. The readings and safety status are displayed on the LCD.

## Applications
- Industrial safety monitoring
- Laboratories
- Indoor environmental monitoring
- Gas leakage detection

## Future Enhancements
- Wi-Fi-based remote monitoring
- Mobile application integration
- Cloud data storage
- Buzzer and LED alerts
- Automatic data logging

## Project Team
- Nandhini P S
- Nithyasri N
- Ragavi R
- Raj Prabha V

## Project Domain
Electronics and Communication Engineering – Embedded Systems and IoT
