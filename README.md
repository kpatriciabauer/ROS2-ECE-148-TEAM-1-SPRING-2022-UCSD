# ROS2-ECE-148-TEAM-1
We need to build code to make the car go vroom vroom
so we have 3 nodes, lane guidance, lane detection, and calibration
The calobration node is responsible for giving the car the ability to differentiate yellow and white using computer vision
The lane detection node is meant to calculate the PID variables and also process the image to count the contours of white
The lane guidance node is what controlles the car's movement and it can detect distances at angles with the lidar
