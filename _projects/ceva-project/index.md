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
main-image: /Ceva.png
---

---
# Design Challenge
The core challenge of this project was to build a vision-based system capable of reliably detecting boxes and accurately measuring their physical properties — regardless of how they were positioned in front of the camera. The system needed to handle varying box orientations and sizes without any manual input, reflecting the kind of unpredictability found in real-world logistics and warehousing environments. This highlighted the need for robust object detection, precise depth estimation, and intelligent volume classification.



## Measurement Objective
Our system was designed to detect a box placed within the camera's field of view and automatically compute its height, dimensions, and total volume. Beyond raw measurements, the system would then compare the calculated volume against predefined thresholds for small, medium, and large box categories — alerting the user if the object's volume exceeds the recommended limits for each size class.




## Thematic Arena: Scaled Warehousing Simulation
The project was scoped as a scaled-down simulation of a logistics and warehousing use case, where automated dimensioning of parcels is a common operational need. Rather than a physical arena, our working environment was a controlled tabletop setup designed to replicate how boxes might be presented to a fixed scanning station in a warehouse setting.




## Hardware Platform: ZED Camera
For this project, we used the ZED stereo camera as our primary sensing device. The ZED provides high-quality RGB imagery alongside dense depth data, making it well-suited for both object detection and 3D spatial measurement in a fixed-camera configuration.
{% include image-gallery.html images="ZED2i.png" height="400"%} 



## Detection Framework: YOLO-Based Object Detection
To identify boxes within the camera's field of view, we employed a YOLO-based object detection model. YOLO's real-time inference capabilities allowed us to accurately localise boxes in each frame, which then served as the region of interest for depth extraction and dimension calculation.
{% include image-gallery.html images="Detection.png" height="400"%} 



## Demonstration
This clip demonstrates our vision-based dimensioning system using the ZED camera and YOLO, detecting boxes in real time and instantly computing their height, dimensions, and volume against standard size classifications.  
If you would like to explore the source code for this project, you can visit our GitHub repository:  
[🔗 View Project Code on GitHub](https://github.com/AloysiusHo/Personal_Project/tree/main/Systems-Engineering-Project-1-Group-6-main)

{% include youtube-video.html id="bXW4LSCAjjY" autoplay = "true" width= "900px" %}  

<br>


