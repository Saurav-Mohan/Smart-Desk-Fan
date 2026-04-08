# RIG-Induction-Smart-Desk-Fan
Smart Tracking Thermal Fan
An automated desktop cooling system that integrates computer vision and thermal sensing to provide targeted airflow. The system utilizes face detection to orient the fan toward the user while dynamically adjusting motor speed based on environmental temperature.

Features
Autonomous Face Tracking: Uses Haar Cascade classifiers to identify and follow the nearest human face.

Dual-Axis Positioning: Two-servo mechanism (pan and tilt) to maintain directional focus.

Temperature-Dependent PWM: Automated fan speed adjustment based on real-time ambient temperature data.

Hardware Components
Microcontroller: ESP32

Video Capture: Laptop webcam

Actuation: Two High-Torque Servo Motors (Pan/Tilt) and one DC Fan.

Control: L298N Motor Driver 

Sensing: DHT11 Temperature Sensor.

Software Stack
OpenCV: Image processing and Haar Cascade implementation.

Python: Primary logic and serial communication.

C++ (Arduino): Low-level hardware pulse-width modulation and servo positioning.
