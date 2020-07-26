---
layout: project
type: project
image: images/micromouse.jpg
title: Micromouse
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2015-07-01
labels:
  - Robotics
  - Arduino
  - C++
summary: My team developed a robotic mouse that won first place in the 2015 UH Micromouse competition.
---


<div class="ui small rounded images">
  <img class="ui image" src="../images/Screenshot from 2020-03-25 20-24-50.png">
  <img class="ui image" src="../images/Screenshot 2020-03-25 20 12 33.png">
</div>

This project was built from the ground up and coded using C++ in the ROS platform. It employs a feature-based SLAM system using Extended Kalman filters and is run on the turtle bot 3 platform.

The entire task is split into parts as follows:
1) A library called rigid2d, which creates useful methods following the modern screw theory approach, detailed in 'Modern Robotics' by Kevin Lynch and Frank Park.
2) Creation of URDF descriptions to match a turtlebot3's dimensions
3) Creating libraries called diff drive and waypoints to create differential drive robot  and waypoint follower C++ objects
4) Testing encoders and odometry in simulation and comparing it with the real turtlebot
5) Creating a clustering algorithm for identification of cylindrical landmarks
6)  EKF slam

Code source :

https://github.com/vishwajeet-NU/slam_project


