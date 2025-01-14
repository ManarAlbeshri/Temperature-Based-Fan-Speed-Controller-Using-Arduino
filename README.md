# Temperature-Based Fan Speed Controller Using Arduino

## Overview
This project involves creating a temperature-based fan speed controller that automatically adjusts fan speed based on ambient temperature. It uses an Arduino, temperature sensors, and an electric fan, with a simple interface to display real-time temperature and fan status.

## Business Requirements
The system aims to improve energy efficiency, enhance user comfort, and reduce noise by adjusting fan speed according to temperature.

## System Overview
- Controller: Arduino-based system.
- Sensors: Measure ambient temperature.
- Fan: Adjusts speed based on temperature readings.
- User Interface: Displays real-time temperature and fan status.

## Functional Requirements

### 1. Temperature Monitoring
- Continuously monitor and display ambient temperature.
- Accurate readings within a predefined range (e.g., 0°C to 100°C).
- Update temperature readings every second.

### 2. Automatic Fan Speed Control
- Automatically adjust fan speed based on temperature:
  - Below 25°C: Fan stops or runs at low speed.
  - 25°C - 40°C: Fan speed increases gradually.
  - Above 40°C: Fan runs at maximum speed.

### 3. Real-Time Display
- Show current temperature and fan status.
- Clear messages like "Fan Stopped," "Low Speed," or "High Speed."
- Updates within 1 second of any change.

## Non-Functional Requirements
- Performance: Respond to temperature changes within 1-2 seconds.
- Scalability: Support additional sensors or components.
- Usability: Easy-to-read display.

## Use Case: Operating the Fan
- Actor: User
- Goal: Adjust fan speed based on temperature.
- Steps:
  1. System reads temperature.
  2. Adjusts fan speed accordingly.
  3. Fan operates at the appropriate speed.

## Conclusion
This project provides an efficient, user-friendly system for temperature-based fan speed control, with potential for future expansion.
