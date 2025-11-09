<!-- TITLE -->
<h1 align="center">
  <b> GPS-Based Obstacle Avoiding Car</b><br>
  <sub><b>2nd Year Mini Project – ECE Department</b></sub>
</h1>

<!-- HEADER -->
<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=30&color=00C4FF&center=true&vCenter=true&width=850&lines=Autonomous+Navigation+;+Obstacle+Detection+;+Real-Time+GPS+Tracking" />
</h1>

<p align="center">
  <b>Developed using Arduino Nano, GPS NEO-6M, GSM SIM800L, and Ultrasonic Sensor</b>
</p>

---

## Project Overview

The **GPS-Based Obstacle Avoiding Car** is an autonomous robotic vehicle capable of **detecting obstacles**, **avoiding collisions**, and **transmitting its real-time location** using **GPS and GSM** modules.  
It integrates **ultrasonic sensing** for obstacle detection and **Arduino-controlled motor driving** for autonomous navigation, making it ideal for applications like **surveillance, logistics, and hazardous environment exploration**.

---

##  Key Features

-  **Real-Time GPS Tracking** – Provides continuous position updates via GPS NEO-6M.  
-  **GSM Communication** – Sends location coordinates to a predefined mobile number using SIM800L.  
-  **Ultrasonic Obstacle Detection** – Detects obstacles within 2–400 cm range and avoids collisions.  
-  **Autonomous Navigation** – Uses Arduino Nano and L298N motor driver for motor control and path correction.  
-  **Efficient Power Management** – Buck converters ensure stable power to each module.  

---

## 🧩 Block & Circuit Diagrams

### 🧱 Block Diagram
<p align="center">
<img width="414" height="391" alt="image" src="https://github.com/user-attachments/assets/fc241b65-b8a6-4613-a0ef-44b4ebf69962" />
</p>

### Circuit Diagram
<p align="center">

  <img width="679" height="421" alt="image" src="https://github.com/user-attachments/assets/34adfc19-81c8-4a14-8241-fedf639ef34e" />

</p>

---

## 🧰 Components Used

| Component | Specification / Model | Function |
|------------|------------------------|-----------|
| **Microcontroller** | Arduino Nano (ATmega328P) | Central control unit |
| **Ultrasonic Sensor** | HC-SR04 | Obstacle detection |
| **Servo Motor** | SG90 | Scans environment for obstacles |
| **GPS Module** | NEO-6M | Location tracking |
| **GSM Module** | SIM800L | Sends SMS with coordinates |
| **Motor Driver** | L298N Dual H-Bridge | Controls DC motors |
| **DC Motors + Wheels** | 2x 300RPM | Motion and navigation |
| **Power Supply** | 3S Li-ion (11.1V, 2200mAh) | Power source |
| **Buck Converter** | LM2596 | Voltage regulation |

---

## Working Principle

1. **Obstacle Detection:**  
   The ultrasonic sensor scans the path and sends distance data to Arduino Nano.  
   If an obstacle is detected, the car changes direction.

2. **Location Tracking:**  
   The GPS module continuously retrieves latitude and longitude coordinates.

3. **Data Transmission:**  
   Using the SIM800L GSM module, the robot sends its real-time location to a registered phone number via SMS.

4. **Motor Control:**  
   The Arduino sends PWM signals to the L298N motor driver for direction and speed control.

---

## Hardware Setup

<p align="center">
  <img src="https://github.com/user-attachments/assets/0c3c1a7e-54a1-4005-8c58-5d94b54408c5" width="300">
</p>

**Assembly Overview:**
- Arduino Nano placed centrally on a breadboard.  
- HC-SR04 ultrasonic sensor mounted on a servo motor at the front.  
- L298N connected to dual DC motors for movement.  
- GPS and GSM modules interfaced via UART pins.  
- Powered using Li-ion battery with voltage regulation.

---

## Software Implementation

- Programmed using **Arduino IDE**
- Language: **C/C++**
---

## Collaborator

- Mohd. Faiz (https://www.linkedin.com/in/mohd-faiz-710661353)
- Riya Verma (https://www.linkedin.com/in/riya-verma-641230317)
