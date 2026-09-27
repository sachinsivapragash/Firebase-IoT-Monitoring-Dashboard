# Firebase IoT Monitoring Dashboard

## 📌 Overview

A cloud-based IoT monitoring dashboard built with **Firebase**. The system provides a login-protected web dashboard for monitoring **temperature, humidity, ambient light, and device status** through Firebase Realtime Database.

The dashboard also allows users to send **bulb ON/OFF control commands** through the Firebase database.

---

## 🎯 Objective

The objective of this project is to build a secure cloud monitoring system using **Firebase Authentication, Firebase Realtime Database, and Firebase Hosting**.

The dashboard:

- Displays live sensor data
- Shows device status
- Provides bulb control
- Uses login authentication
- Uses database security rules
- Runs through Firebase Hosting

---

## ☁️ Technologies Used

- **Firebase**
- **Firebase Realtime Database**
- **Firebase Authentication**
- **Firebase Hosting**
- **Firebase CLI**
- **HTML**
- **CSS**
- **JavaScript**
- **Node.js**

---

## 🏗️ System Design

```text
             Firebase Realtime Database
                       ↕
              Login-Protected
                 Web Dashboard
                       │
          ┌────────────┴────────────┐
          ↓                         ↓
     Sensor Data               Bulb Control
          │                         │
   ┌──────┴──────┐                  │
   │             │                  │
Temperature   Humidity          ON / OFF
   │             │                  │
   └──────┬──────┘                  │
          │                         │
       LDR Light                    │
                                    │
                              Future Device
