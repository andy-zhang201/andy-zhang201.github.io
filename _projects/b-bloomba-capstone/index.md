---
layout: post
title: "The Bloomba: An autonomous plant-watering robot demonstration"
description:  Team leader for an autonomous plant watering robot project (Final Year Capstone Thesis). It uses a LIDAR sensor to measure its surroundings and a SLAM algorithm to navigate. We also built a custom watering arm to water pots that are placed up to 130 cm high. To accurately locate the plant pots, it can also use computer vision to identify April Tags placed on the pots.

skills: 
- Leadership
- ROS2/Linux programming
- Python Programming
- Computer Vision
- Project Management
main-image: /images/poster_cropped.png
---

---
## Situation
My final year engineering capstone project was an autonomous plant watering robot for Lake Harbour offices, built alongside my teammates Benjamin Nero, Christine Vu, Louis Liu, and Luke Palandra. The project was highly interdisciplinary and tested our skills in mechanical, electrical, and software engineering. Lake Harbour’s office houses many potted plants which need to be watered regularly. The challenge thrown to us was to construct a plant watering robot that could travel to each of the plants in the office and water them all in one trip. The plants were placed at different elevations, requiring the robot to reach up and down to water certain plants. Lastly, the robot needed to complete its task autonomously, without human control or intervention.  

{% include image-gallery.html images="./images/OfficeMap.png, ./images/Plants.png" height="300" alignment="center" %} 

## Methods Used
My role in the team was to take leadership of the overall robot design and ensure that each system was integrated coherently. I used project management practices such as setting milestones, Gantt charts for scheduling, and design phase reviews to make collective, informed decisions on our next steps. I talked to each subsystem lead to understand their requirements, and when conflicts arose I would bring people together to resolve them. 

{% include image-gallery.html images="./images/Robot Design.png" height="300" alignment="center" %} 

{% include image-gallery.html images="./images/ben_assemble.jpg, ./images/ben_finished.jpg" height="300" alignment="center" %} 

I was fascinated by the computer vision aspect of the project and also implemented software to allow the robot to detect plant pots and measure how high they are from the ground. I took the lead in developing an April Tags detection feature using ROS2 and Python for the robot platform, for which we used the iRobot Create 3. I calibrated a desktop webcamera to discover its optic parameters, and then used an apriltags library to detect visual fiducials using a Raspberry Pi 4. I wrote a ROS2 node using Python to take detections from the webcamera and calculate their corresponding tag’s position in space. Doing so allowed the robot to measure where the plant pots were and to move into position where it could water them.

{% include youtube-video.html id="7-nJhi6nrz0" autoplay= "false" width="800px"%}


## Outcomes
We made a custom chassis for mounting the sensors to the robot, the watering arm, and a 4L tank. An electrical system was also built to power the pump and to move the watering arm with an Arduino MC board. Our robot could travel to all the plants in the office and water them using remote control, proving the functionality of our hardware systems.

{% include youtube-video.html id="Yv5cJ6PL378" autoplay= "false" width="800px"%}

Running on a Raspberry Pi 4, our autonomy stack was able to generate a map of the entire office and use it to find its location using SLAM. Our robot could also detect April Tags to measure how tall it needed to raise its watering arm and what position it needed to reach to water it.

Thanks to the efforts of my team and I, our project won **2nd place for Best Overall Capstone Project** in the end of year showcase!

{% include image-gallery.html images="./TeamBloomba.JPG" height="600" alignment="center" %} 

Future work on the project should integrate the autonomy stack with our April Tags node to allow the robot to seek out plants and water them autonomously. A user interface should be developed to make the robot intuitive to use, and the robot’s battery should be stress tested to determine how many plants it can water before it needs to recharge.

Our project poster summarizes our robot's capabilities: <a href="https://drive.google.com/file/d/1s82e8F0W3_51T0VU1_VDnTmWZpQ_koFt/view?usp=sharing"> <b>Capstone Showcase Poster</b> </a>

For more information, please look at our final report: <a href="https://drive.google.com/file/d/1VrwP-gLmM_8kJhrKf-MG7TYiCl2okHa1/view?usp=sharing
"><b>Team Bloomba Capstone Final Report</b></a>

