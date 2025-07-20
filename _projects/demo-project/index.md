---
layout: post
title: Systems Engineering Project 1
description:
   This project involved applying a systems engineering approach to develop and test an autonomous navigation system for the LIMO robot using ROS 1 Melodic. A custom arena was created to serve as a controlled environment for navigation tasks. The robot was configured with ROS navigation packages to perform mapping, localization, and path planning.
skills: 
  - Robot Operating System (ROS 1 Melodic)
  - C++ / Python Programming
  - Autonomous Navigation (using move_base, amcl, costmaps)
  - Linux/Ubuntu Development Environment
  - Sensor Integration (LIDAR, IMU, wheel encoders)

main-image: /limo.png
---

---
# Goal of the Project 
The ultimate objective was to demonstrate how a small mobile robot can navigate independently in a structured environment by combining software, hardware, and system-level thinking.
## Problem Definition 
This project enables the LIMO mobile robot to autonomously navigate a structured indoor arena using ROS 1 Melodic. The main challenge was configuring and integrating onboard sensors with the ROS navigation stack for reliable localization, path planning, and obstacle avoidance. A systems engineering approach was applied to develop and integrate the navigation program into the robot, ensuring consistent performance in the test environment.

## Mobile Robot: AgileX LIMO
#Introduction to AgileX LIMO
The AgileX LIMO is a versatile, four-wheeled mobile robot platform designed for indoor navigation and autonomous operations. It features integrated sensors and is compatible with ROS (Robot Operating System), making it ideal for research and development in robotics, including localization, path planning, and obstacle avoidance tasks.

{% include image-gallery.html images="limo.png" height="400" %} 
The AgileX LIMO is the current robot model used in our project.

## Robot Test Arena – Canopy Park Theme
{% include image-gallery.html images="Arena.jpg" height="400" %} 
My team and I designed and developed the arena layout for the robot’s navigation. The arena was constructed following the project theme, “Jewel Canopy Park.”

## AgileX LIMO Demonstration

{% include mp4-video.html src="/assets/Video/Limo-video.mp4" autoplay="true" %}

## Github
[Source code](https://github.com/YongJiee/Systems-Engineering-Project-1-Group-6)


