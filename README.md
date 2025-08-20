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
## Features
- Monitors soil moisture levels in real-time
- Prevents overwatering and underwatering  
- Low-cost and easy to assemble  
- Scalable for home gardening or small farms
- - LED indicators:
- 🟢 **Green LED** → Soil is well hydrated  
- 🟠 **Orange LED** → Soil is moderately dry  
- 🔴 **Red LED** → Soil is too dry, watering needed  


---


## 🛠️ Components Used
- Soil Moisture Sensor  
- Arduino / ESP32 / Raspberry Pi (depending on setup)  
- Jumper wires  
- Breadboard or PCB  
- Power source  

---
## Components Used for Arduino

| Component                                | Qty | What it’s for                                                        |
| ---------------------------------------- | --- | -------------------------------------------------------------------- |
| LCD 16x2 (I2C, PCF8574-based, addr 0x20) | 1   | Displays soil moisture, temperature, and light readings              |
| Arduino Uno R3                           | 1   | Main microcontroller that processes sensor data and controls outputs |
| Green LED                                | 1   | Indicates soil is sufficiently wet                                   |
| Orange LED                               | 1   | Indicates soil is moderately dry                                     |
| Red LED                                  | 1   | Indicates soil is very dry and needs watering                        |
| 1 kΩ Resistors (R1, R2, R3, R5)          | 4   | Limit current to protect LEDs and sensors                            |
| Photoresistor (LDR)                      | 1   | Measures light intensity in the environment                          |
| Soil Moisture Sensor                     | 1   | Detects the soil’s moisture level                                    |
| TMP36 Temperature Sensor                 | 1   | Measures soil/ambient temperature                                    |

---

## Circuit Wiring Diagram
<img width="1297" height="704" alt="Screenshot 2025-08-20 081548" src="https://github.com/user-attachments/assets/0c38310e-83e5-4c7a-a62b-4612773cc7ee" />

---
