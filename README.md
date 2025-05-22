# 🤖 Face Tracking Robot

A real-time autonomous robot capable of detecting, tracking, and following a human face using a camera, pan-tilt mechanism, and Arduino-controlled mobile base. This project integrates **computer vision**, **embedded systems**, and **robotics** to demonstrate intelligent motion and real-time interaction.

---

## 🎯 Project Objective

To design and implement a mobile robot that can:
- Detect and track human faces using a webcam and OpenCV
- Control pan-tilt camera alignment for continuous face focus
- Navigate autonomously using a 3-wheeled Arduino-controlled base
- Synchronize visual tracking with physical motion in real time

---

## 🔑 Key Features

- 🎯 **Face Tracking**: Real-time detection and tracking with OpenCV’s Haar cascades or DNN models.
- 🎥 **Pan-Tilt Control**: Dual-servo mechanism enables 2-DOF camera movement (horizontal + vertical).
- 🚗 **Mobile Base**: 3-wheeled robot driven via Arduino and DC motors for autonomous motion.
- 🔄 **Serial Communication**: Python-Arduino integration using serial protocol to coordinate tracking and movement.

---

## ⚙️ System Architecture

![System Block Diagram](https://github.com/Chetansai11/Face-Tracking-Robot/blob/main/block_diagram.png)  
*Figure 1: Architecture of the Face Tracking Robot*

---

## 🧩 Hardware Components

| Component            | Description                                     |
|----------------------|-------------------------------------------------|
| 🎥 Webcam             | Captures live video stream                     |
| 🔄 Pan-Tilt Platform | Two servo motors for dynamic camera alignment   |
| 🧠 Arduino Uno        | Controls base movement and servo commands       |
| ⚙️ Motor Driver (L298N) | Powers the wheels and regulates movement       |
| 🔋 Power Source       | Battery pack to support mobile autonomy         |

---

## 🧠 Software Components

| Module               | Description                                      |
|----------------------|--------------------------------------------------|
| 🧾 Face Detection     | Python + OpenCV for real-time detection/tracking |
| 🎮 Motor Control      | Arduino C++ for driving motors and servos        |
| 🔗 Serial Sync        | USB Serial interface to coordinate motion & vision |

---

## 🚀 Demonstration

### 📸 Face Tracking in Action  
![Face Tracking](https://github.com/Chetansai11/Face-Tracking-Robot/blob/main/tracking.png)  
*Figure 2: Face detection and servo movement in real time*

### 🛠️ Robot Design & Build  
![Robot Design](https://github.com/Chetansai11/Face-Tracking-Robot/blob/main/robot.png)  
*Figure 3: Physical prototype of the robot with mounted camera and wheels*

---

## 📈 Results

- ✅ **Stable Real-Time Tracking** with smooth face locking using servo-based pan-tilt system.
- 🔄 **Autonomous Following** of subjects with consistent alignment, even during turns and distance shifts.
- ⚡ **Efficient Communication** between Python (vision) and Arduino (motion) with low latency.

---

## 🛠️ Tech Stack

- **Languages**: Python, C++
- **Libraries & Tools**: OpenCV, PySerial, Arduino IDE
- **Hardware**: Arduino Uno, Servo Motors (SG90), L298N Motor Driver, Webcam, 3-Wheel Chassis

---

## 🧪 Future Enhancements

- 🚧 Add **obstacle detection** (e.g., ultrasonic sensors) for safer path navigation.
- 🧠 Integrate **face recognition** to track specific individuals.
- ⚙️ Upgrade to **more powerful motors** and a **better battery system** for longer runtime and smoother movement.
- 📡 Enable **Bluetooth/WiFi remote control** for manual overrides or enhanced interactivity.

---

## 📬 Contact

**Chetan Sai Borra**  
📧 sai311235@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/chetan-sai-16a252251/)

> *This project demonstrates an end-to-end real-world integration of computer vision, embedded systems, and robotics—laying the groundwork for intelligent autonomous agents in personal and service robotics.*
