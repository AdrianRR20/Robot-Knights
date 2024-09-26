Engineering materials
====

This repository contains engineering materials of a self-driven vehicle's model participating in the WRO Future Engineers competition in the season 2024.

## Content

* `t-photos` contains 2 photos of the team (an official one and one funny photo with all team members)
* `v-photos` contains 6 photos of the vehicle (from every side, from top and bottom)
* `video` contains the video.md file with the link to a video where driving demonstration exists
* `schemes` contains one or several schematic diagrams in form of JPEG, PNG or PDF of the electromechanical components illustrating all the elements (electronic components and motors) used in the vehicle and how they connect to each other.
* `src` contains code of control software for all components which were programmed to participate in the competition
* `models` is for the files for models used by 3D printers, laser cutting machines and CNC machines to produce the vehicle elements. If there is nothing to add to this location, the directory can be removed.
* `other` is for other files which can be used to understand how to prepare the vehicle for the competition. It may include documentation how to connect to a SBC/SBM and upload files there, datasets, hardware specifications, communication protocols descriptions etc. If there is nothing to add to this location, the directory can be removed.

## Introduction

“Knight” the robot of our team is conformed by a brick ev3 with the following characteristics:
1. processor: it has an ARM9 processor at 300 MHz.


2. Display: A monochromatic LCD screen of 178x128 pixels.


3. Navigation buttons: 6 buttons (up, down, left, right, center, center, and “back”) to navigate through the menu.


4. Memory: 16 MB of internal flash memory and 64 MB of RAM. It also has a microSD card slot up to 32 GB for memory expansion.


5. Connectivity:

USB: A standard USB port for connecting peripherals, such as keyboards or Wi-Fi dongles.

Mini-USB port: For connecting to a computer and transferring programs.

Bluetooth: For wireless communication with other devices.

Wi-Fi: Supports USB Wi-Fi adapters for wireless connectivity.



6. Motor and sensor ports:

4 ports for motors (A, B, C, D).

4 ports for sensors (1, 2, 3, 4).



7. Power: Powered by 6 AA batteries or a rechargeable lithium-ion battery.


8. Loudspeaker: Integrated, allows to play sounds and music.


9. Compatibility: Can be programmed using various programming environments such as EV3-G (official LEGO software), Python, and other languages.

![image](https://github.com/user-attachments/assets/2a1b52fb-022d-4902-8b60-de1180ad1ced)

The motors and sensors we used for our robot were:


1. Servomotor Ev3 (A): In charge of directing the movement of the robot in clockwise or counterclockwise directions.

2. Servomotor Ev3 (B): It allows the robot to advance in the direction of the motor A.

3. Large motor NXT: It performs the radar function by connecting to the ultrasonic and color sensors that search for and identify obstacles.

4. Ultrasonic sensor: Measures the distance in centimeters to the obstacle in front of it.

5. Color sensors: Detect the color of the obstacles in order to dodge to the left or right.

6. Gyroscope: Calculates the robot's rotation degrees to park itself independently.

![image](https://github.com/user-attachments/assets/7bf6b790-8e13-4088-a447-a85a781107b4)
