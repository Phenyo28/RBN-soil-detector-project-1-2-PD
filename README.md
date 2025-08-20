# RBN-soil-detector-project-1-2-PD

This project is a Soil Moisture Detection System. It measures soil moisture levels and provides feedback using an LCD display and 3 LEDs.  
The device helps prevent overwatering or underwatering, making it suitable for home gardening or agriculture

---

## Repository Contents
| File / Folder                 | Description                                       |
| ----------------------------- | ------------------------------------------------- |
| `Assembly 1.zip`              | Complete 3D assembly files                        |
| `Assembly STL.zip`            | STL files for 3D printing the case/enclosure      |
| `Bill of material`            | List of all required electronic components        |
| `Soil Detector Schematic.pdf` | Circuit wiring diagram in PDF format              |
| `Soil Detector.png`           | Circuit schematic (image version)                 |
| `soil_detector1.ino`          | Arduino source code for running the soil detector |

---

## Components Used
- Soil Moisture Sensor  
- Arduino IDE 
- Jumper wires  
- Breadboard or PCB  
- Power source
---
## Features
- Monitors soil moisture levels in real-time
- Prevents overwatering and underwatering  
- Low-cost and easy to assemble  
- Scalable for home gardening or small farms
- LED indicators:
- 🟢 **Green LED** → Soil is well hydrated  
- 🟠 **Orange LED** → Soil is moderately dry  
- 🔴 **Red LED** → Soil is too dry 

---

---

## Setup and Installation
1. Wire sensors, LCD, and LEDs as shown in the schematic.
   Use resistors for LEDs and connect the LCD via I2C.
2. Install the LiquidCrystal_I2C library.
   Select Arduino Uno board and correct COM port.
4. Open soil_detector1.ino and upload it to the Arduino.
5. View readings on the Serial Monitor (9600 baud) or LCD.
   LED indicators: 🟢 hydrated 🟠 moderately dry 🔴 too dry.

---

## Circuit Wiring Diagram

<img width="1117" height="579" alt="Screenshot 2025-08-20 085340" src="https://github.com/user-attachments/assets/8419c3e5-52b8-4fbe-89eb-45b7c49eabe9" />

---

## Hardware components

| Component | Description |
|--------------------------------|-----------------------------------------------------------------------------|
| Soil Moisture Sensor Probes | Detects the moisture level in the soil by measuring conductivity. |
| 16x2 LCD Display (I2C) | Displays real-time readings such as soil moisture percentage. |
| LED Indicators (Green/Orange/Red) | Visual feedback: Green = Good, Orange = Moderate, Red = Low moisture. |
| Push Button / Power Switch | Turns the device ON/OFF or resets readings. |
| Battery Pack / Power Supply | Provides portable power to the system. |
| Casing/Enclosure | Protects the electronics and provides a compact handheld design. |
---
## Soil moisture detector
<img width="420" height="522" alt="Screenshot 2025-08-20 090954" src="https://github.com/user-attachments/assets/a3591f1e-447a-4426-9a99-0de228a09199" />


---
