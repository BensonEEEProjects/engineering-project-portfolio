Project 1: Water Level and Flow Monitoring System Using Automotive Fuel Sensor
1. Project Overview

This project involved the design and implementation of a mini water tank monitoring system that measures water level and flow rate in real time. An automotive fuel level sensor was repurposed as a water level sensor, while flow sensors were used to monitor inlet and outlet water flow. The system provides visual and audio alerts based on predefined water level conditions and abnormal flow rates.

2. Problem Statement

In small-scale water storage systems, low water levels and abnormal inflow or outflow rates often go unnoticed, leading to pump damage, water wastage, or system inefficiency. There is a need for a simple, low-cost monitoring and alert system to improve reliability and safety.

3. Project Objectives

To measure water level in a mini tank using a repurposed automotive fuel sensor

To monitor water inflow and outflow using flow sensors

To provide clear visual and audio alerts based on tank conditions

To display real-time data via serial communication and MATLAB visualization

4. System Description and Operation

The system continuously reads data from the water level sensor and the inlet and outlet flow sensors. Based on calibrated thresholds, the system responds as follows:

Low water level or abnormal flow rate: Red LED turns ON and buzzer is activated

Half-filled tank: Yellow LED turns ON, buzzer OFF

Fully filled tank: Green LED turns ON, buzzer OFF

All sensor readings and system states are displayed on the serial monitor and monitored using MATLAB for analysis and visualization.

5. My Role and Responsibilities

Connected and tested LED and buzzer circuits

Calibrated the automotive fuel sensor for accurate water level measurement

Calibrated and validated inlet and outlet flow sensors

Implemented serial monitor outputs for water level and flow readings

Tested and verified threshold-based logic for LED and buzzer activation

6. Tools and Technologies Used

Arduino microcontroller

Automotive fuel level sensor

Water flow sensors

LEDs (Red, Yellow, Green)

Buzzer

MATLAB

Serial Monitor

7. Results and Performance

The system successfully detected water level changes and abnormal flow conditions. Visual indicators and audio alerts responded accurately according to predefined thresholds. Serial and MATLAB monitoring confirmed stable and consistent sensor readings after calibration.

8. Key Learnings and Skills Gained

Practical sensor calibration techniques

Repurposing automotive sensors for alternative applications

Threshold-based control system design

Hardware and software integration

Real-time data monitoring and visualization

9. Future Improvements

Integration with a PLC-based control system

Wireless monitoring using IoT platforms

Data logging for long-term analysis

Mobile or web-based dashboard visualization
