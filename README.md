Smart Plant Monitoring System using ESP8266
Project Overview
This project involves creating a Smart Plant Monitoring System using an ESP8266 microcontroller and various sensors, including a FC-28 Soil Moisture Sensor, DHT11 Humidity Sensor, PIR Motion Sensor, and a DC Water Pump controlled via a Relay Module. The system is designed to monitor and maintain optimal plant conditions automatically, with real-time data available through the Blynk IoT app.

Key Features:
Automated irrigation system based on soil moisture levels.
Real-time monitoring of temperature, humidity, and soil moisture.
Motion detection for added security.
Manual on/off button for controlling the water pump.
Integration with Blynk IoT for remote monitoring and control.
Components Used
ESP8266 Microcontroller
FC-28 Soil Moisture Sensor
DHT11 Humidity Sensor
PIR Motion Sensor
16x2 I2C LCD Display
DC Water Pump
Relay Module (5V)
Manual On/Off Button
5-7V Battery for Power Supply
Blynk IoT Application for mobile-based monitoring
Circuit Diagram
The system integrates the following components connected to the ESP8266:

Soil Moisture Sensor: Connected to analog pin A0.
DHT11 Sensor: Connected to digital pin D2.
PIR Motion Sensor: Connected to digital pin D3.
16x2 LCD Display (I2C): Connected to SDA and SCL pins.
DC Water Pump: Controlled via a Relay Module connected to D8.
Manual On/Off Button: Connected to D5 pin for controlling the water pump.
Power Supply: 5V-7V battery to power the system.
Working Principle
Sensors: The system continuously monitors:

Soil Moisture: To determine if the plant needs water.
Temperature and Humidity: Using the DHT11 sensor.
Motion: Using the PIR sensor for security purposes.
Watering: When the soil moisture falls below a set threshold, the DC water pump is triggered via the Relay Module to water the plant.

Manual Control: A manual on/off button can override the system and control the pump directly.

Blynk IoT: The system sends real-time data to the Blynk App for remote monitoring and control. Users can monitor soil moisture levels, temperature, and humidity, and view the water pump's status.

Blynk IoT Integration
The system is connected to the Blynk App, where users can:
Monitor real-time sensor data (soil moisture, temperature, humidity).
Control the water pump remotely.
View motion detection status.
Download the Blynk App from the Google Play Store or the Apple App Store.
Circuit Diagram

Software
Libraries Used:
Blynk: For remote monitoring and control via the app.
DHT: For reading data from the DHT11 sensor.
LiquidCrystal_I2C: For controlling the LCD display via I2C.

Future Improvements
Solar Power Integration: To make the system more eco-friendly and energy-efficient.
Advanced Sensors: Add sensors for pH and nutrient levels for more comprehensive monitoring.
AI-Based Automation: Implement predictive models to optimize watering schedules.
Security Features: Add a camera module to capture images in case of motion detection.

Applications
Small-Scale Agriculture: Helps in maintaining optimal plant growth conditions.
Home Gardening: Ideal for indoor and outdoor plant care.
Greenhouses: Automates irrigation and climate control for better yield.