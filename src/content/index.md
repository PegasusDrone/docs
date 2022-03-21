---
title: Overview
order: 0
pcx-content-type: landing-page
---

# Pegasus Drone

## Overview

Pegasus is a px4 based enterprise grade 4G drone build from the ground up. Equipped with an onboard Xavier Nx system, a Zed stereo Camera, redundant lidars (range finders), Pegasus is a ROS2 based drone capable of flying autonomously and creating 3D stereo-based maps of the environment.
The LTE module allows live streaming of the drone's stereo data to a remote server for large scale spatial mapping performed in real time.

A FastDDS based AES encripted pipeline was setup to stream the data to the server. Apart from remote DDS streaming, the onboard xavier system also uses FastDDS for sending uORB messages to the pixhawk flight controller (an alternative to mavlink).

## What sets Pegasus apart?

The hardware stack is open, configurable and costs about one third compared to enterprise grade drones with similar features like DJI Matrice 300RTK. Any hardware damage can be easily replaced at minimal cost.
This makes it best suited for research, especially in Aerial robotics, where flight crash while developing autonomy software stacks are frequent.

## Navigation

- Hardware
  - CAD Design
  - Hardware components BOM and selection
  - Sensor & actuators selection
  - TX16s transmitter specifics
- Electronics
  - Drone Schematic
  - Custom PCB schematic
  - Altium PCB layout
- DDS
  - DDS setup
- Stereo
  - Visual Inertial Odometry
  - Visual Slam / Spatial Mapping
- Instructions
  - Steps for RPi Cross compilation
  - Steps to setup Xavier Nx on the drone
  - Px4 DDS setup
  - Flight Routine setup (offboard mode)
  - Pre-Flight Checklist
- Medusa Drone
  - Hardware
  - Schematic / Wiring
  - CAD

![](outdoor.jpg)
![](pegasus.jpg)

<Aside type="warning" header="Pages To-Do">

- CAD Files and 3D printed parts Page
- Schematic Files Page
- Steps to setup Xavier NX
- Steps for RPi cross Compilation
- Steps to setup TS16s Transmitter
- Steps to update X8R Receiver Firmware
- References (Links)

</Aside>
