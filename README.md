🧠 Bachelor Thesis — Pothole Detection and Its Avoidance Using Machine Learning

Author: Charudatta Bangal

Institution: Sinhgad College of Engineering, Pune (Affiliated to Savitribai Phule Pune University)

Degree: Bachelor of Engineering (Computer Engineering)

Year: 2019–2020

Guide: Prof. S. N. Bhosale

📘 Project Overview

This project presents a smart pothole detection and avoidance system using machine learning and computer vision techniques.
The system detects potholes and road irregularities through camera and IR sensors, assisting drivers by:

Alerting them to the presence of potholes

Suggesting movement (left/right) to avoid damage

Automatically reducing vehicle speed near detected potholes

Collected data is stored locally or on a cloud database and can later be used for road condition analysis, prioritizing road repairs, and urban planning.

🎯 Objectives

Detect road anomalies such as potholes, bumps, and uneven surfaces in real time.

Assist the driver through directional guidance and automatic speed control.

Improve driving comfort and safety.

Provide data insights for municipal maintenance and smart city infrastructure.

💡 Motivation

Prolonged monsoons and poor maintenance lead to severe road degradation in India, resulting in accidents and vehicle damage.
This system aims to mitigate such issues by combining IoT, sensors, and machine learning for proactive road condition detection.

⚙️ System Architecture

Hardware Components:

Raspberry Pi (controller)

IR sensors (for pothole detection)

Camera module (for speed-breaker recognition)

GPS module (for geolocation)

Wi-Fi connectivity (for cloud sync)

Software Components:

Programming Language: Python 3

IDE: PyCharm

Database: SQLite / Cloud

Algorithms: Convolutional Neural Networks (CNNs) for image-based pothole detection

🧩 Functional Flow

Capture road image and sensor data.

Process input through CNN model to detect potholes/speed-breakers.

Provide driver assistance (alerts and navigation).

Store detection data in the local or cloud database for later analytics.

🧠 Algorithm Used

Convolutional Neural Networks (CNN) — used to classify and detect potholes through:

Convolution operation

ReLU activation

Max pooling

Flattening

Fully connected layers

This combination ensures efficient feature extraction and high detection accuracy even under varying light and angle conditions.

🧪 Testing and Results

Detection time: ~10 seconds per pothole

Accuracy: Stable detection under varying light conditions

Performance: Smooth real-time operation at moderate vehicle speeds

GUI interface was developed in Python for user interaction and visualization of road anomalies.

📊 Project Planning Summary

Project Duration:-	9 months (COCOMO II Estimation)

Estimated Effort:-	44 person-months

Estimated Cost:-	  ₹45,000 (approx.)

Model Used:-	      Waterfall Model

🧩 Publication Details

Journal 1:
International Journal of Advance Scientific Research and Engineering
Paper: A Survey on Pothole Detection and Its Avoidance Using Machine Learning
ISSN: 2456-0774

Journal 2:
Open Access International Journal of Science and Engineering
Paper: Pothole Detection and Its Avoidance
ISSN: 2456-3293

🔮 Future Scope

Integration with Smart City IoT networks

Sending real-time alerts to municipal authorities

Use of reinforcement learning for adaptive driving response

Integration with autonomous driving frameworks

👩‍💻 Contributors

Charudatta Bangal:-	 Machine Learning & System Integration

Deveyash Bharat:-	   Front-end Interface

Aryan Vaid:-	       Image Processing

Siddharth Changede:- Sensor Module

Aditya Raj:-	       Database & Cloud
