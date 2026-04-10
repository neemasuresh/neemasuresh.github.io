---
title: "FPGA-Based Signal Conditioning using FIR LPF"
layout: single
collection: projects
---

## 🔍 Overview
Designed and implemented an **FPGA-based FIR Low-Pass Filter (LPF)** for real-time signal conditioning.  
The system efficiently filters input signals using a hardware-based architecture, enabling high-speed and reliable digital signal processing.

---

## ⚙️ Key Features
- Real-time FIR filtering using FPGA  
- Parallel processing for high-speed operation  
- Efficient hardware implementation using Verilog  
- Stable and reliable signal conditioning  
- Suitable for embedded DSP applications  

---

## 🧠 Working Principle
- Input signal is applied to the FPGA  
- Previous samples are stored using a shift register  
- Each sample is multiplied with predefined FIR coefficients  
- Multiply-Accumulate (MAC) operation produces filtered output  
- High-frequency noise components are attenuated  

---

## 🧩 Hardware Used
- Intel/Altera Cyclone 10 LP FPGA (T20Q144I4)  
- Supporting passive components for signal interfacing  

---

## 🛠 Tools & Software
- Verilog HDL  
- Efinity / Quartus Prime  
- GTKWave (for simulation)  
- PCB Design (Altium / KiCad)  

---

## 💡 My Contributions
- Designed FIR filter architecture in Verilog  
- Implemented shift register and MAC-based filtering  
- Simulated and verified filter performance  
- Optimized design for efficient FPGA utilization  
- Designed PCB for FPGA-based implementation (if applicable)  
- Tested and validated real-time filtering  

---

## 🔌 Circuit & Hardware

### FPGA Board 
### PCB
![FPGA Board](/assets/images/firlp/firlppcb.png)
### Schematic


![FPGA Board](/assets/images/firlp/DigitalBoard_page-0003.jpg)
![FPGA Board](/assets/images/firlp/DigitalBoard_page-0004.jpg)
![FPGA Board](/assets/images/firlp/DigitalBoard_page-0001.jpg)
![FPGA Board](/assets/images/firlp/DigitalBoard_page-0002.jpg)
---

## 📊 Results

### Simulation Output
![Waveform](/assets/images/firlp/lpoutresponse.jpg)

- Successfully attenuated high-frequency noise  
- Output matches expected low-pass filter behavior  
- Stable real-time operation achieved  

---

## 📎 Downloads
- 📥 [Verilog Source Code](./verilog/)
- 📥 [Simulation Files](./simulation/)
- 📥 [PCB Design](./pcb/)

---

## 🏁 Conclusion
This project demonstrates an efficient **FPGA-based digital filtering system**, showcasing the advantages of hardware acceleration for real-time signal processing applications.
