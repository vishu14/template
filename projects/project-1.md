---
layout: project
type: project
image: images/Screenshot from 2020-03-25 20-24-50.png
title: EKF - Slam
permalink: projects/Ekf Slam 
# All dates must be YYYY-MM-DD format!
date: 2020-02-01
labels:
  - Robotics
  - SLAM
  - C++
  - ROS
  - GIT
summary: A ROS implementation of EKF Slam on a turtlebot3 
youtubeId: BS0KN7_F8DE
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/Screenshot from 2020-03-25 20-24-50.png">
  <img class="ui image" src="../images/Screenshot 2020-03-25 20 12 33.png">
</div>

This project was built from the ground up and coded using C++. It employs a feature-based SLAM system using Extended Kalman filters and is run on the turtle bot 3 platform.

Project details:
1) A kinematics library called rigid2d, which provides useful functions for forward and inverse kinematics following the modern screw theory approach. This is detailed in 'Modern Robotics' by Kevin Lynch and Frank Park. </br>
2) Creation of URDF descriptions to match a turtlebot3's dimensions. </br>
3) Custom gazebo sensor plugins to simulate wheel encoders. </br>
4) Creating libraries called diff drive and waypoints to create differential drive robot and waypoint follower objects. </br>
5) Testing encoders and odometry in simulation and comparing it with the real turtlebot. </br>
6) Creating a clustering algorithm for identification of cylindrical landmarks. </br>
7) EKF slam.

Code source :

https://github.com/vishwajeet-NU/slam_project

  
{% include youtubePlayer.html id=page.youtubeId %}

