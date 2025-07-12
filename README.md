# ESP32 Smartwatch Firmware (ESP-IDF)

This repository contains firmware for a custom smartwatch project built using the ESP32-S3 and developed with the ESP-IDF framework. The goal is to create a feature-complete, low-power wearable device with a responsive UI and expandable sensor/peripheral support — a foundation for a production-ready smartwatch platform.

## Project Overview

This project runs on the [Waveshare ESP32-S3 1.28" Round LCD Dev Board](https://www.waveshare.com/wiki/ESP32-S3-Touch-LCD-1.28), which integrates:
- **ESP32-S3R2** SoC
- **GC9A01 240×240 round LCD**
- **CST816S capacitive touch controller**
- **QMI8658 6-axis IMU**
- **Battery management and charging circuit**

All firmware is written in **C using ESP-IDF**, with **LVGL** used for display rendering and UI.

## Features

- Real-time clock display
- Page-swiping UI using capacitive touch input
- Compass feature using QMI8658 IMU 
- Stopwatch feature 
- Sleep mode with display timeout
- Wake gesture detection via IMU

## Future Hardware Plans

This project is currently developed on a dev board, but the long-term roadmap includes:
- **Custom 3D-printed watch casing**  
  Designed to make the dev board wearable like a commercial smartwatch.
- **Custom PCB Bring-Up**  
  A fully custom smartwatch PCB designed to:
  - Match mechanical constraints of the printed case (or design a new case if necessary)
  - Include additional peripherals (e.g., haptic motor, pulse sensor, BLE co-processor, etc.)

## Open Source Usage

This project is open-source and intended to be shared, modified, and built upon — including full hardware and enclosure design in the future. You're welcome to flash your own version, print a custom case, or fork the firmware.

This project is licensed under the MIT License. See the [LICENSE](./LICENSE.md) file for details.
