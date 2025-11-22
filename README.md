# 📦 Intelligent Robotic Medicine Storage System – ASQII HealthTech

Final Year Project – Computer Vision & Robotics  
ASQII HealthTech | Tunis, Tunisia | 2024–2025

---

## 🎥 Project Demonstration

### 1️⃣ Computer Vision Pipeline (GIF)
![Computer Vision Demo](media/cv_demo.gif)

### 2️⃣ Robotic Storage System (GIF)
![Robot Demo](media/robot_demo.gif)

### 🖼️ OCR Extraction Example
![OCR Example](media/ocr_example.png)

---

## 🚀 Project Overview

This final-year project was carried out within the startup **ASQII HealthTech**.  
Its goal is the **design and implementation of an automated intelligent storage system for pharmaceutical products** using computer vision and robotics.

The work is structured around **two major components**:

---

## 📌 1. Computer Vision Pipeline (OCR-Based Medicine Recognition)

A complete CV pipeline was developed to:
- Detect medicine boxes in captured images  
- Correct orientation  
- Extract text using **OCR**  
- Identify medicine names, dosages, and quantities  
- Match results against a pharmaceutical database  

This module enables **high-accuracy recognition** even from noisy or rotated images.

---

## 📌 2. Automated Storage Robot (Cartesian XY System)

The second part of the project focuses on an automated robotic storage system based on:
- A **Cartesian XY robot**
- A **gripper** for box handling  
- Motion control using **ESP32-based boards**  
- Task execution after receiving commands from the CV pipeline  

The robot:
➡️ Retrieves the identified medicine  
➡️ Moves it to the appropriate storage location  
➡️ Places it safely inside the cabinet  

This ensures **fully automated and reliable operation**.

---

## 🔄 System Communication

All modules communicate via a **secure MQTT protocol**, enabling:
- Real-time coordination  
- Reliable message transmission  
- Scalability for modular expansion  

---

## 🧪 Development Methodology

The project followed the **Agile SCRUM methodology**, integrating:
- Computer Vision development  
- Mechanical design of the XY robot  
- PCB & electronic design based on ESP32  
- MQTT and communication protocol design  
- Iterative testing and refinement  

---

## 🧠 Tech Stack

- **Computer Vision:** Python, OpenCV, OCR, YOLO/OBB models  
- **Robotics:** ESP32, Stepper motors, Endstops, Gripper  
- **Communication:** MQTT (secure), JSON messaging  
- **Embedded Electronics:** PCB design, sensors & actuators  
- **Mechanical:** Cartesian robot, custom gripper  

---

## 📚 Keywords

Computer Vision · OCR · Cartesian Robot · MQTT · Pharmaceutical Automation · ESP32 · Sensors & Actuators · Robotics · Embedded Systems

---

## 📁 Repository Structure

