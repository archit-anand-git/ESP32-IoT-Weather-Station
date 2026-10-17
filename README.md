# IoT-Based Weather Monitoring Station

An ESP32-based weather monitoring system that measures temperature
and humidity and displays the readings remotely using Blynk IoT.

## Overview

This project monitors environmental conditions using a DHT11 sensor
connected to an ESP32 microcontroller. The ESP32 collects temperature
and humidity readings and transmits the data over Wi-Fi to the Blynk
IoT platform.

The readings can be viewed through a Blynk dashboard, allowing users
to monitor environmental conditions remotely.

## Objectives

- Measure temperature and relative humidity.
- Interface a DHT11 sensor with the ESP32.
- Transmit sensor readings over Wi-Fi.
- Display real-time measurements on a Blynk dashboard.
- Gain practical experience with IoT communication and cloud-based
  monitoring.

## Hardware Components

| Component | Purpose |
| ESP32 | Microcontroller and Wi-Fi connectivity |
| DHT11 | Temperature and humidity measurement |
| Jumper Wires | Electrical connections |
| USB Cable | Power supply and programming |

## Software and Technologies

- Arduino IDE
- Embedded C/C++
- ESP32
- DHT11 Sensor
- Blynk IoT
- Wi-Fi Communication

## Working Principle

1. The DHT11 sensor measures ambient temperature and humidity.
2. The ESP32 reads the sensor measurements.
3. The ESP32 connects to a Wi-Fi network.
4. The measured values are sent to the Blynk IoT platform.
5. The Blynk dashboard displays the readings for remote monitoring.

## Features

- Real-time temperature monitoring.
- Relative humidity monitoring.
- Wi-Fi-based data transmission.
- Remote monitoring through the Blynk IoT dashboard.

## System Architecture

DHT11 Sensor to ESP32 to(through WI-FI) Blynk IoT Cloud to Mobile/Dashboard 

## Current Project Status

The project demonstrates sensor interfacing, Wi-Fi communication
and remote monitoring through Blynk IoT.

## Future Improvements

- Add additional environmental sensors.
- Store historical readings and visualize trends.
- Configure threshold-based alerts.
- Explore weather data logging and analysis.
- Improve the dashboard with additional widgets.

## Applications

- Indoor environmental monitoring.
- Basic weather observation.
- Smart-home monitoring.
- IoT learning and experimentation.

## Author

Archit Anand

Electronics and Communication Engineering Student

## Disclaimer

The DHT11 is a basic environmental sensor. Its readings are intended
for educational and experimental monitoring rather than professional
weather forecasting.
