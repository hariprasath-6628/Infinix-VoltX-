VoltX is an IoT-based smart charging solution designed to improve smartphone battery lifespan and reduce energy wastage. The system continuously monitors the battery percentage of a smartphone through a mobile application and automatically controls the charging process using an ESP32 microcontroller and relay module.
When the battery reaches a predefined charge level, the system disconnects power to prevent overcharging and unnecessary energy consumption. �
IoT-Based-Smart-Charging-Cutoff-and-Battery
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
Alerts users through LEDs, buzzer, and OLED display.
