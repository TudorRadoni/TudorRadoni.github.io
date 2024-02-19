---
title: Arduccelerometer
publishDate: 2020-12-7 22:22:22
img: /assets/work/arduccelerometer.png
img_alt: A picture of the arduccelerometer project on a breadboard
description: |
  Arduccelerometer is currently used to monitor the acceleration of a car. The project is built in a way that leaves room for adjustment for any car, making it easy to modify in order to make it work regardless of the power that the platform is capable of.
tags:
  - Arduino
  - Embedded Systems
  - Electronics
  - C/C++
  - Accelerometer
  - Display
---

Accelerometer with graphical display, based on Arduino.

Arduccelerometer is a versatile project which can be used in many scenarios, but I have chosen to exemplify its capabilities in the context of cars. Thanks to the use of a display, the Arduino board takes values from the standalone accelerometer and prints the values to the screen in an intuitive way, making it easy to monitor while driving.

## Project description

The aim of this project is to show the acceleration of the car. The way the project is built leaves room for adjustment for any car, making it easy to modify in order to make it work regardless of the power that the platform is capable of.
For this project, the following components were used:

- Arduino Pro Micro development board
- Adafruit MPU6050 6-DoF Accelerometer and Gyroscope
- Adafruit SSD1306 128x64 OLED Display
