#  Trash Rover 

## Overview
**Trash Rover** is a 4-wheel drive autonomous robot designed to collect trash that piles up after the snow melts in Canada.  
The goal is to make garbage collection easier, cleaner, and more efficient through robotics and automation.

This project is a personal build that combines **Arduino**, **Raspberry Pi**, and **computer vision** to create a functional prototype that can detect and collect trash using a ramp mechanism.

---

##  Features
-  4-wheel drive system for stability and outdoor movement  
-  Ramp-based mechanism to collect trash  
-  Raspberry Pi 5 for camera and processing  
-  Arduino Mega for motor control and sensor inputs    
-  Expandable with sensors and AI object detection

---

## Components & Tech Stack
**Hardware:**
- Raspberry Pi 5 (8GB)
- Arduino Mega
- 4x Servo motors
- Power supply / battery pack
- L-brackets, corner braces, and chassis parts

**Software:**
- Python
- Arduino IDE
- OpenCV (for object detection)
- Linux (Raspberry Pi OS)

##  How the EcoRover Works

The **EcoRover** is designed to collect trash using a front-mounted ramp system inspired by medieval drawbridges.  
When the onboard vision system detects trash, the ramp lowers and the rover drives forward, allowing the garbage to slide onto the ramp. Once the object is inside the collection zone, the ramp closes, causing the trash to fall neatly into the internal storage area.

The rover will use a **4-wheel drive** system for better traction and maneuverability.  
A **Raspberry Pi 5 (8GB)** will handle object detection through **YOLO**, while an **Arduino Mega** will control the motors and ramp mechanism.  
A dedicated **power supply** will provide stable energy to all components. Additional hardware and features will be determined as the project evolves.


