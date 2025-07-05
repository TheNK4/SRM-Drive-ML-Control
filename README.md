# 🚀 AETHER-SRM: Advanced Embedded Torque & Harmonic Elimination Relay for Switched Reluctance Motors

> **AETHER-SRM** is an AI-driven embedded solution that enhances Switched Reluctance Motor (SRM) performance by intelligently reducing torque ripple, suppressing harmonic distortion, and boosting power factor—**in real-time** using a low-cost ESP8266 microcontroller and SVM-based anomaly detection.

---

## 📌 Key Features

- ⚙️ **Torque Ripple Reduction**: 55.3%
- 🎧 **Harmonic Distortion Suppression**: 57.9%
- 🔋 **Power Factor Enhancement**: 21.1%
- 🧠 **Real-Time SVM-Based Fault Detection**
- 🔄 **Adaptive Switching Frequency Control**
- 🧾 **Minimal Hardware – No External Sensors**
- 💻 Embedded in ESP8266 using C, Python, and arduinoFFT

---

## 🎯 Project Objective

Switched Reluctance Motors are efficient and rugged but suffer from torque ripple and non-sinusoidal current profiles. This project:
- Reduces mechanical and electrical losses
- Performs **on-the-fly anomaly detection** using SVM (Support Vector Machines)
- Eliminates the need for expensive external signal conditioning or sensors
- Uses **embedded FFT analysis** to derive harmonic features for intelligent switching decisions

---

## ⚙️ Hardware Overview

| Component             | Description                                  |
|----------------------|----------------------------------------------|
| **ESP8266 NodeMCU**   | Core controller for PWM generation & logic  |
| **3-Phase SRM**       | 24V, ~0.5–1kW Switched Reluctance Motor      |
| **INA219 Sensor**     | Voltage & current feedback via I2C          |
| **MOSFET (IRF540N)**  | Switching devices in asymmetric converter   |
| **Snubber/Freewheeling** | For transient protection                 |
| **DC Supply**         | 24V, ≥5A regulated input                     |





---
