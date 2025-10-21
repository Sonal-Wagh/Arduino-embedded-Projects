# Overview

This repository contains two embedded systems projects implemented using Arduino and simulated on Tinkercad.
Both tasks are designed to demonstrate the use of sensors, actuators, and microcontroller-based logic for automation and access control.

# Project 1: Smart Lock System (Keypad, LCD, Servo Motor, Buzzer)
**1.Objective**

To develop a digital lock system using an Arduino-controlled keypad, LCD screen, and servo motor, with an added buzzer for incorrect attempts and a password reset feature.

**2.Key Features**

a.Keypad Input: Allows user to enter a secure password.

b.LCD Display: Provides feedback on input and system state (e.g., “Enter Password”, “Access Granted”, “Access Denied”).

c.Servo Motor: Acts as the physical lock mechanism.

d.Buzzer: Emits a sound for each incorrect password attempt.

e.Password Reset: Entering "####" triggers a password reset after verifying the current password.

**3.Working Principle**

User enters the password through the keypad.

a.If correct, the servo unlocks (rotates).

b.If incorrect, the buzzer sounds, and access is denied.

c.If "####" is entered, the system enters reset mode, allowing the user to set a new password after verification.

**4.Components Used**

Arduino Uno

4x4 Keypad

16x2 LCD Display

Servo Motor

Buzzer

Jumper Wires & Breadboard

# Project 2: People Counter using PIR Sensors
**1.Objective**

To design a system capable of monitoring and displaying the number of people entering or leaving a room using PIR sensors and an LCD display.

**2.Key Features**

a.Bidirectional Counting: Accurately detects entry and exit using two PIR sensors.

b.LCD Display: Continuously displays the current count of individuals in the room.

c.Automatic Adjustment: Increments or decrements count based on motion sequence.

**3.Working Principle**

a.PIR Sensor 1 detects motion at the entrance → person entering.

b.PIR Sensor 2 detects motion at the exit → person leaving.

c.The system updates the count accordingly and displays it on the LCD.

**4.Components Used**

Arduino Uno

2x PIR Motion Sensors

16x2 LCD Display

Jumper Wires & Breadboard

**Simulation**
Both projects were created and tested using Tinkercad Circuits
You can open the provided links in the repository to view and simulate the circuits.
