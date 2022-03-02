---
title: PX4 DDS
order: 3
pcx-content-type: best-practices
---
# Snippets

to-do 


git clone git@github.com:PX4/PX4-Autopilot.git ~/ros2_ws/PX4-Autopilot
git clone https://github.com/PX4/PX4-Autopilot.git --recursive -b v1.12.2
cd ~/ros2_ws/PX4-Autopilot

make px4_fmu-v5_rtps
make px4_fmu-v5_rtps upload

./Tools/mavlink_shell.py /dev/ttyACM0
in nuttx:
micrortps_client start -t UDP

micrortps_client start -t UART 


https://fast-dds.docs.eprosima.com/en/latest/installation/sources/sources_linux.html
https://docs.px4.io/master/en/dev_setup/building_px4.html
https://docs.px4.io/master/en/config/firmware.html



ping www.google.com 
screen /dev/ttyUSB0 57600 8N1 
nsh> micrortps_client start -t UDP
INFO  [micrortps_client] UDP transport: ip address: 127.0.0.1; recv port: 2019; send port: 2020; sleep: 1000us

kill ctrl+a + k

vncserver -geometry 1920x1000   
vncserver -kill :1

> Author: [Mihir Patel](https://github.com/mihyr)