# Analog-Neural-Networks-for-Electric-Vehicles
# Description: A brain-inspired, low-power Battery Management System that uses analog neurons for real-time SoC estimation, fault detection, adaptive charging, and Vehicle-to-Grid (V2G) interaction. Eliminates heavy digital processors, enabling faster, safer, and energy-efficient battery control for Electric Vehicles.

# 📌 Project Overview

This project proposes a sensorless, low-power Analog Neural Network (ANN) to improve the battery management system (BMS) in Electric Vehicles. Inspired by the human brain’s decentralized decision-making, the system uses analog neurons for real-time, autonomous battery monitoring and control — eliminating the heavy reliance on digital processors and sensors.

The prototype focuses on developing the Intelligent Battery Management Neuron (IBMN), which handles:

# ⚡ State of Charge (SoC) detection

# 🧠 RC memory-based learning (user-specific charging/discharging habits)

# 🔧 Fault detection & self-healing

# 🌡️ Thermal monitoring & adaptive charging control

# 🔌 Vehicle-to-Grid (V2G) interaction


# 🎯 Objectives

Develop an Analog Neural Network–based BMS capable of low-power, real-time operation.

Achieve autonomous SoC estimation without conventional digital sensors.

Implement self-healing mechanisms for faults and anomalies.

Integrate analog RC memory circuits to learn user driving/charging behavior.

Enable predictive charging and grid communication (V2G).

Enhance battery safety, adaptability, and efficiency while reducing cost and complexity.

# 🛠️ Hardware Components

Lithium-Ion Batteries (11.1V, 2000mAh)

LM358 (dual op-amp)

ADS1115 (16-bit ADC)

DS18B20 (temperature sensor)

DS3231 (Real-Time Clock)

ESP32 Microcontroller

16x2 I2C LCD

Bidirectional Logic Level Shifter

# 🖥️ Software Components

Arduino IDE (firmware development)

LTSpice (circuit simulation)

SQL Database (logging SoC, charging history, thermal logs)

Mobile App – “Trash Master” for:

Real-time SoC & temperature updates

Fault alerts & driving behavior insights

Grid charging interaction

# 🔬 Methodology

SoC Detection Neuron – Analog voltage mapping via LM358 + ADS1115.

RC Memory Neuron – Learns user’s charging/discharging behavior.

Fault Detection & Healing – Thermal and current monitoring with reflexive response.

RTC Module – Time-based charging and grid scheduling.

Mobile App – Cloud database sync for user monitoring and V2G interaction.

# 📊 Results

SoC estimation accuracy within ±3% error margin.

RC memory neuron successfully retained charging/discharging patterns.

Fault detection reacted instantly to temperature rise (>45°C).

V2G functionality validated with simulated grid communication.

Prototype demonstrated fast, low-power decision-making compared to digital BMS.

# 🚀 Future Scope

Expand ANN with additional neurons (torque distribution, regenerative braking, cruise control).

Develop more advanced analog memory circuits.

Integrate real-time grid pricing for tariff-aware charging.

Miniaturize into System-on-Chip (SoC) or neuromorphic BMS module for commercial EVs.

# 🏆 Achievements

Prototype validated through bench testing & LTSpice simulations.

Conference paper published based on this work.

Demonstrated brain-inspired, sustainable battery management with faster decisions, lower power, and higher safety.
