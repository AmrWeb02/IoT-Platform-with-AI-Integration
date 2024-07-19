# IoT-Platform-with-AI-Integration
IoT solution built on RESTful architecture. This project leverages multiple technologies web development, embedded systems, and AI.
Note: We discussed the "health monitoring" use case to demonstrate the importance of IoT. 

This project allows for near real-time data transmission of blood oxygen saturation (SpO2) and heart rate (HR) using ESP32 as the microcontroller via Wi-Fi technology. Data is securely transmitted to a MySQL database for storage and future use.
A user-friendly web interface, built with HTML, CSS, JavaScript, and PHP allows effortless visualization and analysis of your health data.
This project provides a comprehensive health monitoring system that offers users the following capabilities:

Near Real-time health data: Continuously monitor your blood oxygen saturation (SpO2) using the MAX30102 oximeter sensor.
AI-powered insights: Provide personalized insights and recommendations tailored to your unique health profile using GEMINI API.
Data storage and visualization: Securely transmit sensor data via WiFi to a MySQL database.
Report: Generate a well-formatted report regarding the user's health status and recommendations to the nearest hospitals the patient should attend, GeoLocation API is used for this purpose.

This project empowers users with:
Enhanced health awareness: Real-time access to health data and AI-driven interpretations enable informed decision-making about your well-being.
Improved self-management: Proactively manage your health with the user-friendly interface, allowing you to track trends and identify potential issues early on.
Personalized insights: The AI integration provides valuable feedback tailored to your unique health profile.

To get started, you'll need the following:

⬝ Hardware:
1. ESP32 or any microcontroller that supports Wi-Fi
2. MAX30102 oximeter sensor or any sensor of your selection
3. Jumper wires and breadboard
4. LCD (optional)

⬝ Software:
1. Arduino IDE (Depends on the selected microcontroller)
2. MySQL database server (Mandatory)
3. Web server

⬝ Prerequisites:
1. Web Development skills: Familiarity with HTML, CSS, Javascript, and PHP (Including browser APIs like Fetch, Geo-Location and third-party APIs like GEMINI)
2. Data communication: REST APIs, Data exchange format (JSON)

