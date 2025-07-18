# STP - Smart Time Piece

STP (Smart Time Piece) is an open-source ESP32-based smartwatch firmware and hardware platform.  
This repository contains the firmware for STP, developed using ESP-IDF for the ESP32-S3 SoC, designed to provide a low-power, feature-rich wearable with a modern UI and expandability.

---

## Project Status

STP is under active development and evolves through iterative versions.  
Each iteration will add new and improved features in hardware/software.  
This README will be updated as the project grows.  

---

## Iteration History

### V1 

- Basic time display with ESP32 RTC and NTP synchronization  
- Touch-based page-swiping UI using LVGL  
- Compass using QMI8658 6-axis IMU  
- Stopwatch functionality  
- Display timeout with light sleep power management  
- Wake gesture detection via IMU  

### V2 (Future Plans)

- Deep sleep mode with RTC wake-up support  
- Expanded sensor suite (e.g., heart rate monitor, environmental sensors)   
- Enhanced UI with settings and customization  
- Custom PCB support  


---

## Hardware Platform

This firmware currently runs on the [Waveshare ESP32-S3 1.28" Round LCD Dev Board](https://www.waveshare.com/wiki/ESP32-S3-Touch-LCD-1.28), which features:

- ESP32-S3R2 System on Chip  
- GC9A01 240×240 round LCD display  
- CST816S capacitive touch controller  
- QMI8658 6-axis IMU sensor  
- Battery management and charging circuitry

Long-term plans include designing a custom PCB and 3D-printed watch casing to create a fully integrated smartwatch.

---

## Repository Structure
- `/V1/` # Firmware and resources for V1 iteration
- `/V2/` # Firmware and resources for V2 iteration
- `/docs/`# 3D design files, PCB design files, and other resources
- `/LICENSE.md` # License file
- `/README.md` # This master README

---

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE.md) for details.
