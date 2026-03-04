# 🌱 Solar-LoRa Smart Farming System

**Solar-powered LoRa IoT smart farming system with ESP32 sensor nodes and AI-based predictive monitoring.**

## 📌 Project Overview

This project implements a **precision agriculture monitoring system** designed for small farms.
Multiple sensor nodes collect environmental and soil data and transmit it to a central farm node using **ESP-NOW**. The farm node then sends the data over **LoRa** to a receiver station for remote monitoring.

The system is **solar-powered**, energy-efficient, and capable of long-range communication, making it suitable for farms where internet connectivity is limited.

---

## 🏗 System Architecture

Sensor Nodes (ESP32 + Sensors)
⬇ ESP-NOW Communication
Main Farm Node (ESP32 + LoRa Transmitter)
⬇ LoRa Long Range Communication
Receiver Node (ESP32 + LoRa + WiFi)
⬇
Web Dashboard for Monitoring

---

## ⚙️ Hardware Components

* ESP32 Microcontroller
* SX1278 LoRa Module
* Soil Moisture Sensor
* Soil pH Sensor
* Temperature & Humidity Sensor
* Solar Power System
* LoRa Antenna

---

## 📡 Communication Technologies

### ESP-NOW

Used for **low-power communication between multiple sensor nodes and the main farm node**.

### LoRa

Used for **long-range communication between the farm node and the receiver station**.

### WiFi

Used by the receiver node to **display sensor data on a web dashboard**.

---

## 🚀 Features

* Multi-node sensor network
* Long-range LoRa communication
* Solar-powered system
* Remote farm monitoring
* Scalable architecture for large farms

---

## 🔮 Future Improvements

* AI-based crop health prediction
* Automated irrigation control
* Weather data integration
* Mobile application monitoring

---

## 👨‍💻 Author

**Gautam**
