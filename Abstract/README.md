# Abstract

## Project Overview

This project presents the design and testing of a **Hybrid Renewable Energy System** that combines a **3 W Solar Photovoltaic (PV) panel** and **Micro-Algae Bio-Electrochemical Cells (BECC)** to provide continuous, low-cost, and monitorable power generation.

The micro-algae bio-cell consists of **copper** and **zinc electrodes** immersed in an algae-containing aquatic solution. Through photosynthetic and electrochemical redox reactions, the bio-cell generates an electromotive force of approximately **0.01–0.02 V**.

The generated voltage is amplified using a **DC-DC Boost Converter** and a **5 V Step-Up Module**, allowing the system to charge a **3-cell, 11.1 V Lithium-Ion battery pack**. The solar PV panel provides additional current for faster battery charging.

An **ESP32 microcontroller** measures voltage and current in real time using a voltage divider and an **ACS712 Hall-effect current sensor**. It calculates the output power, controls a cooling fan through an **L298N motor driver**, and hosts a **Wi-Fi-based Energy Dashboard** for remote monitoring.

## Experimental Results

During laboratory testing, the prototype achieved:

- **Voltage:** 2.54 V
- **Current:** 1.52 A
- **Power:** 3.85 W

These results demonstrate stable operation of the hybrid renewable energy system.

## Conclusion

The proposed prototype successfully combines biological and photovoltaic energy harvesting with IoT-based monitoring, making it suitable for research, education, and small-scale off-grid renewable energy applications.
