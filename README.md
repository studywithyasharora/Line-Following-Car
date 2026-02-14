# Line-Following-Car
🤖 Line Follower Robot using Arduino &amp; L298N 


This project is a 2-Sensor Line Following Robot built using Arduino, L298N Motor Driver, and IR Sensors.

The robot follows a black line on a white surface using simple digital logic.

It is designed for:

Robotics beginners

School-level competitions

STEM education

Practical embedded systems learning

🛠 Hardware Used

Arduino Uno

L298N Motor Driver

2 × IR Sensors (Digital Output)

2 × Yellow Gear Motors

Robot Chassis

7V–12V Battery

Jumper Wires

⚙ Working Principle

The robot uses two IR sensors:

Sensor Output	Surface
1	White
0	Black
Logic:

Both sensors on white → Move Forward

Left sensor on black → Turn Left

Right sensor on black → Turn Right

Both sensors on black → Stop (junction detection)

This simple decision-making system allows the robot to stay aligned with the black line.

🔌 Pin Configuration
Motor Driver (L298N)
Function	Arduino Pin
IN1	4
IN2	5
IN3	6
IN4	7
ENA	9
ENB	10
IR Sensors
Sensor	Arduino Pin
Left IR	A5
Right IR	A4
🚀 Features

Simple and beginner-friendly logic

PWM speed control using ENA & ENB

Easy to upgrade to PID control

Compatible with yellow gear motors

Suitable for robotics competitions
