# Mini PCB Plotter

A DIY CNC-based PCB plotting and engraving machine developed using Arduino UNO, stepper motors, and GRBL firmware.

## 📌 Project Overview

The Mini PCB Plotter is a computer-controlled machine designed to draw PCB layouts and perform basic PCB engraving operations.

The machine converts a digital PCB design into G-code and uses the G-code commands to control the movement of the X and Y axes and the Z-axis tool.

## ⚙️ Hardware Used

- Arduino UNO R3
- CNC Shield V3
- NEMA 17 Stepper Motors
- A4988 Stepper Motor Drivers
- Servo Motor for Z-axis
- 775 DC Motor for engraving
- 12V SMPS
- Mechanical frame and lead screws

## 💻 Software & Tools

- Arduino IDE
- GRBL Firmware
- Inkscape
- EasyEDA
- Universal G-code Sender (UGS)
- G-code

## 🔧 Working Principle

1. The PCB layout is designed using EasyEDA.
2. The required design is converted into a suitable tool path.
3. G-code is generated for machine movement.
4. Universal G-code Sender is used to send the G-code to the Arduino.
5. GRBL running on the Arduino interprets the G-code commands.
6. The stepper motors control the X and Y axis movement.
7. The Z-axis servo controls the tool position.
8. The engraving motor performs the required PCB plotting/engraving operation.

## 🧩 System Architecture

PC / PCB Design
        ↓
G-code Generation
        ↓
Universal G-code Sender
        ↓
Arduino UNO + GRBL
        ↓
CNC Shield
        ↓
A4988 Stepper Drivers
        ↓
NEMA 17 Stepper Motors
        ↓
X-Y Axis Movement

 🎯 Applications

- PCB layout plotting
- Basic PCB engraving
- CNC machine learning
- Embedded systems experimentation
- Educational prototyping

 📚 Skills Demonstrated

- Arduino
- Embedded Systems
- Stepper Motor Control
- Motor Driver Interfacing
- CNC Control
- G-code
- GRBL
- PCB Design
- Hardware Debugging
- Electronics Prototyping

## 👩‍💻 Project Status

Completed prototype / Academic Mini Project
<img width="1536" height="1536" alt="image" src="https://github.com/user-attachments/assets/9ed12e0c-3251-48e3-92f7-95328cfeb73e" />

<img width="1536" height="1536" alt="image" src="https://github.com/user-attachments/assets/18b372eb-cf7a-427c-9e77-9b717b43c238" />
<img width="640" height="360" alt="image" src="https://github.com/user-attachments/assets/9458264d-768b-4262-a506-e406c3014adb" />

