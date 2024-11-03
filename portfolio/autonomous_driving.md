---
layout: default
title: Future Mobility Technology Center
---

# {{ page.title }}

<div class="message">
Undergraduate Research Intern, Dec. 2022 – Feb. 2023 <br>
The <a href="https://www.fmtc.snu.ac.kr/">Future Mobility Technology Center (FMTC)</a> at Seoul National University, under the guidance of Prof. Kyongsu Yi, focuses on cutting-edge research in autonomous driving, perception, and control systems for automated vehicles. During my internship, I engaged in comprehensive training on autonomous driving technology and participated in the Sungkyunkwan University Future Mobility Automated Driving Software Contest, where our team received the Best Design Award.
</div>

## 1. Autonomous Driving Training Program

Throughout December 2022, I attended a month-long training program on the essential components of autonomous driving, covering **perception, decision-making, and control systems**. Led by Prof. Kyongsu Yi and FMTC researchers, the sessions detailed the required specifications, algorithm types, and current developmental stages in academia and industry. Additionally, I gained hands-on experience in autonomous vehicle technology on **FMTC’s internal driving track**, where I observed and interacted with various autonomous vehicles under development, including an opportunity to drive a self-driving truck.
<img src="/images/fmtc_truck.png" alt="Driving an Autonomous Truck" style="width: 50%; margin: 0.5rem; border-radius: 5px;">


In this program, I worked with tools such as **ROS, Ubuntu, Python, MATLAB, and CATIA** to implement:

- **LiDAR Mapping**: Real-time mapping for environmental analysis using LiDAR sensors.
- **Intersection Decision-Making**: Techniques for safe and efficient intersection navigation.
- **Kalman Filtering**: Utilized radar and GPS data in Kalman filtering to enhance vehicle positioning accuracy.

This experience provided a comprehensive understanding of autonomous driving systems and insights into the development of real-world applications.

<img src="/images/fmtc_radar.png" alt="Radar Practical Exercise" style="width: 50%; margin: 0.5rem; border-radius: 5px;">

## 2. Sungkyunkwan University Future Mobility Automated Driving Software Contest

In February 2023, I led the **LiDAR team** in the **Sungkyunkwan University Future Mobility Automated Driving Software Contest**, where our team was awarded **Best Design**. Our focus was on creating a perception system that integrated LiDAR and camera data to detect and classify environmental features and obstacles. Key contributions included:

- **LiDAR-Based Obstacle Detection**: Developed detection and categorization algorithms for nearby objects, enabling real-time responses.
<img src="/images/fmtc_lidar1.png" alt="LiDAR Mapping Screen" style="width: 50%; margin: 0.5rem; border-radius: 5px;">

- **ROS-Free Communication Protocol**: Optimized communication between scripts by implementing a TCP/IP-based protocol to bypass ROS, suitable for our limited hardware and computational resources. This allowed seamless data exchange between `mai.py` (lane recognition and control) and the LiDAR-based obstacle detection script.

- **YOLO V5 Object Detection**: Integrated a camera-based object detection model using YOLO V5 to identify lanes, traffic signals, and obstacles. Set up OpenCV and configured a webcam to capture and analyze real-time visual data.
<img src="/images/fmtc_yolo.png" alt="YOLO V5 Object Detection in Action" style="width: 50%; margin: 0.5rem; border-radius: 5px;">

### Technical Skills and Tools

Through this project, I honed my skills in:

- **ROS and Ubuntu**: Efficiently set up and optimized ROS for autonomous tasks.
- **Python and OpenCV**: Developed real-time scripts for object recognition and environmental mapping.
- **Kalman Filtering**: Used for multi-sensor data fusion in vehicle trajectory prediction.
- **YOLO V5**: Trained and deployed object detection models for real-time classification.
- **RPLIDAR Library**: Applied for real-time LiDAR mapping and obstacle detection.

### Reflections and Takeaways

This internship provided a thorough foundation in the technological principles behind autonomous vehicles, from high-level software algorithms to hardware integration. Engaging in both the training program and a competitive contest allowed me to deepen my technical capabilities and gain insights into adapting autonomous driving solutions under real-world constraints. Moreover, this experience sparked my interest in **computer vision** and **environmental perception algorithms**, motivating me to explore applications of AI in enhancing daily life.
