# Wall Climbing Robot – ROS 2 Controlled Vertical Navigation and Object Detection

This repository contains the design, source code, and technical documentation for a **wall-climbing robot** designed for vertical surface navigation and autonomous object tracking. The robot utilizes **five brushless motors** for adhesion to the wall and **two DC motors** for movement along the surface. The system is controlled using **ROS 2**, enabling modular control, sensor integration, and autonomous functionality for efficient inspection and interaction with objects on vertical surfaces.

## Project Overview
![WhatsApp Image 2025-05-28 at 23 31 18_49b4ef34](https://github.com/user-attachments/assets/1eed36ed-f4df-4bb4-a358-0da6e0ac14bb)

The wall-climbing robot is equipped with the following key components:

- **Five Brushless Motors**: These motors are used to generate the necessary force to adhere the robot to the wall via suction or magnetic mechanisms.
- **Two DC Motors**: These motors provide movement for the robot, enabling it to navigate across vertical surfaces.
- **ROS 2 Integration**: The robot’s control system is built upon ROS 2, which facilitates modular software architecture, sensor fusion, and autonomous navigation.
- **Object Detection System**: The robot can detect objects and autonomously navigate towards them for inspection or interaction.

## Hardware Components

The hardware setup for the wall-climbing robot includes the following components:

- **Brushless Motors (x5)**: Used for adhesion to vertical surfaces through suction or magnetic mechanisms.
- **DC Motors (x2)**: Responsible for movement along the wall surface.
- **Motor Drivers**: ESCs for controlling brushless motors and H-bridge drivers for DC motor control.
- **Microcontroller / Single-Board Computer**: Raspberry Pi 4 or NVIDIA Jetson Nano for processing and control.
- **Camera Module**: A camera system for real-time object detection.
- **Power Supply**: A battery pack designed to provide sufficient power for high-current motors and other components.

## Software Architecture

The software stack for the wall-climbing robot is based on **Robot Operating System 2 (ROS 2)**, which facilitates modular development and communication between system components. The key software components are:

- **Motor Control Node**: Manages the control of motors for both adhesion and movement.
- **Object Detection Node**: Uses computer vision techniques to identify objects in the robot’s environment.
- **Navigation Node**: Computes the trajectory and movement commands to direct the robot towards detected objects.
- **TF / Odometry **: For localization and tracking the robot’s position relative to its environment.


