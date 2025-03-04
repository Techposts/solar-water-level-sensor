# Solar-Powered Water Level Sensor for Home Assistant

## Overview
This is a **solar-powered, wireless water level sensor** designed for **Home Assistant**. It utilizes an **ESP32-C3 Supermini** and an **AJ SR04M waterproof ultrasonic sensor** to measure and transmit water levels. The system runs on a **1S Li-ion battery**, charged via an **MPPT 6V module**, making it self-sufficient and maintenance-free.  

This sensor has been **installed and tested for over 6 months**, operating reliably in real-world conditions.

## Features
- **Wireless & Solar-Powered** – No need for constant charging or wiring.
- **ESPHome-Based** – Seamless integration with **Home Assistant**.
- **Waterproof Ultrasonic Sensor** – Accurately measures water levels.
- **Battery Monitoring** – Sends battery percentage to Home Assistant.
- **Low Power Consumption** – Optimized for extended battery life.
- **3D-Printed Case** – Protects components from environmental damage.

## Components Used
1. **ESP32-C3 Supermini**
2. **AJ SR04M Waterproof Ultrasonic Sensor**
3. **MPPT 6V Solar Charging Module**
4. **1S Li-ion Battery (with BMS)**
5. **3D-Printed Enclosure** (for weatherproofing)

## Wiring Diagram - Refer to the Video
https://youtube.com/shorts/L9-_Wh9T4gA
## Installation & Setup
### **1. Flashing the ESP32-C3**
- Use **ESPHome Flasher** or the **ESPHome add-on** in Home Assistant.
- Upload the provided `water-level-sensor.yaml` configuration.

### **2. Adding to Home Assistant**
- Navigate to **Settings > Devices & Services**.
- Click **Add Integration** > **ESPHome**.
- Enter the device name (`water-level-sensor.local`).
- Water level and battery percentage will now be visible in Home Assistant.

### **3. 3D-Printed Enclosure**
A **custom 3D-printed case** protects the sensor and electronics from weather conditions. STL files will be available in this repository.

## ESPHome Configuration
The **ESPHome YAML configuration** used to flash onto the ESP32-C3 Supermini is available.

