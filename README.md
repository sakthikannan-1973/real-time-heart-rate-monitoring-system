# Real Time Heart Rate Monitoring System

## Project Overview
This project aims to develop a real-time heart rate monitoring prototype using an ESP32 microcontroller and a MAX30102 pulse sensor. An MPU6050 accelerometer and gyroscope can be used to monitor movement, while a 16×2 I2C LCD displays system information.

## Components Required
- ESP32 development board
- MAX30102 pulse sensor
- MPU6050 accelerometer and gyroscope
- 16×2 LCD with I2C interface
- Breadboard and jumper wires

## Features
- Heart rate sensing using the MAX30102
- Motion monitoring using the MPU6050
- LCD-based information display
- ESP32-based sensor integration
- Potential for Wi-Fi connectivity and cloud data logging

## Hardware Connections
The I2C devices share the ESP32 SDA and SCL lines:
- SDA: GPIO 21
- SCL: GPIO 22
- MAX30102 I2C address: `0x57`
- MPU6050 I2C address: `0x68`
- LCD I2C address: `0x27`

## Project Status
Hardware detection has been tested. Heart rate calculation, complete sensor integration, and cloud logging should be marked complete only after they have been verified.

## Disclaimer
This is an educational prototype and is not intended for medical diagnosis.
