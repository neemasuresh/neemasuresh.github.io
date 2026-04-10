---
title: "AC Mains Frequency Measurement using STM32"
layout: single
collection: projects
---

## 🔍 Overview
Designed and implemented a system to measure AC mains frequency using an STM32 microcontroller with proper electrical isolation.  
The system safely converts AC signals into digital pulses and uses timer input capture to compute frequency in real time.

---

## ⚙️ Key Features
- Optocoupler-based isolation for safe AC interfacing  
- Timer input capture for precise frequency measurement  
- Real-time frequency display on 16x2 LCD  
- Noise-resistant signal conditioning  
- Reliable operation for 50 Hz mains  

---

## 🧠 Working Principle
- AC mains signal is stepped down and passed through an optocoupler  
- The optocoupler generates a digital pulse corresponding to AC zero-crossing  
- STM32 timer captures the time between pulses  
- Frequency is calculated using timer difference  

---

## 🧩 Hardware Used
- STM32G431CBT6 Microcontroller  
- PC817 Optocoupler  
- Resistors and capacitors (signal conditioning)  
- 16x2 LCD Display  

---

## 🛠 Tools & Software
- Embedded C  
- STM32CubeIDE  
- PCB Design (Altium / KiCad)  

---

## 💡 My Contributions
- Designed isolation and signal conditioning circuit  
- Configured STM32 timer in input capture mode  
- Implemented LCD interface without external libraries  
- Ensured accurate and stable frequency computation  

---

## 🔌 Circuit & PCB

### Schematic
![Schematic](/assets/images/ac-frequency/schematic.png)

### PCB Design
![PCB](/assets/images/ac-frequency/pcb.png)

---

## 📊 Results

### Output / Display
![Output](/assets/images/ac-frequency/output.jpg)

### Hardware Setup
![Setup](/assets/images/ac-frequency/setup.jpg)

- Achieved accurate measurement of AC mains frequency (~50 Hz)  
- Stable readings with minimal noise interference  
- Safe operation ensured through electrical isolation  

---

## 📂 Downloads (Optional)
- [Schematic File](#)
- [PCB Layout](#)
- [Gerber Files](#)
