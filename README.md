# RBN-soil-detector-project-1-2-PD

This project is a Soil Moisture Detection System. It measures the water content in soil, helping plants get the right amount of water. It prevents overwatering and underwatering, conserves water, and supports healthy plant growth. The system can be integrated with automatic irrigation setups for smart watering and is useful for agricultural efficiency, gardening, and research purposes.

---

## Repository Contents
| File / Folder                 | Description                                       |
| ----------------------------- | ------------------------------------------------- |
| `Assembly 1.zip`              | Complete 3D assembly files                        |
| `Assembly STL.zip`            | STL files for 3D printing the case                |
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

## Hardware components(for the circuit)

| Component              | Quantity | Purpose in the project                                  |
|------------------------|----------|----------------------------------------|
| Arduino Uno            | 1        | Microcontroller                        |
| Soil Moisture Sensor   | 1        |   Detects the moisture level in the soil by measuring conductivity                 |
| DHT11 Sensor           | 1        | To detect the temperature and humidity           |
| Photoresistor (LDR)    | 1        | For light measurement                  |
| LCD 16x2 (I2C module)  | 1        | Displays real time readings                 |
| Green LED              | 1        | Soil moisture >50% = Good                    |
| Orange LED             | 1        | Soil moisture ~30% = Moderate                    |
| Red LED                | 1        | Soil moisture < 10% = Low moisture        |
| Breadboard             | 1        | For prototyping and experimenting                       |
| Jumper Wires           | 10+      | To connect components (Female or Male connectors)          |
| 9V Battery             | 1        | Powers the system                      |

---
## Soil moisture detector
<img width="420" height="522" alt="Screenshot 2025-08-20 090954" src="https://github.com/user-attachments/assets/a3591f1e-447a-4426-9a99-0de228a09199" /> <img width="424" height="496" alt="Screenshot 2025-08-20 092450" src="https://github.com/user-attachments/assets/cec03b9f-1ffe-4240-9b1a-e8d6ba269a45" /> <img width="166" height="518" alt="Screenshot 2025-08-20 093041" src="https://github.com/user-attachments/assets/e2dc7993-2322-4a7d-9bce-dc653c2595dc" />
<img width="419" height="457" alt="image" src="https://github.com/user-attachments/assets/0f13ae0d-460c-4bc5-b349-536677e756d1" /> <img width="504" height="454" alt="image" src="https://github.com/user-attachments/assets/1974723a-85c0-49f8-aa19-1e93f6f4f03a" />

## Laser Cutting workshop

As part of this project, I attended hands-on workshops that helped me gain essential fabrication and prototyping skills.
- Laser Cutting Workshop – Learned about routine checks, machine maintenance, carbon air filters, focusing tools, bed leveling, and engraving techniques.
- CNC and Additive Manufacturing  – We explored subtractive vs. additive manufacturing, CNC routing operations, tool bits, spindle motors, safety practices, and software workflows.
- Design Tools – Practiced CAD design in Onshape, generated toolpaths using Kiri:Moto, and prepared files for laser cutting.
## Testing the laser cutting machine
<img width="1034" height="483" alt="image" src="https://github.com/user-attachments/assets/3271751c-59ea-4ba5-907c-2de13b75b2dc" />
<img width="1033" height="297" alt="image" src="https://github.com/user-attachments/assets/de8aa434-fb6d-4d78-a152-317b18902a6d" />

## Laser cutting and photo engraving using ImagR
<img width="831" height="429" alt="Screenshot 2025-09-17 091921" src="https://github.com/user-attachments/assets/d383d9c1-d6bd-451e-b3b6-4a34d2d0d8aa" />

---

## Conclusion 
Thank you for checking out the Soil Moisture Detector System! This project provides a simple and effective way to monitor soil moisture, conserve water, and support healthy plant growth.

**For future improvements I will:**
- Improve the system by integrating an automatic irrigation pump.
- Add mobile app or web interface for real-time monitoring remotely.
- Experiment with different soil sensors to increase accuracy.


**Author:**
Rea Diale – mananadiale@gmail.com
