---
layout: project
type: project
image: images/11)1.png
title: A* path planner for a grid world
permalink: projects/A* path planner for a grid world
# All dates must be YYYY-MM-DD format!
date: 2019-09-01
labels:
  - MATLAB
  - Navigation
  - Path Planning
summary: Developed an A* planner in MATLAB
---

<img class="ui medium right floated rounded image" src="../images/step2_3.png">

Two variants of A* are implemented in a grid based world with obstacles. Data was used from the UTIAS Multi-Robot Cooperative Localization and Mapping Dataset, by the ASRL lab. </br>
​

1) Offline A*: Paths are planned given a start position and a goal. A robot then follows this path using a simple P-controller. This however assumes the robot will follow the path as is, which is never the case given a noisy real-world. </br>

2) Online A*: Paths are recalculated for each achieved position. Gaussian noise is added to the motion model to simulate motion uncertainty.

code source: </br>

https://github.com/vishwajeet-NU/ML-AI-/tree/master/a_star
