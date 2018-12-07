# Arbotix Drivers

## Summary

Slightly modified version of the regular [arbotix_ros](https://github.com/Interbotix/arbotix_ros) repository, which contains drivers for using the [Arbotix microcontorller](https://www.trossenrobotics.com/p/arbotix-robot-controller.aspx) with ROS. Modifications include a new controller (```arbotix_gazebo```), which matches the functionality of the hardware arbotix controller (``` arbotix_driver```) in simulation, and the publishing of joint loads from dynamixel servos on physical systems.

## Recommended OS/Programs

This software was developed and tested in:
- Ubuntu 16.04 LTS
- ROS Kinetic
- Gazebo 7.13.0
