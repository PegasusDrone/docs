---
title: Pre-Flight Checklist
order: 5
pcx-content-type: best-practices
---

# Pegasus Checklist

## Pre-Departure

- Batteries:
  - 6S Lipo Charged at ~ 23.0 V
  - (2) 2S Li-Ion Battery Charged at ~ 7.0 V
- GoPro:
  - Charged, free memory
- Pixhawk
  - Free Memory Card
  - All flight modes set as desired (and memorized)
- Pegasus Drone Kit
- Laptop
  - With Qgroundcontrol installed and pegasus-DDS working
- Backup Props

## Pre-Flight

- Don't Connect Lipo Battery to drone
- Connect Pixhawk to laptop and check calibration and modes, look for any errors. The top bar should be green and display ready for flight.
- Connect to Xavier and start your nodes (see offboard instructions for details)
- Ensure publishing frequency set to Qos Standards
- Check LIPO battery voltage
- Make sure the transmitter is in disarmed mode.
- Extend Pegasus arms, check all connections, if unsure, do a continuity test using a multimeter.
- Make sure all nuts and bolts are tight, especially of the propellers.
- connect the battery and wait for the green LED in GPS
- Ensure GPS status is good on Qgroundcontrol
- Remove the USB cable from the laptop
- Place drone at a safe distance from your position (ideally 1 - 1.5 meters)
- Start recording device if required.
- Arm the drone, and press the emergency kill switch, to ensure it works.
- Reset the emergency switch, disarm the drone.

## Flight

- Set Position mode and arm the drone.
- Once in a stable position set offboard mode.
- Set position mode, then set land mode
- Disarm the drone and remove the battery


> Author: [Mihir Patel](https://github.com/mihyr)