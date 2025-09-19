
# 🚀 ESP32 Bluetooth Servo Control

This project demonstrates how to control a **servo motor** using an **ESP32** and **Bluetooth serial communication**.  
You can send angle commands (0–180) from your phone or PC via a Bluetooth terminal, and the servo rotates accordingly.

---

## 🔧 Hardware Requirements
- ESP32 Development Board  
- Servo motor (e.g., SG90 / MG995)  
- External 5V power supply (recommended for stable servo operation)  
- Jumper wires  

---

## ⚡ Circuit Connections

| Servo Pin  | ESP32 / Supply |
|------------|----------------|
| VCC (Red)  | 5V (external supply or ESP32 5V) |
| GND (Brown/Black) | ESP32 GND (must be common with external supply) |
| Signal (Orange/Yellow) | GPIO 18 (can be changed to any PWM pin) |

⚠️ Important: If using an external 5V supply, connect its **GND** to the **ESP32 GND**.

---

## 📥 Setup & Installation

1. Install [Arduino IDE](https://www.arduino.cc/en/software) and configure **ESP32 Board Manager**.  
2. Install the required libraries:
   - **ESP32Servo** (by Kevin Harrington, John K. Bennett)  
   - **BluetoothSerial** (already included with ESP32 core)  

Connect your ESP32 via USB and upload the code.


