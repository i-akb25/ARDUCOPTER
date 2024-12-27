# Arducopter - The Arduino Auto-Level Quadcopter 🚁

![GitHub repo size](https://img.shields.io/github/repo-size/i-akb25/ARDUCOPTER?color=ff69b4&style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/i-akb25/ARDUCOPTER?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/i-akb25/ARDUCOPTER?color=ff69b4&style=flat-square) 

Welcome to the **Arducopter Project**—an auto-leveling Arduino Uno-based quadcopter that is easy to build and a joy to fly. With its auto-leveling feature, the Arducopter self-stabilizes when you release the control sticks, making it perfect for both beginners and hobbyists alike.

---

## Table of Contents 📜
- [Overview](#overview)
- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Step-by-Step Guide](#step-by-step-guide)
- [FAQs](#faqs)

---

## Overview 🌟
The **Arducopter** is designed to provide an easy-to-understand and customizable flight controller for quadcopters. It is **not** a high-end flight controller but is ideal for those who want to learn the basics of quadcopter flight control and coding.

The project comes with:
- Well-documented code.
- A step-by-step building guide.

---

## Features ✨
- **Auto-Leveling:** The quadcopter self-levels during flight.
- **Customizable Code:** Modify and extend the flight controller software for your own needs.
- **Education Tutorial:** Learn about gyros, ESCs, and PID controllers.

---

## Hardware Requirements ⚙️
To build the Arducopter, you'll need the following components:

| Component                        | Quantity |
|----------------------------------|----------|
| 450-size frame with power distribution | 1 |
| 1000kV motors + 10x4.5 props + ESC 30A combo | 4 |
| 3S 2200mAh 35C LiPo battery     | 1 |
| Arduino Uno or Funduino Uno     | 1 |
| MPU-6050 gyro/accelerometer      | 1 |
| Flysky FS-i6 6-CH Transmitter   | 1 |
| 2S/3S LiPo battery charger       | 1 |
| Resistors (1.5kΩ, 1kΩ, 330Ω), diode (1N4001), LED, wires, and connectors | As needed |

> **Tip:** Use **8x4.5 props** for better motor response and to reduce ESC stress.

---

## Step-by-Step Guide 🛠️

### 1. **Software Setup**
- Download the complete Arducopter software package.
- Extract the zip file and read the `README.txt` file.

### 2. **Build the Quadcopter**
- Follow the [Arducopter Hardware Tutorial](#) to assemble the frame, motors, ESCs, and other components.
- Ensure correct orientation of the MPU-6050 gyro (Z-axis vertical).

### 3. **Connect Components**
- Connect the transmitter and receiver as per the provided schematic.
- Ensure correct wiring for the ESCs and resistors.

### 4. **Calibrate ESCs**
- Remove props and calibrate ESCs to ensure consistent motor performance.

### 5. **Test the Setup**
- Run setup programs to:
  - Check receiver input.
  - Validate gyro and accelerometer angles.
- Adjust PID settings if necessary.

### 6. **Upload Flight Controller Code**
- Upload the flight controller software to the Arduino Uno.
- Conduct test flights outdoors, preferably over grass for safety.

---

## FAQs ❓
### Q: Can I use a different gyro/accelerometer?
A: No. The Arducopter software only supports the **MPU-6050** due to its auto-leveling feature.

### Q: Do I need prior experience with Arduino?
A: Basic knowledge of Arduino and RC systems is helpful but not mandatory. The tutorials cover all essential aspects.

---

## Safety Note ⚠️
Always prioritize safety when testing or flying your Arducopter:
1. Test in open areas.
2. Wear protective gear.
3. Remove props during setup.

---

## License 📄
This project is free to use for educational and personal purposes. Attribution is appreciated.

Happy Flying! 🚀
