# Hospital Healthcare – Emergency Alert System  
### Using Contiki OS & COOJA Simulator

---

## Overview
This project implements a **real-time emergency healthcare alert system** using **Contiki OS** and the **COOJA network simulator**. It simulates a **Wireless Sensor Network (WSN)** for continuous patient health monitoring, where sensor nodes detect abnormal vital signs and immediately alert a central **sink node**.

The system is designed to be **lightweight, energy-efficient, and responsive**, making it suitable for **IoT-based smart healthcare applications**.

---

## Objectives
- Simulate continuous monitoring of patient health parameters  
- Detect abnormal or critical health conditions using predefined thresholds  
- Classify alerts based on severity (**MODERATE / CRITICAL**)  
- Transmit alerts reliably to a sink node using **UDP communication**  
- Demonstrate efficient operation in **low-power IoT environments**

---

## System Architecture
The system consists of the following components:

- **Alert Nodes**  
  Simulated patient nodes that monitor vital parameters and generate alerts  

- **Sink Node**  
  Central node that receives alerts and triggers visual indications (LED)  

- **COOJA Simulator**  
  Used to visualize, test, and validate network behavior  

- **Contiki OS**  
  Event-driven operating system optimized for low-power IoT devices  

---

## Monitored Health Parameters
- Body Temperature  
- Heart Rate  
- Blood Pressure  
- Respiratory Rate  
- SpO₂ (Oxygen Saturation)  

Each parameter is continuously compared against **medically defined threshold values**.

---

## Technologies Used
- **Contiki OS (v3.x)**  
- **COOJA Network Simulator**  
- **C Programming Language**  
- **UDP Multicast Communication**  
- **RPL Routing Protocol**  
- **ContikiMAC** (Low-power MAC protocol)  
- **Sky Motes** (Simulated hardware)

---

## Simulation Setup
- **Alert Nodes:** 5–6  
- **Sink Nodes:** 1  
- **Communication Protocol:** UDP  
- **Simulation Duration:** 300–600 seconds  
- **Environment:** Ubuntu (native or Docker-based)

---

## Results
- **Alert Success Rate:** ~98%  
- **Average Alert Latency:** ~1.2 seconds  
- **Energy Efficiency:** Low power consumption using duty cycling  
- **Reliability:** Consistent packet delivery within sink node range  

These results validate the system’s **reliability** and **suitability for real-time healthcare monitoring**.

---

## Applications
- Remote patient monitoring  
- Elderly care systems  
- Post-operative monitoring  
- Emergency detection in hospitals  
- Smart healthcare IoT infrastructures  

---
