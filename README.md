# Smart Equipment Diagnostic Circuit

## Project Overview
An Arduino-based system designed to monitor the condition of an industrial electric motor and detect abnormal operating conditions.

## Problem Statement
Industrial motors can develop faults such as overheating, excessive vibration and overcurrent. If these problems are not detected early, they can cause equipment damage, unexpected breakdowns, production losses and higher maintenance costs.

## Parameters Monitored
- Temperature: TMP36 sensor
- Current: Potentiometer-based simulation
- Vibration: Potentiometer-based simulation

## Components Used
- Arduino Uno
- TMP36 temperature sensor
- 3 potentiometers
- 16x2 LCD
- Green, yellow and red LEDs
- Piezo buzzer
- Resistors
- Breadboard and jumper wires

## Working Principle
Sensor inputs are read by the Arduino and compared with predefined thresholds. The system displays readings and equipment status on the LCD and activates LEDs and a buzzer when abnormal conditions are detected.

## Software and Tools
- Arduino C++
- Tinkercad Circuits

## Project Limitations
Current and vibration are simulated using potentiometers. Physical industrial motor testing has not been implemented.

## Simulation
Tinkercad Circuit Link: https://www.tinkercad.com/things/5ku6JFVlJXK-smart-equipment-diagnostic-circuit
Website link: http://localhost:5174/
