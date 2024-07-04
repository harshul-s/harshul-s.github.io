---
title: Multi Agent PathFinding (MAPF)
date: 2023-05-08T07:53:39.073Z
description: Multi Agent Path Finding by comparing a Prioritised A* planner with
  Conflict Based Search
taxonomies:
  tags:
    - Robotics
    - Python
extra:
  image: /media/screenshot-2024-07-04-at-3.56.01-pm.png
  link: /media/16350.pdf
---
We w﻿orked to Implement Conflict Based Search to compare and contrast it's performance and completeness in a simulation with multiple agents representing autonomous vehicles being controlled as part of some centralized fleet. 

We found that the structure of searching a conflict tree led to exponential time complexity impacting the performance of the planner significantly. However, we were able to structure scenarios and orderings of agents such that a prioritized planner would fail to find a path and CBS  would be capable of finding a solution.