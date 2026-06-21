# Line Following Robot

## Overview
A Line Following Robot (LFR) that follows a predefined path using an IR sensor array. The robot continuously detects the line and adjusts its movement accordingly. An ultrasonic sensor is also used for obstacle detection.

## Components Used
- Arduino Uno
- L298N Motor Driver
- IR Sensor Array (5 Sensors)
- Ultrasonic Sensor (HC-SR04)
- DC Motors (2x)
- Robot Chassis
- Caster Wheel
- Battery Pack
- Switch
- Jumper Wires
- Breadboard

## Features
- Automatic line tracking
- Obstacle detection using ultrasonic sensor
- Differential motor control
- Real-time path correction

## Working Principle
The IR sensor array detects the position of the line beneath the robot. Based on sensor readings, the Arduino controls the motors through the L298N motor driver to keep the robot on the path. The ultrasonic sensor detects obstacles and helps prevent collisions.


## Author
Samreen Mughal
