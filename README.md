# Ece-project
The Object Detector Radar is an embedded electronics project designed to detect the presence and position of nearby objects using ultrasonic sensing and real-time signal processing. The system replicates the basic working principle of radar by continuously transmitting pulses, receiving the reflected signals from obstacles, and calculating 
Object Detector Radar using Ultrasonic Sensor & Arduino
📌 Project Overview

The Object Detector Radar is an ECE project that detects objects within a defined range by scanning the environment using an ultrasonic sensor mounted on a servo motor. The system mimics basic radar functionality by sending ultrasonic pulses, receiving echoes, calculating distance, and plotting detected objects on a radar-style interface in real time.

This project demonstrates concepts of embedded systems, sensor interfacing, real-time data processing, and environmental scanning.

🚀 Features

180° scanning using servo motor

Real-time object detection

Distance measurement using ultrasonic sensor (HC-SR04)

Radar-style display on laptop (Processing IDE GUI)

Low-cost, easy-to-build, beginner-friendly

Applications in robotics, obstacle detection & security systems

🛠️ Components Used

Arduino UNO

HC-SR04 Ultrasonic Sensor

SG90 Servo Motor

Jumper Wires

USB Cable

Laptop/PC with Arduino IDE + Processing IDE

🔧 Working Principle

The servo rotates the ultrasonic sensor across a predefined angle (0°–180°).

At each angle, the sensor sends ultrasonic pulses and receives echo signals.

Arduino calculates distance using time-of-flight formula.

Data is sent to the Processing GUI through serial communication.

The radar interface plots detected objects in real time.

📂 Project Structure
/Object-Detector-Radar
│── Arduino_Code/
│── Processing_GUI_Code/
│── images/
│── README.md

▶️ How to Run

Upload the Arduino code to the Arduino UNO.

Open the Processing GUI code and run it.

Select your COM port.

Watch the radar map display real-time detected objects.

📸 Screenshots

(Add your radar interface and hardware setup images here)

🧠 Applications

Robotics and automation

Obstacle detection

Security monitoring

Smart parking systems

Industrial distance-monitoring systems

🤝 Contributing

Feel free to fork the repository and submit improvements!
