# 🌬️ Smart IoT Fan Controller

A smart fan automation system built using **ESP32**, **Firebase Realtime Database**, and a **responsive web dashboard**. The project automatically controls a fan based on room temperature while also allowing users to monitor and control the fan remotely over Wi-Fi.

---

## 📖 Project Overview

The Smart IoT Fan Controller is an IoT-based automation project that monitors the surrounding temperature and controls a fan automatically. It also provides a modern web dashboard where users can monitor real-time data, switch between Auto and Manual modes, and control the fan from anywhere using Firebase.

This project demonstrates the practical implementation of IoT, cloud computing, embedded systems, and web technologies.

---

## ✨ Features

- 🌡️ Real-time Temperature Monitoring
- 💧 Humidity Monitoring
- 🤖 Automatic Fan Control
- 🎮 Manual Fan ON/OFF Control
- 🔄 Auto and Manual Mode Switching
- ☁️ Firebase Realtime Database Integration
- 📊 Live Temperature Graph
- 📱 Responsive Web Dashboard
- 📺 OLED Display for Live Status
- 📶 Wi-Fi Connection Monitoring
- 🔄 Automatic Reconnection to Wi-Fi
- 🕒 Last Connected Status
- 🎤 Voice Control Support (Dashboard)
- 📈 Live Data Synchronization
- 🌐 Remote Access via Internet

---

## 🛠️ Technologies Used

### Hardware

- ESP32 Development Board
- DHT22 Temperature & Humidity Sensor
- SSD1306 OLED Display
- Relay Module
- DC Fan
- Power Supply (5V)

### Software

- Arduino IDE
- Firebase Realtime Database
- HTML
- CSS
- JavaScript
- Chart.js
- ESP32 Wi-Fi Library

---

## 📂 Project Architecture

```
        DHT22 Sensor
              │
              ▼
          ESP32 Controller
              │
      ┌───────┴────────┐
      │                │
      ▼                ▼
 OLED Display      Relay Module
                        │
                        ▼
                      DC Fan

              │
              ▼
      Firebase Realtime Database
              │
              ▼
       Web Dashboard (HTML/CSS/JS)
```

---

## ⚙️ Working

1. ESP32 connects to Wi-Fi.
2. Temperature and humidity are read from the DHT22 sensor.
3. Sensor values are displayed on the OLED display.
4. Data is uploaded to Firebase.
5. The web dashboard fetches live data from Firebase.
6. If Auto Mode is enabled:
   - Fan turns ON when temperature exceeds the threshold.
   - Fan turns OFF when temperature drops below the threshold.
7. If Manual Mode is enabled:
   - User controls the fan from the dashboard.
8. All changes are synchronized instantly.

---

## 📸 Dashboard Features

- Live Temperature Card
- Humidity Display
- Fan Status Indicator
- Auto / Manual Toggle
- Fan ON/OFF Buttons
- Wi-Fi Status
- Live Temperature Chart
- Voice Control Button
- Mobile Friendly UI

---

## 📁 Project Structure

```
Smart-IoT-Fan/
│
├── Arduino_Code/
│   └── Smart_IoT_Fan.ino
│
├── Website/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│
├── Images/
│
├── README.md
│
└── LICENSE
```

---

## 🚀 Installation

### Hardware Setup

- Connect DHT22 to ESP32.
- Connect OLED using I2C.
- Connect Relay to GPIO.
- Connect Fan through Relay.
- Power the ESP32.

### Software Setup

1. Install Arduino IDE.
2. Install ESP32 Board Package.
3. Install required libraries:
   - WiFi
   - Firebase ESP Client
   - DHT Library
   - Adafruit SSD1306
   - Adafruit GFX
4. Configure Wi-Fi credentials.
5. Configure Firebase credentials.
6. Upload the code.
7. Open the dashboard.

---

## 📊 Firebase Database

```
temperature
humidity
fan
mode
wifi
lastConnected
```

---

## 📈 Future Enhancements

- PWM Fan Speed Control
- Mobile Application
- Email Notifications
- Telegram Alerts
- Google Assistant Integration
- Alexa Integration
- Energy Consumption Monitoring
- Data Logging
- AI-based Temperature Prediction
- Weather API Integration
- Multiple Fan Support
- MQTT Communication

---

## 🎯 Applications

- Smart Home Automation
- Office Automation
- Server Room Cooling
- Laboratories
- Industrial Monitoring
- Greenhouse Automation
- College IoT Projects

---

## 👨‍💻 Author

**Aditya Singh**

B.Tech Computer Science Engineering

IoT & Embedded Systems Enthusiast

---

## 📚 Learning Outcomes

- Internet of Things (IoT)
- ESP32 Programming
- Cloud Database Integration
- Firebase Realtime Database
- Embedded Systems
- Sensor Interfacing
- Relay Control
- Responsive Web Development
- Real-time Data Synchronization

---

## 📄 License

This project is developed for educational and learning purposes.

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub and share it with others!
