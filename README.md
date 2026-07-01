Fire and Smoke Detection System using Arduino

Project Overview

This project is an Arduino-based Fire and Smoke Detection System that detects the presence of fire and smoke using sensors. The system displays the smoke level on a 16×2 I2C LCD and activates a buzzer when fire or high smoke is detected.

Features

- Detects fire using a flame sensor.
- Detects smoke using a smoke sensor.
- Displays smoke level on a 16×2 I2C LCD.
- Activates a buzzer as an alarm.
- Indicates Low, Medium, and High smoke levels.
- Displays fire detection status on the LCD.

Components Used

- Arduino Uno
- MQ Smoke Sensor
- Flame Sensor
- 16×2 I2C LCD Display
- Buzzer
- Breadboard
- Jumper Wires

Pin Connections

Component| Arduino Pin
Smoke Sensor| A0
Flame Sensor| D8
Buzzer| D9
I2C LCD| SDA, SCL

Working

1. The smoke sensor continuously monitors the smoke level.
2. The flame sensor detects the presence of fire.
3. The LCD displays the smoke level as LOW, MEDIUM, or HIGH.
4. If fire is detected, the LCD displays "FIRE DETECTED" and the buzzer turns ON.
5. If no fire is detected, the LCD displays "NO FIRE DETECTED".
6. The smoke level is also displayed in the Serial Monitor.

Software Used

- Arduino IDE
- Arduino C/C++

Applications

- Home Fire Safety
- Industrial Safety
- Laboratories
- Offices
- Warehouses

Output

- Displays LOW, MEDIUM, or HIGH smoke level on the LCD.
- Shows "NO FIRE DETECTED" when no fire is present.
- Shows "FIRE DETECTED" when a flame is detected.
- Activates the buzzer for fire detection and high smoke levels.
- Prints the smoke sensor value in the Arduino Serial Monitor.

Author
Rinamohan
<br>

Weather Monitoring System using ESP32

Project Overview

This project is an IoT-based Weather Monitoring System developed using ESP32, Blynk, and multiple environmental sensors. It monitors temperature, humidity, rainfall, atmospheric pressure, and air quality in real time. The sensor readings are displayed on a 16×2 I2C LCD and transmitted to the Blynk mobile application for remote monitoring.

Features

- Real-time Temperature Monitoring
- Humidity Measurement
- Rain Detection
- Atmospheric Pressure Monitoring
- Air Quality Monitoring
- LCD Display for Live Sensor Data
- Remote Monitoring using the Blynk App

Components Used

- ESP32 Development Board
- DHT11 Temperature and Humidity Sensor
- BMP180 Pressure Sensor
- MQ135 Air Quality Sensor
- Rain Sensor Module
- 16×2 I2C LCD Display
- Jumper Wires
- Breadboard

Software Used

- Arduino IDE
- ESP32 Board Package
- Blynk IoT Platform
- Arduino C/C++

Working

1. The DHT11 sensor measures temperature and humidity.
2. The BMP180 sensor measures atmospheric pressure.
3. The rain sensor detects rainfall intensity.
4. The MQ135 sensor monitors air quality.
5. All sensor values are displayed on the 16×2 LCD.
6. The readings are sent to the Blynk mobile application through Wi-Fi.
7. The Blynk LED indicator turns ON when poor air quality is detected.

Blynk Virtual Pins

Sensor| Virtual Pin
Temperature| V0
Humidity| V1
Rain Sensor| V2
Pressure| V3
Air Quality LED| V4

Applications

- Smart Weather Monitoring
- Environmental Monitoring
- Smart Agriculture
- Greenhouse Monitoring
- Air Pollution Monitoring

Output

- Displays Temperature and Humidity on the LCD.
- Displays Rainfall Level and Atmospheric Pressure on the LCD.
- Sends real-time sensor data to the Blynk mobile application.
- Turns ON the Blynk LED when poor air quality is detected.
- Displays all sensor readings in the Arduino Serial Monitor for monitoring.

Author

Rinamohan
