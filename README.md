
# Automated Pill Sorting by Color Using a Robotic Arm

## Overview

The Automated Pill Sorting System is a robotics-based prototype designed to identify and sort pills according to their colors. The system aims to demonstrate how automation can assist in organizing medication through color-based detection and robotic manipulation.

Using a TCS34725 RGB color sensor, the system detects the color of a pill and processes the readings through an Arduino Uno. A robotic arm controlled by servo motors and a PCA9685 servo driver then picks up the pill and transfers it to its corresponding sorting container.

The project integrates color recognition, robotic movement, and automated sorting to demonstrate the potential application of robotics in pharmaceutical organization.

## Project Images

![Robotic arm color sorting system - view 1](Images/ROBARM1.jpg)

![Robotic arm color sorting system - view 2](Images/ROBARM2.jpg)

![Robotic arm color sorting system - view 3](Images/ROBARM3.jpg)

## Objectives

- Develop an automated pill sorting system based on color recognition.
- Detect pill colors using an RGB color sensor.
- Control robotic arm movements through programmed servo sequences.
- Automatically transfer pills into their corresponding containers.
- Demonstrate the integration of robotics, sensors, and embedded systems.

## Main Components

- Arduino Uno
- TCS34725 RGB Color Sensor
- PCA9685 16-Channel PWM Servo Driver
- Servo Motors
- Robotic Arm Structure
- Gripper Mechanism
- LCD I2C Display
- External Power Supply

## Technologies Used

- Arduino IDE
- Embedded C++
- TCS34725 Color Detection
- PCA9685 Servo Control
- I2C Communication
- Robotics and Automation

## Key Features

- Automatic pill color detection
- RGB-based color identification
- Robotic arm movement control
- Automated pill picking and placement
- Color-based pill sorting
- LCD display for system feedback

## System Operation

1. A pill is positioned within the color sensor's detection area.
2. The TCS34725 sensor reads the pill's RGB color values.
3. The Arduino processes the sensor readings and determines the detected color.
4. The robotic arm moves toward the pill.
5. The gripper picks up the pill.
6. The arm transfers the pill to its designated color container.
7. The gripper releases the pill, completing the sorting process.


## Development Status

Prototype developed. The project involves RGB color detection, servo motor coordination, and automated robotic arm movements for color-based pill sorting.

## Application

The project demonstrates the potential use of robotics and automation in pharmaceutical organization, particularly in sorting medication according to visual characteristics.

## Limitations

- Sorting is based on pill color rather than medication identity.
- The system does not verify pill composition, dosage, or authenticity.
- Different lighting conditions and pill surfaces may affect color detection.
- The prototype is intended for educational and demonstration purposes, not actual pharmaceutical dispensing.

## Development Status
Prototype developed. The project includes color detection and coordinated servo movement programming for automated object sorting.

## Application
The system demonstrates the use of robotics and automation in sorting applications, particularly in basic industrial material handling.

## Project Developers 
Del Rosario, Joab Yitshaq Q.
Godalle Abegail T.
Jovellanos, Jericho Michael D.
Lucero, Mie Haina R.
Olea, Angelo Alexis S.
Tumazar, Bryan C,
Velasco, Peter Jayson 
Villanueva, Jan Patrick