# Smart-Soil-Irrigation-System

A Bluetooth-controlled smart irrigation robotic system designed to optimize water usage in agriculture. The system uses soil moisture and environmental sensors to monitor field conditions and activates irrigation only when necessary.


Project Overview:

This mini project was developed as part of the Microprocessor and Microcontroller (MPMC) curriculum. The goal is to build an automated, flexible, and mobile irrigation system to reduce water wastage and improve crop productivity.
The system consists of a robotic chassis embedded with various sensors including a soil moisture sensor and a DHT11 temperature and humidity sensor. A Bluetooth module allows manual control of the system using a smartphone. The robot can autonomously detect when the soil needs water and operate the pump accordingly. The pump only activates when the soil moisture level falls below a predefined threshold (50%), thus preventing overwatering and conserving water.
Additionally, the system includes a water pump, L298N motor driver, and multiple LEDs and a horn for operational feedback. It enables both autonomous and manual irrigation and can navigate through fields using its motorized wheels.


Features:

Automated Irrigation using soil moisture data.
Real-time Temperature and Humidity Monitoring using DHT11 sensor.
Manual control using a Bluetooth-enabled smartphone via HC-06 module.
Mobility enabled by a robotic chassis powered by an L298N motor driver.
Water pump control for targeted irrigation.
Visual and audio indicators through front/rear LEDs and a buzzer.
Efficient water management by irrigating only when soil moisture is low.


Hardware Components:

Arduino UNO – acts as the central controller.
Soil Moisture Sensor – measures the moisture level in the soil.
DHT11 Temperature & Humidity Sensor – provides environmental data.
HC-06 Bluetooth Module – enables wireless control via mobile phone.
L298N Motor Driver – controls the movement of the chassis motors.
Water Pump – irrigates the soil when needed.
Mobile Robotic Chassis – allows movement across the field.
LEDs – used for indicating direction and system status.
Buzzer – provides auditory feedback.
Jumper Wires, Breadboard, and Power Supply for setup and connection.


Working Principle:

The robot continuously reads data from the soil moisture sensor and the DHT11 temperature and humidity sensor. Based on the moisture level detected, the Arduino UNO decides whether the soil requires irrigation.
If the moisture content falls below 50%, the pump is activated to water the soil. If the moisture content is above the threshold, the pump remains off to avoid overwatering. This simple condition ensures precise irrigation.
The robotic platform can be manually directed using a smartphone via Bluetooth, allowing the user to position it appropriately. Manual override is particularly useful in scenarios where specific regions need inspection or special watering.
Additionally, front and back LEDs, a parking LED, and a horn (buzzer) are integrated to enhance navigation visibility and safety.


Future Scope:

The system can be expanded in the following ways:
GPS Integration: Add GPS modules to allow autonomous navigation and field mapping.
Solar Power: Implement solar panels to power the system sustainably.
IoT Dashboard: Create a cloud-connected dashboard to view real-time soil and environmental data.
Predictive Analytics: Use machine learning models to predict irrigation needs based on past weather and soil data.
Sprinkler Integration: Equip the system with a sprinkler setup for wider area coverage.
Advanced Sensor Network: Include additional sensors like pH, rainfall, and sunlight sensors for broader data collection.

