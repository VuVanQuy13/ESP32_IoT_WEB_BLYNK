# 🌍 IoT Environmental Monitoring System with ESP32 + WebSocket + Blynk

## 📌 Introduction
This is an **IoT environmental monitoring system** built using the **ESP32**.  
The system measures **temperature, humidity, and dust concentration**, then displays the data in real time on:  

- A **Web Dashboard** (HTML/CSS + WebSocket) hosted directly on the ESP32.  
- The **Blynk IoT app** for remote monitoring and control over the Internet.  

The system supports **Automatic/Manual modes** and allows alert thresholds to be adjusted directly through the **web interface** or the **Blynk app**. Threshold values are stored using **Preferences (ESP32 emulated EEPROM)** so they are retained after a restart.

---

## ⚙️ Features

- 🌡 Measure **temperature & humidity** using a **DHT11** sensor  
- 🌫 Measure **dust concentration** using a **Sharp GP2Y10** sensor (with a custom C++ library)  
- 📡 **Real-time Web Dashboard** (WebSocket + SPIFFS + Bootstrap)  
- 📱 Connect to **Blynk IoT Cloud** for remote monitoring & control  
- 🔧 **Adjust alert thresholds** using sliders on the web interface or in the Blynk app  
- 💾 Store settings using **Preferences** (retained after a reset)  
- 🛡 Integrated **Watchdog Timer (WDT)** and **automatic WiFi reconnection** for system stability  
- 💡 **Automatic/Manual modes** for controlling alert LEDs  

---

## 🛠 Technologies & Tools

- **Languages:** C, C++ (Arduino Framework)  
- **Microcontroller:** ESP32  
- **IoT Platform:** Blynk IoT Cloud  
- **Web:** HTML, CSS, Bootstrap, FontAwesome, WebSocket  
- **Sensors:** DHT11, Sharp GP2Y10  
- **Libraries:** ESPAsyncWebServer, Arduino_JSON, SPIFFS, Preferences, esp_task_wdt  
- **Development Tools:** Arduino IDE / PlatformIO, GitHub  

---

## 📂 Project Structure

├── firmware/ # ESP32 code  
├── data/ # HTML, CSS, and JS files for SPIFFS  
└── README.md    

---
## Web Dashboard Interface:  
<img width="1917" height="913" alt="image" src="https://github.com/user-attachments/assets/ed7c83a6-ef63-4d88-a2bc-2574b901cb92" />  

---
## BLYNK Interface:  
<img width="1617" height="742" alt="image" src="https://github.com/user-attachments/assets/f35b83a9-2b18-497a-9ec4-69e8e346aa2f" />  

---
## Altium:
- **SCH**: 
<img width="1081" height="717" alt="image" src="https://github.com/user-attachments/assets/3a977b6c-a00d-4419-afe5-d5c3162974ae" />

- **PCB**:
<img width="1119" height="712" alt="image" src="https://github.com/user-attachments/assets/37066228-31f4-4d04-9528-03fb1f0f843e" />

---
## Completed Circuit Board:
![ALtium](https://github.com/user-attachments/assets/f8a46e01-963e-4a49-8875-94911fc64c47)

![Bottom View](https://github.com/user-attachments/assets/4c70fc32-14a1-4549-aa13-a8ec93be3b7f)


