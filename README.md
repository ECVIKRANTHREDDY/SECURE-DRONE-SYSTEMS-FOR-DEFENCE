# Secure Drone System for Defense

## Overview
The **Secure Drone System for Defense** is an AI-powered drone developed during the **Quest Global Ingenium Hackathon 2025**. The project focuses on **real-time object detection, secure navigation, and operational resilience** in defense scenarios. The drone is designed to operate reliably even under **GPS spoofing attacks** and integrates multiple navigation systems to ensure positional accuracy.

This project demonstrates a combination of **machine learning, computer vision, and software engineering principles**, aimed at building scalable, secure, and efficient autonomous systems for defense applications.

---

## Motivation
Drones are increasingly used in defense for reconnaissance, surveillance, and tactical operations. However, **GPS spoofing attacks** and unauthorized access can compromise their effectiveness. The main motivation behind this project was to:

- Ensure drones **operate securely** in contested environments.
- Implement **real-time object detection** for situational awareness.
- Build a **robust multi-navigation system** to mitigate GPS vulnerabilities.
- Showcase innovation and practical problem-solving in a competitive hackathon environment.

---

## Features

### 1. Real-Time Object Detection
- Utilizes **ML models (CNN, YOLO variants)** for detecting objects.
- Capable of tracking moving objects in live drone video feeds.
- Supports **multiple object classes** relevant to defense scenarios.

### 2. Anti-GPS Spoofing Mechanism
- Integrates **GPS with alternative navigation systems** to maintain positional accuracy.
- Detects abnormal GPS coordinates and switches to **backup navigation sources**.
- Ensures reliable drone operation even if primary GPS is tampered with.

### 3. Secure Communication
- Implements **encryption protocols** to secure drone control and data transmission.
- Prevents unauthorized access and ensures data integrity.
- Uses **lightweight encryption** suitable for real-time communication.

### 4. Defense-Focused Design
- Optimized for **scalability and operational reliability**.
- Modular software design for **easy maintenance and upgrades**.
- Focused on practical **defense-oriented functionality**.

---

## Architecture
[ Drone Hardware ]
|
[ Navigation Module ] ----> Anti-GPS Spoofing
|
[ Object Detection Module ] ----> Real-time Video Feed
|
[ Communication Module ] ----> Secure Control & Data
|
[ Central Control System ]


- **Navigation Module:** Integrates GPS and alternative positioning systems.
- **Object Detection Module:** ML model for tracking and detecting objects.
- **Communication Module:** Securely transmits data and receives commands.
- **Central Control System:** Coordinates all modules for autonomous operation.

---

## Technology Stack
- **Programming Languages:** Python, C++
- **Machine Learning & AI:** PyTorch, TensorFlow
- **Computer Vision Libraries:** OpenCV, NumPy
- **Navigation & Control:** GPS, alternative positioning systems
- **Software Tools:** Git, VS Code, ROS (Robot Operating System)
- **Deployment:** Real-time embedded system on drone hardware

---

## Modules

### 1. Object Detection
- Uses Convolutional Neural Networks (CNNs) to detect objects.
- Optimized for **low-latency inference** for real-time video streams.
- Handles **multi-class detection** with accuracy metrics logged for evaluation.

### 2. Navigation
- Implements **multi-navigation integration**: GPS + alternative systems.
- Detects **GPS anomalies** and switches to backup coordinates.
- Ensures **accurate drone positioning** under spoofing attacks.

### 3. Security
- Encrypts all communications between drone and base station.
- Implements **lightweight, fast encryption** suitable for real-time operations.
- Logs unauthorized access attempts for monitoring.

---
