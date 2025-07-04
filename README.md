# Verilog Projects – Digital Clock & Automated Car Parking System 🚦⏰

This repository contains two beginner-to-intermediate level Verilog HDL projects developed as part of my project work at IIT Kanpur. The designs were implemented and simulated using **Vivado** and **GTKWave**.

---

## 🚀 Projects Overview

### 1. Digital Clock ⏰
A modular Verilog-based digital clock that tracks time in hours, minutes, and seconds in real-time.

**Features:**
- Time tracking using counters for seconds, minutes, and hours
- Reset and pause functionalities
- 24-hour format display
- Synchronous design using clock division
- Testbench included for simulation validation

**Modules:**
- Clock Divider
- Seconds Counter
- Minutes Counter
- Hours Counter
- Top Module to integrate all counters

---

### 2. Automated Car Parking System 🚗
A Verilog model that simulates an automated parking system with sensor-based entry and exit logic.

**Features:**
- Dynamic parking slot allocation
- Entry/Exit gate control using FSMs
- Slot counter and availability tracking
- LED-style indicators (simulated via output registers)
- Easily extendable to more slots or multi-level systems

**Modules:**
- Entry Sensor Logic
- Exit Sensor Logic
- Slot Availability Counter
- FSM for Gate Control

---

## 🛠️ Tools & Technologies

- **Language:** Verilog HDL
- **Simulation:** GTKWave
- **Synthesis:** Xilinx Vivado
---
