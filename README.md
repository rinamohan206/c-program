# 🔥 Fire & Smoke Detection System &🌦️ Weather Monitoring System

This repository contains **two IoT/Embedded Systems projects** built using Arduino and ESP32:

1. Fire and Smoke Detection System (Arduino Uno)
2. Weather Monitoring System (ESP32 + Blynk IoT)

---

# 🔥 1. Fire and Smoke Detection System (Arduino)

## 📌 Project Overview
This project is an Arduino-based safety system that detects fire and smoke using sensors. It displays real-time smoke levels on a 16×2 I2C LCD and triggers a buzzer alarm when fire or high smoke levels are detected.

---

## ✨ Features
- Fire detection using Flame Sensor  
- Smoke detection using MQ Smoke Sensor  
- Real-time smoke level display (LOW / MEDIUM / HIGH)  
- 16×2 I2C LCD display  
- Buzzer alarm system  
- Serial Monitor output  

---

## 🧰 Components Used
- Arduino Uno  
- MQ Smoke Sensor  
- Flame Sensor  
- 16×2 I2C LCD Display  
- Buzzer  
- Breadboard & Jumper Wires  

---

## 🔌 Pin Connections

| Component       | Arduino Pin |
|----------------|-------------|
| Smoke Sensor   | A0          |
| Flame Sensor   | D8          |
| Buzzer         | D9          |
| I2C LCD        | SDA, SCL    |

---

## ⚙️ Working
- Smoke sensor continuously reads air quality levels  
- Flame sensor detects fire presence  
- LCD shows smoke level and fire status  
- Buzzer activates when fire or high smoke is detected  
- Serial Monitor displays sensor values  

---

## 🎯 Applications
- Home Safety Systems  
- Industrial Safety  
- Laboratories  
- Offices & Warehouses  

---

## 📤 Output
- LOW / MEDIUM / HIGH smoke levels on LCD  
- “FIRE DETECTED” alert message  
- Buzzer alarm activation  
- Serial monitor data logging  

---

# 🌦️ 2. Weather Monitoring System (ESP32 + Blynk IoT)

## 📌 Project Overview
This IoT-based system uses ESP32 and multiple sensors to monitor environmental conditions like temperature, humidity, rainfall, pressure, and air quality in real time. Data is displayed on LCD and sent to the Blynk mobile app.

---

## ✨ Features
- Real-time Temperature & Humidity monitoring  
- Rain detection system  
- Atmospheric pressure monitoring  
- Air quality monitoring  
- LCD live data display  
- Remote monitoring using Blynk IoT app  

---

## 🧰 Components Used
- ESP32 Development Board  
- DHT11 Sensor  
- BMP180 Pressure Sensor  
- MQ135 Air Quality Sensor  
- Rain Sensor Module  
- 16×2 I2C LCD Display  
- Jumper Wires & Breadboard  

---

## ☁️ Blynk Virtual Pins

| Sensor        | Virtual Pin |
|--------------|-------------|
| Temperature  | V0          |
| Humidity     | V1          |
| Rain Sensor  | V2          |
| Pressure     | V3          |
| Air Quality  | V4          |

---

## ⚙️ Working
- Sensors collect environmental data  
- ESP32 processes and sends data via Wi-Fi  
- LCD displays live readings  
- Blynk app shows remote sensor values  
- Air quality alert activates LED indicator  

---

## 🎯 Applications
- Smart Weather Stations  
- Smart Agriculture  
- Greenhouse Monitoring  
- Pollution Monitoring Systems  

---

## 📤 Output
- Live environmental data on LCD  
- Remote monitoring via Blynk app  
- Serial monitor logging  
- Air quality alert system  

---

# 👨‍💻 Author
**Rinamohan**

---
