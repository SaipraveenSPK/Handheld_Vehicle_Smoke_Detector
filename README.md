# Handheld Vehicle Smoke Detection System

A portable IoT device for real-time detection and alerting of excessive vehicle exhaust smoke levels.

## Features

- **MQ-135 Sensor & Arduino Nano**  
  Continuously monitors and quantifies smoke emissions in parts per million (PPM).  
- **Threshold-Based Alerts**  
  MCU logic distinguishes normal vs. hazardous smoke levels and triggers alerts accordingly.  
- **Live Display**  
  Serial I2C LCD (PCF8574) shows real-time PPM readings and color-coded LED indicators (green/yellow/red).  
- **Remote Notifications**  
  Piezo buzzer for local alerts and wireless module (HC-05/ESP8266) for instant notifications to a central server.

## Tech Stack

- **Microcontroller**: Arduino Nano (ATmega328)  
- **Sensors & Actuators**: MQ-135 Gas Sensor, I2C LCD, LEDs, Piezo Buzzer  
- **Programming**: C++ (Arduino IDE)  
- **Simulation & Prototyping**: Tinkercad  
- **Communication**: HC-05 or ESP8266 Wireless Module  

---

> Developed as part of an IoT project to ensure cleaner air and safer environments by providing real-time vehicle smoke monitoring and alerts.  
> Developed by Sai Praveen, Barani, MohanRaj
