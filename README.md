# 🌾 Real-Time Soil Moisture Monitoring System using ESP32 and Firebase

This project presents a smart agricultural solution designed to help farmers monitor soil moisture levels in real time. By integrating an ESP32 microcontroller with a soil moisture sensor and Firebase Realtime Database, the system enables remote crop monitoring from anywhere via internet connectivity.


## Features

- 📡 Real-time soil moisture data acquisition
- 🌐 Remote monitoring via Firebase
- 🔧 Simple hardware and software setup
- 📊 Scalable system for multiple plants or fields
- 🔒 Secure data transmission using Wi-Fi



## Tech Stack

| Component      | Details                          |
|----------------|----------------------------------|
| Microcontroller| ESP32                            |
| Sensor         | Soil Moisture Sensor (Analog)    |
| Cloud Platform | Firebase Realtime Database       |
| IDE            | Arduino IDE                      |
| Programming    | Embedded C / Arduino Framework   |



## Hardware Requirements

- ESP32 Dev Board  
- Analog Soil Moisture Sensor  
- Breadboard and Jumper Wires  
- USB Cable  
- Wi-Fi Access Point

---

## Software Setup

### 1. Install Dependencies
- [Arduino IDE](https://www.arduino.cc/en/software)
- ESP32 Board Manager  
- Libraries:
  - FirebaseESP32
  - WiFi

### 2. Firebase Configuration
- Create a Firebase project
- Enable Realtime Database
- Database URL:"https://esp32-6ea6c-default-rtdb.asia-southeast1.firebasedatabase.app/"
- API key:"AIzaSyDD0oSM_wqSgAxqn9Qr3Bre4433AmloJmc"

### 3. Upload Code to ESP32
#define WIFI_SSID "Mamatha"
#define WIFI_PASSWORD "mamatha123"
