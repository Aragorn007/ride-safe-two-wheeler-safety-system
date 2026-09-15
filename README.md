# Ride Safe - AI Based Two Wheeler Safety System

## Overview

Ride Safe is an AI-powered helmet detection system designed to improve rider safety and reduce accidents caused by non-compliance with helmet usage.

The system uses a machine learning model trained using Edge Impulse and deployed on a XIAO ESP32S3 Sense microcontroller with an integrated camera module.

## Problem Statement

A significant number of road accidents occur due to riders not wearing helmets, increasing the risk of severe head injuries.

## Proposed Solution

The camera continuously captures images of the rider.

The trained AI model determines whether a helmet is present.

If a helmet is detected, the bike ignition/key mechanism is enabled.

If no helmet is detected, the ignition remains locked.

## Technologies Used

- Edge Impulse
- Arduino IDE
- XIAO ESP32S3 Sense
- Embedded AI
- Computer Vision
- Machine Learning

## Working

1. Camera captures rider image.
2. AI model detects helmet presence.
3. Prediction is processed locally on ESP32.
4. Ignition switch is enabled/disabled accordingly.

## Hardware

- XIAO ESP32S3 Sense
- Camera Module
- Rotary Bike Switch
- Power Supply Circuit

## Future Improvements

- IR filter for night-time detection
- Improved training dataset
- Direct engine integration
- Alarm system

## Cost

| Component | Cost |
|-----------|------|
| XIAO ESP32S3 Sense | ₹1500 |
| Other Components | ₹100 |
| Total | ₹1600 |

## Social Impact

- Reduces head injuries
- Promotes safer riding culture

## Team

Team T212

## Gallery

<img width="1600" height="1200" alt="Helmet_detection_output" src="https://github.com/user-attachments/assets/775e6aa1-2c3d-4d38-8f72-de864891bb5d" />
<img width="2048" height="1447" alt="Certificate" src="https://github.com/user-attachments/assets/42377d7b-f1aa-4f27-a863-72ad358e4741" />
