# 🚨 Accident Detection & Telegram SOS System (ESP8266 + SW-420)

## 📌 Overview
This project uses an **ESP8266 (NodeMCU)** and an **SW-420 vibration sensor** to detect accidents.  
When a vibration above a certain threshold is detected, the system automatically sends an **SOS alert message** to a **Telegram chat** using a Telegram Bot.  

## 🛠️ Hardware Requirements
- ESP8266 NodeMCU
- SW-420 vibration sensor
- Breadboard + jumper wires
- USB cable for programming

## 💻 Software Requirements
- [Arduino IDE](https://www.arduino.cc/en/software)
- ESP8266 Board Manager installed in Arduino IDE
- Libraries:
  - `ESP8266WiFi.h`
  - `WiFiClientSecure.h`
  - `UniversalTelegramBot.h`

## 📂 Project Structure
