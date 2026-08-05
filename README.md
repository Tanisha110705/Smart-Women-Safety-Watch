# Smart Women Safety Watch 🏆

## 🥇 1st Prize Winner — Hackathon Project

A safety watch based on ESP32 microcontroller, which detects emergencies through multi-sensor monitoring and sends alerts to emergency contacts.

## Overview

Smart Women Safety Watch consists of physiological and environmental sensors to monitor user condition in real-time.

The watch makes use of:
- An ECG sensor to monitor heartbeat
- A custom-made coin-based GSR sensor to detect stress levels
- PIR sensor to detect motion
- Microphone to monitor ambient sounds

Sensor data is analyzed by the decision-making logic made in the ESP32 microcontroller to classify the user condition as SAFE, ALERT, or DANGER zones.


## Key Features

- Real-time health & environment monitoring
- Multi-sensor threats detection
- Design of custom coin-based GSR sensor
- Emergency panic button
- IoT Dashboard for live monitoring
- Emergency contact alerting system
- LED indication for safety levels

## Hardware Used

- ESP32
- ECG Sensor
- Custom Made Coin Based GSR Sensor
- PIR Sensor
- Microphone Module
- Push Button
- RGB LEDs

## Working
1. Sensors sense the physiological and environmental data.
2. ESP32 processes the sensor values according to threshold-based logic.
3. System classifies the condition as:
