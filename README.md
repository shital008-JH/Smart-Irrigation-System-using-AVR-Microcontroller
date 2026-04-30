#🌱 Smart Irrigation System (AVR Based)

An automated irrigation system that monitors soil moisture in real time and controls water supply accordingly. This project uses a microcontroller-based approach to reduce water wastage and improve plant growth by ensuring optimal soil conditions.
---

## 📖 Overview

Traditional irrigation systems often rely on fixed schedules or manual control, which can lead to inefficient water usage. This system solves that problem by continuously sensing soil moisture and making automatic decisions using a microcontroller.
---

### It follows a simple logic:
👉 Dry soil → Pump ON
👉 Wet soil → Pump OFF
---

## ⚙️ How It Works

The system operates in a continuous loop:

Soil moisture sensor reads moisture level
Microcontroller processes the data using ADC
Compares with threshold values
Controls relay based on condition
Relay switches the water pump ON/OFF

A minimum runtime condition is also applied to prevent rapid switching of the pump.

---

## 🧩 Tech Stack / Components

Hardware:

Microcontroller (ATmega32 / ATmega328P)
Soil Moisture Sensor
Relay Module
DC Water Pump
Power Supply

Others:

Breadboard
Jumper Wires
🔌 System Architecture
Soil Sensor → Microcontroller → Relay → Water Pump
Sensor → Analog input (A0)
Relay → Digital output (D6)
Common Ground for all components

---

## 💡 Key Features
Real-time soil monitoring
Automatic irrigation control
Safe switching using relay
Water conservation
Low-cost and easy to implement
Suitable for small & large setups

---

## 🧠 Logic Used
Dry Condition:
Moisture value > dryThreshold → Pump ON
Wet Condition:
Moisture value < wetThreshold → Pump OFF
Protection:
Minimum pump runtime to avoid frequent switching

---

## 🌍 Applications
Agricultural fields
Home gardening
Greenhouses
Smart farming systems
Landscaping & parks
---

##🔮 Future Improvements
IoT-based remote monitoring
Mobile app integration
Solar-powered system
AI-based irrigation logic
---

## 📌 Advantages
Efficient water usage
Fully automated
Reduces manual effort
Cost-effective
Improves plant health
---

### 📄 Note

This project was developed as a group project as part of academic work.
---

##⭐ Support

If you found this project useful, consider giving it a ⭐ and sharing it!
---
