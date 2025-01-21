# Face-Tracking-Robot

## Project Overview  

The **Face Tracking Robot** is a mobile, autonomous robot designed to track and follow a person's face in real time using computer vision and a pan-tilt mechanism. The robot incorporates a Python-based vision system and an Arduino-controlled 3-wheeled base, enabling two degrees of freedom (DOF) for precise face alignment and tracking.

---

## Key Features  

- **Pan-Tilt Mechanism**: Enables two degrees of freedom (DOF) using servo motors for precise face tracking.  
- **Face Detection and Tracking**: Implements Python-based computer vision algorithms for real-time face tracking.  
- **Autonomous Mobility**: 3-wheeled base controlled via Arduino allows the robot to follow a person autonomously while maintaining consistent face alignment.  
- **Real-Time Processing**: Utilizes a webcam feed for continuous tracking and navigation.  

---

## System Architecture  

The system integrates multiple components, including face detection, motion control, and autonomous navigation. Below is the block diagram illustrating the architecture:

![Block Diagram](https://github.com/Chetansai11/Face-Tracking-Robot/blob/main/block_diagram.png)  
*Figure 1: System Architecture of the Face Tracking Robot.*  

---

## Hardware Components  

1. **Pan-Tilt Mechanism**:  
   - Controlled by two servo motors to adjust the camera's vertical and horizontal positions.  
2. **3-Wheeled Mobile Base**:  
   - Controlled by an Arduino module for autonomous movement.  
3. **Webcam**:  
   - Captures live video feed for face detection.  
4. **Microcontroller**:  
   - Arduino Uno for controlling servos and wheels.  

---

## Software Components  

1. **Face Detection**:  
   - Python with OpenCV library for real-time face detection and tracking.  
2. **Motor Control**:  
   - Arduino code for controlling servo motors and DC motors.  
3. **Communication**:  
   - Serial communication between Python and Arduino for synchronized tracking and motion.  

---

## Demonstration  

### Face Tracking in Action  
Below is an example of the robot actively tracking a face in real time:  

![Face Tracking](https://github.com/Chetansai11/Face-Tracking-Robot/blob/main/tracking.png)  
*Figure 2: Face tracking demonstration.*  

### Robot Design  
The robot's physical structure with its pan-tilt mechanism and 4-wheeled base:  

![Robot Design]([path_to_robot_image.jpg](https://github.com/Chetansai11/Face-Tracking-Robot/blob/main/robot.png))  
*Figure 3: Assembled Face Tracking Robot.*  

---

## Results  

- **Real-Time Tracking**: Achieved precise and continuous face alignment using OpenCV algorithms.  
- **Autonomous Mobility**: The robot successfully followed a moving person while maintaining accurate face tracking.  
- **Efficient Processing**: Real-time tracking with minimal lag, ensuring smooth performance.  

---

## Future Enhancements  

- Integrate obstacle detection and avoidance for safer navigation.  
- Upgrade the vision system with advanced face recognition capabilities.  
- Enhance mobility by using a more robust motor driver for faster response.  
