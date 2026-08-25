🐶 IoT-Based Dog Daycare Robotic System
Overview

The IoT-Based Dog Daycare Robotic System is a smart pet monitoring and feeding solution designed to assist pet owners in managing their pets remotely.

The system enables real-time pet monitoring, automatic food dispensing, food-level detection, and remote robot control through an internet-connected web interface.

This project combines IoT technologies, embedded systems, wireless communication, and cloud connectivity to provide a modern pet care solution.
images/
![Final Design](OUTPUTS.pdf)
 🐶 IoT-Based Dog Daycare Robotic System

📌 Project Overview

The IoT-Based Dog Daycare Robotic System is a smart pet monitoring and feeding solution designed to help pet owners remotely monitor, interact with, and feed their pets through an internet-connected platform.

The system integrates ESP32-CAM, ultrasonic sensors, servo motors, Firebase cloud services, and a web-based control interface to provide real-time pet monitoring and automated food dispensing.

 🎯 Objectives

- Enable remote pet monitoring through live video streaming.
- Automate pet food dispensing.
- Monitor food availability in the feeder.
- Allow users to control the robot remotely via the internet.
- Improve pet care when owners are away from home.


 🚀 Key Features

✅ Real-Time Video Monitoring using ESP32-CAM

✅ Automated Food Dispensing

✅ Food Level Detection using HC-SR04 Ultrasonic Sensor

✅ Remote Robot Navigation

✅ Firebase Cloud Connectivity

✅ Web-Based Monitoring and Control

✅ Internet of Things (IoT) Architecture

---

🏗️ System Architecture

```text
User Device (Mobile/Laptop)
            │
            ▼
     Web Application
            │
            ▼
    Firebase Database
            │
            ▼
        ESP32-CAM
            │
 ┌──────────┼──────────┐
 ▼          ▼          ▼
Servo     Ultrasonic  Motor Driver
Motor      Sensor      (L293D)


---

🔧 Hardware Components

| Component | Description |
|------------|------------|
| ESP32-CAM | Camera Module for Video Streaming |
| HC-SR04 Ultrasonic Sensor | Food Level Measurement |
| MG995 Servo Motor | Food Dispensing Mechanism |
| L293D Motor Driver | Wheel and Motor Control |
| DC Gear Motors | Robot Movement |
| Li-Po Battery | Power Supply |
| Arduino Platform | Embedded Control |

---

 💻 Software Components

- Arduino IDE
- Firebase Realtime Database
- Proteus Simulation
- HTML
- CSS
- Embedded C/C++
- IoT Cloud Communication

---

 ⚙️ Working Principle

1. The pet owner accesses the web application.
2. Commands are sent through Firebase Cloud.
3. ESP32-CAM receives instructions and streams live video.
4. The servo motor dispenses food when triggered.
5. The ultrasonic sensor monitors food levels.
6. Robot movement can be controlled remotely.
7. Real-time information is transmitted over the internet.

---

 📊 Technologies Used

- Internet of Things (IoT)
- ESP32-CAM
- Arduino
- Firebase
- Embedded Systems
- Robotics
- HTML
- CSS
- Proteus
- Cloud Connectivity

---

 📷 Project Outputs

 Final Design

![Final Design](OUTPUTS.pdf).

---

 🧪 Testing and Results

The developed system successfully:

- Dispenses food remotely.
- Streams live video from the pet environment.
- Detects food levels inside the container.
- Supports internet-based robot control.
- Provides real-time monitoring through a web application.

---

 📈 Future Enhancements

- AI-Based Pet Behavior Analysis
- Mobile Application Development
- Automated Feeding Schedules
- Pet Health Monitoring
- Voice Assistant Integration
- Smart Notification System

---

 📂 Repository Structure

```text
iot-dog-daycare-robotic-system
│
├── README.md
├── Project_Documentation.pdf
├── CODE_IOT_BASED_DOG_DAYCARE_ROBOTIC_SYSTEM.pdf
├── OUTPUTS.pdf
├── images
│   ├── final_design.jpg
│   └── source_code


---

 👩‍💻 Author

Avancha Sanjana

Bachelor of Technology (Artificial Intelligence)

Hyderabad, India

---
 📜 License

This project is created for academic and educational purposes.

