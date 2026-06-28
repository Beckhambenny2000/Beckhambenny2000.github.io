---
layout: post
title: Project 4
description:  
  This project aimed to solve a problem statement provided by CEVA Logistics while taking budget, sustainability, and social impact into consideration. To achieve this, we developed a computer vision system using a fixed camera setup that combines an RGB camera with a depth camera to detect objects and accurately estimate their physical dimensions. We designed and calibrated a real-time processing pipeline capable of identifying objects and computing their height and dimensions from camera data without manual intervention. The solution was developed for logistics and warehousing applications, simulating an automated package dimensioning system to improve operational efficiency. Through this project, we applied concepts in depth sensing, point cloud processing, and object detection to deliver a reliable and practical dimensioning solution.
  
skills: 
  - Robot Operating System (ROS 2 Humble)
  - C++ / Python Programming
  - Linux/Ubuntu Development Environment
  - System Integration
  - Project Management
main-image: /Ceva.png
---

---
# Design Challenge
The core challenge of this project was to develop a vision-based system capable of reliably detecting boxes and accurately estimating their physical dimensions, regardless of their orientation in front of the camera. The system was designed to handle boxes of different sizes and positions without manual intervention, reflecting the dynamic conditions commonly found in real-world logistics and warehousing environments. This required robust object detection, accurate depth estimation, and reliable volume classification to ensure consistent performance.



## Measurement Objective
Our system was designed to detect boxes within the camera's field of view and automatically estimate their height, dimensions, and overall volume. The calculated volume is then compared against predefined thresholds for small, medium, and large box categories. If the measured volume exceeds the allowable limit for its assigned category, the system alerts the user, enabling quick identification of oversized items in logistics and warehousing operations.




## Thematic Arena: Scaled Warehousing Simulation
The project was developed as a scaled-down simulation of a logistics and warehousing environment, where automated parcel dimensioning is a common operational requirement. Instead of a full-scale warehouse, a controlled tabletop setup was used to emulate how boxes would be presented to a fixed vision-based scanning station, providing a practical environment for developing and validating the system.




## Hardware Platform: ZED Camera
For this project, we used the ZED stereo camera as the primary sensing device. The camera captures high-resolution RGB images together with dense depth information, making it well-suited for accurate object detection and 3D dimensional measurement in a fixed-camera setup.
{% include image-gallery.html images="ZED2i.jpg" height="400"%} 



## Detection Framework: YOLO-Based Object Detection
To detect boxes within the camera's field of view, we employed a YOLO-based object detection model. Its real-time inference capability enabled accurate localisation of boxes in each frame, with the detected bounding boxes serving as the regions of interest for subsequent depth extraction and dimensional measurement.
{% include image-gallery.html images="Detection.png" height="400"%} 



## Demonstration
This clip demonstrates our vision-based dimensioning system using the ZED camera and YOLO, detecting boxes in real time and instantly computing their height, dimensions, and volume against standard size classifications.  
If you would like to explore the source code for this project, you can visit our GitHub repository:  
[🔗 View Project Code on GitHub](https://https://github.com/Beckhambenny2000/Beckham_workspace/tree/main/Project%204)

{% include mp4-video.html src="/assets/Video/ORACLE-X.mp4" autoplay = "true" width = "600px"%} 
<br>


