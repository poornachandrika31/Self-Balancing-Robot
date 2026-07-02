# Self-Balancing Two-Wheeled Robot

A ROS 2-based self-balancing two-wheeled robot designed to maintain stability using PID feedback control. The project integrates simulation, embedded systems, and robotics concepts by combining ROS 2, Gazebo, ESP32, IMU sensors, and micro-ROS to develop a modular real-time control system.

---

## Project Overview

This project was developed as part of a four-member team during a semester project to explore autonomous balancing robots and real-time robotic control systems.

The robot continuously monitors its orientation using IMU sensor data and applies PID-based corrections to maintain balance. Development and testing were performed in Gazebo before preparing the system for hardware deployment.

---

## Features

- ROS 2 Jazzy based modular architecture
- Gazebo simulation environment
- PID-based balancing controller
- Real-time sensor processing
- Modular ROS 2 nodes
- ESP32 integration using micro-ROS
- IMU-based orientation estimation
- Hardware-ready software architecture

---

## Tech Stack

### Languages
- Python
- C (ESP32 Firmware)

### Robotics
- ROS 2 Jazzy
- Gazebo
- micro-ROS

### Embedded Systems
- ESP32
- MPU6050 IMU Sensor

### Control
- PID Controller

### Tools
- Ubuntu Linux
- Git
- VS Code

---

## System Architecture

```
IMU Sensor
      │
      ▼
 Sensor Processing Node
      │
      ▼
 PID Controller Node
      │
      ▼
 Motor Control Node
      │
      ▼
ESP32 / Motors
```

---

## Project Workflow

1. Collect orientation data from the IMU sensor.
2. Publish sensor readings through ROS 2 topics.
3. Compute balancing correction using a PID controller.
4. Send motor control commands.
5. Validate balancing performance inside Gazebo.
6. Prepare deployment using ESP32 and micro-ROS.

---

## My Contribution

As part of a four-member team, I contributed to:

- ROS 2 application development
- Modular node design
- Gazebo simulation setup
- Integration of control logic
- Project testing and validation
- Documentation and project integration

---

## Learning Outcomes

- ROS 2 communication
- Publisher-Subscriber architecture
- Gazebo simulation
- PID control fundamentals
- Embedded robotics concepts
- Real-time robotic software development
- Hardware-software integration

---

## Future Improvements

- Implement sensor fusion using a Kalman Filter
- Tune PID parameters automatically
- Add SLAM and autonomous navigation
- Improve obstacle avoidance
- Deploy on physical hardware for real-world testing
