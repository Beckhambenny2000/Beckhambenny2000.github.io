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
# Header 1 
Used for the title (already generated automatically at the top)
## Header 2  
Use this for the header of each section
### Header 3 
Use this to have subsection if needed


## Embedding images 
### External images
{% include image-gallery.html images="https://live.staticflickr.com/65535/52821641477_d397e56bc4_k.jpg, https://live.staticflickr.com/65535/52822650673_f074b20d90_k.jpg" height="400"%}
<span style="font-size: 10px">"Starship Test Flight Mission" from https://www.flickr.com/photos/spacex/52821641477/</span>  
You can put in multiple entries. All images will be at a fixed height in the same row. With smaller window, they will switch to columns.  

### Embeed images
{% include image-gallery.html images="limo.png" height="400" %} 
place the images in project folder/images then update the file path.   

## Embedded LIMO Video (Autoplay)

{% include mp4-video.html src="/assets/Video/Limo-video.mp4" autoplay="true" %}

## Adding external links
[Source code on Github](https://github.com/YongJiee/Systems-Engineering-Project-1-Group-6)


