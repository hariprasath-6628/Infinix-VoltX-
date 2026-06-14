Project Title
VoltX – IoT-Based Smart Charging Cutoff & Battery Health Optimization System �

Overview
VoltX is an IoT-based smart charging solution designed to improve smartphone battery lifespan and reduce energy wastage. The system continuously monitors the battery percentage of a smartphone through a mobile application and automatically controls the charging process using an ESP32 microcontroller and relay module.
When the battery reaches a predefined charge level, the system disconnects power to prevent overcharging and unnecessary energy consumption. �

Problem Statement
Many users leave their smartphones charging overnight, which leads to:
Battery degradation due to prolonged 100% charging.
Heat generation that accelerates battery wear.
Energy wastage caused by standby power consumption.
Dependence on manual monitoring of charging status. �

Proposed Solution
VoltX provides an automated charging control system that:
Monitors smartphone battery percentage in real time.
Sends battery data from the mobile application to the ESP32 via Wi-Fi.
Controls a relay module to enable or disable charging.
Stops charging when the battery reaches the target level.
Alerts users through LEDs, buzzer, and OLED display. �

Working Principle
User connects the smartphone charger to VoltX.
Mobile app reads the current battery percentage.
Battery information is transmitted to the ESP32 over Wi-Fi.
ESP32 compares the battery level with the predefined threshold.
If the threshold is reached, ESP32 deactivates the relay.
Power supply to the charger is disconnected automatically.
OLED display and indicators show the charging status. �

Features
Real-time battery monitoring.
Automatic charging cutoff.
Improved battery health.
Reduced power consumption.
Wi-Fi-based communication.
OLED status display.
Audio and visual notifications.
User-friendly mobile application. �

Advantages
Extends smartphone battery lifespan.
Prevents overcharging.
Saves electricity.
Reduces heat generation.
Requires minimal user intervention.
Low-cost and scalable solution. �

Applications
Smartphones
Tablets
Power banks
Smart home charging stations
IoT energy management systems �

Future Enhancements
AI-based charging prediction.
Multi-device charging support.
Cloud data analytics.
Battery health reporting dashboard.
Smart scheduling and charging optimization. �

Conclusion
VoltX is an innovative IoT-based charging management system that automatically controls smartphone charging to improve battery health and reduce energy consumption. By combining ESP32, relay control, and a mobile application, the system provides a smart, efficient, and user-friendly solution for modern battery management. �

Team: INFINIX
