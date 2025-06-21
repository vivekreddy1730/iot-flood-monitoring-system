This repository contains the complete design, source code, and documentation for an IoT-based Smart Flood Monitoring and Early Warning System, developed to offer a reliable and scalable solution for disaster risk reduction in flood-prone regions. The system is built using an ESP32 microcontroller, which serves as the central node for collecting environmental data from a variety of sensors:

Water Level Sensor (analog float)

Water Flow Sensor (YF-S201)

Capacitive Rain Sensor

Temperature and Humidity Sensor (DHT11)

These sensors provide continuous monitoring of key hydrological parameters. Sensor data is processed locally on the ESP32 and pushed to cloud platforms such as ThingSpeak (for data logging and analysis) and Blynk (for real-time mobile visualization through an IoT dashboard).

For emergency scenarios, when flood risk thresholds are breached (e.g., water level, rainfall intensity, and flow rate), the system triggers multi-channel alerts, including:

Local LED and buzzer alerts

Push notifications via the Blynk mobile app

SMS notifications via the Twilio API to registered phone numbers, including authorities

The solution is cost-effective (under $30 USD per unit), energy-efficient, and designed for off-grid deployment, with the possibility of integrating solar power and battery backup for rural areas.

It is particularly aligned with the United Nations Sustainable Development Goals (SDGs):

SDG 11: Sustainable Cities and Communities — by providing tools for climate-resilient infrastructure

SDG 13: Climate Action — by promoting preparedness through real-time environmental monitoring

The modular architecture allows for easy scaling and customization. The repository includes:

Full firmware (main_code.ino)

Configuration templates for Blynk and Twilio

Schematics and circuit design

Simulation/test results and documentation

This project is ideal for students, researchers, and developers interested in embedded systems, IoT, disaster management, and smart city infrastructure.

