# ESP32 Smart WiFi & Bluetooth Control System

A Smart RF Monitoring System built using ESP32 that scans for nearby WiFi and Bluetooth devices and disables wireless modules locally when signals are detected. This project is designed for educational purposes and demonstrates basic RF monitoring and control.

---

## Features

- WiFi network scanning (SSID, RSSI, Channel)
- Bluetooth device scanning (BLE)
- Automatic periodic scanning
- Local WiFi disable on detection
- Local Bluetooth disable on detection
- Serial Monitor output for real-time monitoring
- Low memory cleanup after each scan

---

## Hardware Required

- ESP32 Development Board
- USB Cable
- Computer with Arduino IDE

---

## Software Requirements

- Arduino IDE
- ESP32 Board Package
- Libraries:
  - WiFi (built-in)
  - BLEDevice
  - BLEUtils
  - BLEScan

Install ESP32 boards:
