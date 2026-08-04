# Firmware

## Overview

The firmware for the Hybrid Renewable Energy System is developed using the **Arduino IDE** and runs on the **ESP32 Development Board**. It is responsible for monitoring electrical parameters, controlling system components, and hosting the IoT Energy Dashboard.

---

## Functions of the Firmware

The firmware performs the following tasks:

- Reads voltage using the Voltage Sensor (Voltage Divider).
- Reads current using the ACS712 Hall-Effect Current Sensor.
- Calculates real-time power output.
- Monitors battery voltage.
- Controls the 12V DC Cooling Fan using the L298N Motor Driver.
- Hosts a Wi-Fi-based Energy Dashboard.
- Continuously updates voltage, current, and power values.

---

## Development Environment

| Software | Version |
|----------|---------|
| Arduino IDE | 2.x or later |
| ESP32 Board Package | Latest Stable Version |

---

## Required Libraries

- WiFi.h
- WebServer.h
- ACS712 Library
- Arduino.h

---

## Firmware Flow

```text
Start System
      │
      ▼
Initialize ESP32
      │
      ▼
Read Voltage Sensor
      │
      ▼
Read Current Sensor
      │
      ▼
Calculate Power
      │
      ▼
Check Voltage Threshold
      │
      ├─────────────► Turn Cooling Fan ON
      │
      ▼
Update IoT Dashboard
      │
      ▼
Repeat
```

---

## Upload Instructions

1. Install the Arduino IDE.
2. Install the ESP32 Board Package.
3. Connect the ESP32 board using a USB cable.
4. Open the project `.ino` file.
5. Select the correct COM port and ESP32 board.
6. Click **Upload**.
7. Open the Serial Monitor to verify the readings.
8. Connect to the ESP32 Wi-Fi network and open the Energy Dashboard in a web browser.

---

## Firmware Features

- Real-time Voltage Monitoring
- Real-time Current Monitoring
- Power Calculation
- Automatic Cooling Fan Control
- Battery Monitoring
- Wi-Fi-Based IoT Dashboard
- Stable Continuous Operation

---

## Source Code

The complete ESP32 source code is available in this folder as:

```text
Hybrid_Renewable_Energy_System.ino
```
