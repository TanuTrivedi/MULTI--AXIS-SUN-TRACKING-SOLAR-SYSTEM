# MULTI--AXIS-SUN-TRACKING-SOLAR-SYSTEM
# ☀️ Multi-Axis Sun Tracking Solar System

A smart solar panel system that automatically adjusts its position along multiple axes to follow the sun and maximize solar energy absorption throughout the day. This system uses IoT and sensor-based automation for improved efficiency over static solar panels.

---

##  Project Overview

Traditional fixed-angle solar panels lose potential energy because they don’t follow the sun.  
**This Multi-Axis Sun Tracking Solar System** uses real-time light sensor data and microcontroller logic to rotate solar panels in both horizontal and vertical directions — increasing power generation by up to 40%.

##  Key Components

- **ESP32 / Arduino UNO** (Microcontroller)  
- **LDR Sensors** – to detect sunlight intensity  
- **Servo Motors** – to adjust panel orientation  
- **Solar Panel** – to generate electricity  
- **Battery – to store generated energy  
- **IoT Dashboard  – for remote monitoring of panel angles and voltage
- 
##  Technologies Used

- Embedded C / Arduino IDE  
- IoT Modules (for optional monitoring)  
- Sensors & Actuators: LDRs, Servos  
- Power Electronics  
- Cloud Platforms like Blynk or ThingSpeak for monitoring
- 
## How It Works

1. **LDR sensors** are placed in 4 directions around the panel.  
2. Microcontroller reads light intensity from each sensor.  
3. Based on sensor data, servo motors rotate the panel to face the brightest light source.  
4. The system continues tracking throughout the day for maximum efficiency.  
5. Optional voltage detection system logs solar output for performance analysis.

##  Benefits

- Increases solar power generation  
- Smart energy harvesting based on real-time sunlight position  
- Eco-friendly and efficient system  
- Can be expanded with weather sensors and remote monitoring

##  Future Improvements

- Add cloud monitoring using Blynk or ThingSpeak  
- Implement weather prediction-based positioning  
- Solar energy storage management using battery level tracking  
- Integration with a mobile app for manual override


