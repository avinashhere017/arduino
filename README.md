# Arduino-Based Obstacle-Avoiding Robot

Robot Image

This repository contains the code for an Arduino-based obstacle-avoiding robot. The robot is designed to navigate its environment while avoiding obstacles using an ultrasonic sensor, DC motors, and a servo motor for steering.

## Overview
The robot uses an Arduino board along with the following components:

AFMotor Library: This library is used for controlling the DC motors on the robot.
Servo Library: This library is used for controlling the servo motor responsible for steering the robot.
NewPing Library: This library is used to interface with the ultrasonic sensor, which is used to measure distances to obstacles.

## The robot's behavior is simple:

* It moves forward until it detects an obstacle within a certain range using the ultrasonic sensor.
* When an obstacle is detected, it stops, backs up, and turns in the direction of the open path, avoiding the obstacle.
It then continues moving forward.

## Code
The main code file, obstacle_avoiding_robot.ino, contains the Arduino sketch that controls the robot's behavior. The code is structured into setup and loop functions. Key functions and actions include:

Initializing the DC motors and servo motor.
Reading distances from the ultrasonic sensor.
Moving forward, backward, and turning left or right as needed to avoid obstacles.
Please note that the code provided here is a basic example and may require calibration and adjustments for your specific robot and environment.

## Circuit Diagram

![Circuit Diagram](Circuit Diagram.jpg)


## Usage
Set up the hardware components according to the circuit diagram provided.
Upload the obstacle_avoiding_robot.ino code to your Arduino board.
Power up the robot and watch it navigate while avoiding obstacles.
## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
This project was inspired by the desire to create a simple obstacle-avoiding robot using Arduino.
Special thanks to the creators of the AFMotor, Servo, and NewPing libraries, as well as the Arduino community for their support and contributions.


Feel free to contribute to this project or use it as a starting point for your own Arduino-based robotics projects!
