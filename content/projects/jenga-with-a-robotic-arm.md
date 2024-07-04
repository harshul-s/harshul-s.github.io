---
title: Jenga with a Robotic Arm
date: 2023-11-16T08:26:01.491Z
description: Programming a 6DOF direct drive arm to build a jenga tower
taxonomies:
  tags:
    - MatLab
    - Robotics
extra:
  link: https://youtu.be/k011gp1VwyA
  image: /media/img_01fdbf566fd1-1.jpeg
---
T﻿eam Capstone Project to build 6 layers of a Jenga tower within certain bounds within 2 minutes 

* B﻿uilt a robot class to interface with Hebi motor drivers. 
* Implemented forward and inverse kinematics using DH transformations.
* I﻿mplemented Splinar interpolation between waypoints for trajectory tracking
* E﻿xperimented with Position, velocity and torque control

E﻿explored tradeoffs in speed/accuracy and commanding position and velocities vs pure positions along with working around torque and joint limits for the robot. 

#### Ex﻿tensions:

* Introducing some form of force feedback to allow the robot's state to also include the force that is being applied by the jenga block.
* Introducing vision to avoid continual re-turning of motor gains to successfully achieve this task while dead reckoning