Human Follower Robot

This project is an Arduino-based human follower robot that uses an ultrasonic sensor and infrared (IR) sensors to detect obstacles and follow a human. The robot is designed to move forward, turn, or stop based on sensor input, making it an ideal starting point for robotics enthusiasts interested in learning about sensor integration and motor control.

Features

Obstacle Detection: Utilizes an ultrasonic sensor to detect objects in front of the robot and adjusts its movement accordingly.    
Human Following: Equipped with two IR sensors to detect the proximity of a human hand, allowing the robot to follow or turn towards the person.    
Motor Control: Controls two motors to move the robot forward, turn left or right, and stop when necessary. Motor speeds are adjusted dynamically based on sensor readings.    
Simple and Efficient Design: The code is straightforward, making it easy to understand and modify for beginners.  

Components

Ultrasonic Sensor (HC-SR04): Measures the distance to objects in front of the robot.
IR Sensors: Detects the presence of a human hand on either side of the robot.
Motors: Two DC motors control the robot's movement, powered by an H-bridge or motor driver.
Arduino Board: The microcontroller that processes sensor data and controls the motors.

How It Works

The robot uses the ultrasonic sensor to continuously measure the distance to objects in front of it.
If the IR sensors detect a hand close to either side, the robot adjusts its movement to follow the hand.
If an obstacle is detected within a certain range, the robot either stops or adjusts its direction to avoid the obstacle.
The motors are controlled using PWM signals to vary the speed, allowing for smooth and precise movement.

Setup and Usage

Wiring: Connect the ultrasonic sensor, IR sensors, and motors to the Arduino as per the pin configuration in the code.
Upload Code: Upload the provided Arduino sketch to your Arduino board.
Power On: Once powered on, the robot will start monitoring its surroundings and respond based on sensor input.

Future Enhancements
Implement smoother turning logic for more graceful movements.
Add more sensors for enhanced obstacle detection and avoidance.
Integrate a camera for advanced human tracking using computer vision.
