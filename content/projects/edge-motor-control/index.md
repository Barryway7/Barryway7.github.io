---
title: Edge Computing Control System for Motor Speed Regulation
date: 2024-07-01
tags:
  - Control Theory
  - Edge Computing
  - IoT
---

Course project for Cloud Computing and Industrial Internet (05/2024–07/2024). End-to-end edge control system from hardware to cloud.

<!--more-->

- Designed the system architecture: a front end with serial and MQTT communication, and a back end on EdgeX Foundry with Docker and Docker Compose.
- Implemented a PID controller and a fuzzy self-adaptive PI controller, with custom Go plugins for EdgeX Foundry.
- Configured MQTT topics and QoS for computer–edge communication and built a real-time motor speed monitoring system.
- Assembled and calibrated the hardware: microcontroller, rectifier, DC motor, and speed sensor.
