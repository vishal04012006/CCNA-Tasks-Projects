# Task 5 – IoT Device Automation Using Server (Motion Detection System)

## 📌 Overview
This repository contains **Task 5** of my Cisco Packet Tracer practice labs.  
In this task, I designed and implemented a simple **IoT-based automation system** using:

- Motion Detector Sensor  
- Webcam  
- Smart Door  
- IoT Server  

The main objective of this task is to simulate a **smart security system** where devices automatically respond based on motion detection conditions configured on the server.

The lab was created and tested using **Cisco Packet Tracer 8.2.2**.

---

## 🎯 Objectives
- Connect IoT devices to a centralized IoT server
- Configure automation rules using device conditions
- Implement motion-based security control
- Understand basic IoT network communication and automation logic

---

## 🧪 Lab Description

### 🔹 Network Setup
In this task, the following IoT devices were connected through a switch to a central server:

- Motion Detector Sensor
- Webcam
- Smart Door
- Server (IoT Monitor)

All devices were registered and managed through the IoT server interface.

---

### 🔹 Automation Logic Configuration

All automation conditions were configured inside the **IoT Server** under device conditions.

Two main rules were created:

#### ✅ Rule 1 – When Motion is Detected
- Condition: Sensor is ON (Human detected)
- Action:
  - Turn ON the Webcam
  - Unlock / Open the Door

This simulates a smart entry system where the camera activates and the door opens automatically when a person is detected.

---

#### ✅ Rule 2 – When No Motion is Detected
- Condition: Sensor is OFF (No human detected)
- Action:
  - Turn OFF the Webcam
  - Lock / Close the Door

This ensures security by automatically locking the door and turning off monitoring devices when no movement is detected.

---

## ⚙️ Working Mechanism

1. The motion detector senses human movement.
2. The sensor sends its status to the IoT server.
3. The server checks the configured condition rules.
4. Based on the rule:
   - The webcam is activated or deactivated.
   - The smart door is unlocked or locked.

All device behavior is controlled centrally from the server.

---

## ✅ Results
- IoT devices successfully connected to the server.
- Motion detection triggered automatic actions.
- Webcam and door responded correctly based on sensor state.
- Full automation achieved without manual intervention.

---

## 🛠 Tools Used
- Cisco Packet Tracer 8.2.2
- IoT Server
- Motion Detector Sensor
- Webcam
- Smart Door
- 2960 Switch

---

## 📚 Learning Outcomes
Through Task 5, I learned:

- How IoT devices communicate in a network
- How to configure automation rules on an IoT server
- Basic event-driven automation logic
- Centralized control of smart devices
- Practical implementation of a smart security system

---

## 👨‍🎓 Student Details
- **Name:** Vishal A
- **Department:** BE – Cyber Security
- **Institution:** Mahendra Engineering College
