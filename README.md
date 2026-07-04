# LED-Brightness-Control-Using-Potentiometer.
## 🔆 LED Brightness Control Using Potentiometer  This project is used to control the brightness of an LED using a potentiometer. By rotating the potentiometer, the input voltage changes and the microcontroller adjusts the LED brightness using PWM. The LED becomes brighter or dimmer based on the position of the knob.
# LED Brightness Control Using Potentiometer

## Overview
This project demonstrates how to control the brightness of an LED using a potentiometer and an Arduino Uno. The potentiometer acts as an analog input device, allowing the user to adjust the LED brightness smoothly. The Arduino reads the potentiometer value and generates a PWM (Pulse Width Modulation) signal to control the LED intensity.

## Features
- Real-time LED brightness control
- Smooth brightness adjustment using PWM
- Simple and beginner-friendly Arduino project
- Demonstrates analog input and PWM output

## Components Required
- Arduino Uno
- LED
- 220 Ω Resistor
- 10 kΩ Potentiometer
- Breadboard
- Jumper Wires
- USB Cable

## Circuit Connections

### Potentiometer
- Left Pin → 5V
- Middle Pin → A0
- Right Pin → GND

### LED
- Anode (+) → Arduino Pin 9 (through 220 Ω resistor)
- Cathode (-) → GND

## Working Principle
The potentiometer provides a variable analog voltage to the Arduino. The Arduino reads this value using the analog input pin (A0) and maps it to a PWM value (0–255). The PWM signal is then sent to the LED connected to Pin 9, allowing the LED brightness to increase or decrease smoothly as the potentiometer is rotated.

## Applications
- LED dimmer systems
- Home lighting control
- User-controlled brightness adjustment
- PWM demonstration projects
- Arduino learning and educational projects

## Technologies Used
- Arduino IDE
- Embedded C/C++
- PWM (Pulse Width Modulation)
- Analog Input


---
⭐ If you found this project helpful, consider giving it a Star on GitHub!
