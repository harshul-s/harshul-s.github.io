---
title: Robotics Capstone - Autonomous/Unmanned Garden Rover
date: 2024-05-01T09:17:34.193Z
description: garden rover that is capable of dispensing water, monitoring soil
  health and navigating and localizing within a garden
taxonomies:
  tags:
    - Robotics
    - ROS
    - Embedded Programming
    - SLAM
    - C/Arduino
extra:
  link: https://drive.google.com/file/d/1aj8vxZ1PvOd8CYHqXbwo3UE8UqEufL55/view?usp=sharing
  image: /media/screenshot-2024-07-04-at-5.25.36-pm.png
  featured: true
---
W﻿orked over a year to develop a semi-autonomous gardening robot that can maintain a hobbyist garden. 

#### S﻿ystem Decomposition:

* E﻿mbedded Systems

  * P﻿ump system and motor driver
  * L﻿inear Actuator and motor driver to enable potentiometer based control
  * S﻿oil Sensor and RS485 bus code to parse soil data 
* D﻿riveTrain

  * C﻿ustom Drivetrain that can handle ROS twist commands 
* V﻿ision

  * F﻿isheye camera for fiducial detection (fiducials assigned to each garden plant) 
  * L﻿IDAR for SLAM 
* Web Server

  * E﻿C2 Django Webapp endpoint for telemetry and user facing app
* T﻿ele-operation:

  ![](/media/teleop.jpg)