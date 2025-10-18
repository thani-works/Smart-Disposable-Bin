

# Smart Disposable Bin - IoT-based Waste Management System

## Project Overview

The **Smart Disposable Bin** is an intelligent, sensor-driven waste management system designed to automate waste segregation, monitor fill levels, and notify users in real-time. Combining IoT technologies, RFID, infrared, and ultrasonic sensors, the system promotes hygiene, efficiency, and sustainable waste disposal in smart cities, institutions, and residential areas.

---

## Features

* **Lid Automation**: Infrared (IR) sensors detect user presence and automatically open/close the bin lid, ensuring contactless disposal.
* **Waste Classification**: RFID-based detection classifies waste into **biodegradable**, **non-biodegradable**, or **ferromagnetic**, and directs it to the correct compartment.
* **Fill-Level Monitoring**: Ultrasonic sensors measure bin fill percentage to prevent overflow and optimize waste collection.
* **Alert Notification**: Cloud-integrated notifications are sent when bins are near capacity.
* **Cloud Integration**: Supports Firebase, ThingSpeak, IFTTT, and smart device integration for real-time monitoring.
* **Dashboard**: Mobile and web interface displays bin status, history, and analytics for users and authorities.

---

## System Architecture

The system follows a modular approach:

1. **Lid Automation Module** – Contactless lid operation via IR sensors and servo motors.
2. **Waste Classification Module** – RFID-based identification and mechanical sorting.
3. **Fill-Level Monitoring Module** – Ultrasonic sensors detect fill levels and send alerts.
4. **Alert Notification Module** – Cloud services push notifications to apps or devices.
5. **Cloud Module** – Centralized data storage and smart device integration.
6. **User Interface Module** – Web or mobile dashboard built using HTML, CSS, JavaScript, Flutter, or MIT App Inventor.

---

## Technologies Used

* **Hardware**: ESP32/Arduino, IR sensor, RFID reader & tags, Ultrasonic sensor, Servo motors
* **Software & Web**: HTML5, CSS3, JavaScript (ES6+), ThingSpeak API, Firebase, IFTTT
* **Execution Environment**: Any modern web browser (Chrome, Firefox, Edge)

---

## Working

1. User approaches the bin → IR sensor detects presence → Lid opens automatically.
2. Waste item is scanned via RFID → Microcontroller classifies the waste.
3. Servo motors direct waste to the correct compartment.
4. Ultrasonic sensors continuously monitor fill levels → Cloud alert triggered at threshold (e.g., 85%).
5. Dashboard displays real-time bin status, historical data, and notifications.

---

## Benefits

* Promotes hygiene and contactless disposal
* Ensures efficient waste segregation at the source
* Reduces manual labor and operational inefficiencies
* Supports smart city initiatives and data-driven decision-making

---

## Setup Instructions

1. Connect sensors and actuators to ESP32/Arduino as per circuit diagram.
2. Upload microcontroller code to handle sensor input and cloud communication.
3. Configure ThingSpeak or Firebase channel for data logging.
4. Open `index.html` in any modern web browser to view real-time dashboard.

---

## Screenshots

**Circuit Connection**
<img width="774" height="564" alt="circuit png" src="https://github.com/user-attachments/assets/f5234664-38fa-4307-bced-4aa7a7305c34" />


**Top-view of Model**
![Model](screenshots/model.png)

**Dashboard Interface**
![Dashboard](screenshots/dashboard.png)

---

## License

This project is licensed under the MIT License.

---


