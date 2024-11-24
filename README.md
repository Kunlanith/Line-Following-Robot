# STM32 Line Following Robot

## Overview
A line-following robot designed using the STM32 microcontroller for advanced processing capabilities. The robot demonstrates high precision in tracking a line and adapting to changes in the path using a robust PID control algorithm.

## Key Features
- **PID Control** for stability and accuracy.
- 8 IR sensors for precise path detection.
- STM32 microcontroller for real-time adjustments and control.

## Design
### Hardware Components:
- **Microcontroller**: STM32F411RE.
- **Motor Driver**: DRV8833.
- **Sensors**: Infrared Phototransistors.
- **Power Supply**: GNB5502S70A 2S 7.4V LiPo Battery.

### Software:
- PID control algorithm for processing sensor feedback and controlling motor outputs.

## Methodology
1. **Sensor Calibration**:
   - Calibrates minimum and maximum sensor values for effective path tracking.
2. **PID Implementation**:
   - Calculates error values and adjusts motor speeds accordingly.
3. **Real-Time Adjustments**:
   - Uses continuous feedback to adapt to path deviations.

## Results
- The robot successfully followed predefined tracks with consistent accuracy.
- Track A was completed in **29 seconds**, and Track B in **1.48 minutes**.

## Video Demonstration
[![STM32 Line Following Robot](https://img.youtube.com/vi/5bt6mWPSz7Y/0.jpg)](https://youtu.be/5bt6mWPSz7Y?si=nBkfKjXfFc0q5WnF)

## Team Members
- **Kunlanith Busabong**
- **Napat Chuenyoo**
- **Thitiwut Saowanai**

## Future Work
- Optimizing power consumption for extended operation.
- Enhancing algorithm adaptability for various track environments.
