# IMU Based Air Mouse System

This project implements an **Air Mouse** using an **IMU sensor and microcontroller** to control the computer cursor through hand movements. The system interprets motion data from the IMU and converts it into cursor movements, enabling users to interact with a computer without a physical mouse.

## Overview

The Air Mouse works by reading orientation and motion data from an **Inertial Measurement Unit (IMU)**. The motion data is processed and translated into cursor movement commands that are sent to the computer. By moving the device in the air, the user can control the cursor on the screen.

## Features

- Cursor control using hand gestures
- Real-time motion tracking
- IMU-based orientation and movement detection
- Wireless or serial communication with computer
- Low-cost hardware implementation

## Hardware Used

- Microcontroller (e.g., ESP32)
- IMU Sensor (e.g., MPU6050 / MPU9250)
- USB or wireless communication interface
- Power source (battery or USB)

## Working Principle

1. The IMU measures acceleration and angular velocity.
2. The microcontroller reads sensor data in real time.
3. Motion data is filtered and processed to estimate movement.
4. The processed data is mapped to cursor movement.
5. The cursor is moved on the computer accordingly.

## Applications

- Human-computer interaction
- Presentation control
- Smart classrooms
- Accessibility devices
- Gesture-based interfaces

## Repository Contents

- Sensor interfacing code
- Motion processing algorithms
- Cursor control implementation
- Supporting scripts and utilities

## Future Improvements

- Gesture recognition (click, scroll, drag)
- Improved filtering and drift correction
- Wireless communication
- Machine learning based motion classification

