# Problem Statement

## Overview

The growing demand for electricity and the increasing environmental impact of fossil fuels have created a need for clean, sustainable, and renewable energy sources. Solar energy is one of the most widely used renewable resources, but its power generation depends entirely on the availability of sunlight. During cloudy weather and nighttime, solar panels cannot generate sufficient electricity.

Micro-Algae Bio-Electrochemical Cells (BECC) are an emerging renewable energy technology capable of generating electricity through biological and electrochemical reactions. However, the electrical output from algae cells is extremely low (approximately **0.01–0.02 V**), making it unsuitable for direct use in practical applications.

## Existing Challenges

- Solar power generation is limited to daylight hours.
- Micro-algae bio-cells produce very low voltage and current.
- Low-voltage output cannot directly power electronic devices.
- Most renewable energy systems lack real-time monitoring capabilities.
- Efficient integration of multiple renewable energy sources remains a challenge.
- Many existing solutions are expensive and difficult to deploy for educational and research purposes.

## Proposed Solution

This project develops a **Hybrid Renewable Energy System** by integrating a **3 W Solar Photovoltaic (PV) panel** with a **Micro-Algae Bio-Electrochemical Cell (BECC)**.

The generated energy is amplified using a **DC-DC Boost Converter** and a **5 V Step-Up Module**, stored in an **11.1 V Lithium-Ion battery**, and monitored using an **ESP32 microcontroller**. The ESP32 measures voltage, current, and power in real time, automatically controls a cooling fan when required, and provides remote monitoring through a Wi-Fi-based IoT dashboard.

## Objective

The objective of this project is to design and implement a low-cost, environmentally friendly, and IoT-enabled hybrid renewable energy system that improves energy availability, enables efficient monitoring, and demonstrates the practical integration of solar and algae-based power generation for research, education, and small-scale off-grid applications.
