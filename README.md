# AHG HeRo Lab Vibration Motor PCB

A custom 2-layer PCB developed at the AHG HeRo Lab to enable precise limb tracking and haptic feedback for low-cost physical therapy systems.

## Hardware Overview
- **MCU:** Seeed Studio XIAO-ESP32 (BLE-enabled)
- **Sensors:** BNO055 9-DoF IMU (I²C)
- **Haptics:** Custom motor driver circuit for vibration/haptic motors
- **Components:** 15+ discrete parts selected for MCU–motor interfacing
- **PCB:** 2-layer KiCAD design, fully hand-soldered and tested

## Key Features
- IMU-based limb tracking with onboard sensor fusion
- Low-latency I²C communication with the BNO055
- Reliable haptic feedback through a custom motor circuitry
- Compact form factor suitable for wearable PT applications

## Firmware Summary
- I²C driver for BNO055 data acquisition
- BLE data transmission via ESP32-C3 module

<img width="1487" height="936" alt="image" src="https://github.com/user-attachments/assets/8a6024a8-83ad-4578-922c-d9ba611f16fc" />
