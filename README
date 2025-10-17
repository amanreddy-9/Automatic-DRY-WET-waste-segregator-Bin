# ♻️ Automatic Waste Segregation System Using Arduino ♻️

### 🚮 Smart | 💧 Sustainable | ⚙️ Sensor-Based | 🧠 ROS 2 Enabled | 🧱 3D Printable

---

## 🧠 **Project Overview**

The **Automatic Waste Segregation System** is a smart and sustainable automation project designed to **separate wet and dry waste** automatically. Using an **Arduino Uno**, **soil moisture sensor**, **ultrasonic sensor**, and **servo motor**, the system identifies waste type and directs it into respective compartments.  

It offers **touch-free operation**, **eco-friendly design**, and can be easily **3D printed** for compact and durable housing. The system can also be **integrated with ROS 2 (Robot Operating System)** for advanced control, monitoring, and future IoT or robotics expansion.

---

## ⚙️ **Working Principle**

1. 🧭 **Detection:**  
   Ultrasonic sensor detects waste presence near the lid.  

2. 🕹️ **Automation:**  
   Servo motor opens the lid automatically.  

3. 💧 **Classification:**  
   Soil moisture sensor measures moisture:  
   - 💦 *High* → **Wet Waste (Biodegradable)**  
   - 🧱 *Low* → **Dry Waste (Non-Biodegradable)**  

4. 🔁 **Segregation:**  
   Arduino drives servo to direct waste into correct compartment.

---

## 🧱 **3D Printing Compatibility**

The enclosure and dual-bin structure of the system can be **3D printed** using PLA or PETG filament.  
- 🧩 The main bin body can include **two internal partitions** for wet and dry waste.  
- ⚙️ Servo and sensors can be **mounted using printed brackets**.  
- 💡 A **hinged lid** or **servo-driven flap** can also be printed for smooth operation.  

This allows for a **lightweight**, **customizable**, and **aesthetically modern** prototype suitable for home, lab, or exhibition use.

---

## 🤖 **ROS 2 Integration (Convenient Explanation)**

The system can be seamlessly connected to **ROS 2 (Robot Operating System 2)** for intelligent automation and monitoring.

**Integration Concept:**
- The Arduino sends data (e.g., “WET WASTE” or “DRY WASTE”) via serial communication to a **ROS 2 node** running on a Raspberry Pi or PC.
- A simple **ROS 2 publisher node** reads this serial data and publishes it on a topic, for example:  
  ```bash
  /waste_status → "WET WASTE"
