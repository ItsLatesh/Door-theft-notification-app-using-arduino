# Door-theft-notification-app-using-arduino


Overview
This project implements a smart door monitoring system using Arduino and sensors to detect door status changes and notify users of potential theft or unauthorized access. The system is designed to provide real-time updates via notifications sent to a mobile app or other notification service.

Key Features
Door Status Monitoring: Utilizes magnetic or contact sensors to detect whether the door is open or closed.
Real-time Notifications: Sends alerts to designated users when the door status changes, indicating possible theft or unauthorized entry.
Arduino Integration: Uses Arduino microcontrollers for data processing and interfacing with sensors.
Mobile App Integration: Integrates with a mobile application for receiving notifications and viewing door status remotely.
Customizable Alerts: Configurable to send notifications through various channels (e.g., SMS, email) based on user preferences.
Hardware Requirements
Arduino microcontroller (e.g., Arduino Uno, Arduino Mega)
Magnetic/contact sensors for door status detection
WiFi or Bluetooth module for communication (optional, depending on notification method)
Power source (e.g., battery, USB power adapter)
Software Requirements
Arduino IDE for programming the microcontroller
Mobile app development tools (if integrating with a custom mobile application)
Notification service integration (e.g., Firebase Cloud Messaging, Twilio for SMS)
Installation and Usage
Clone the repository to your local machine.
Set up the Arduino IDE with necessary libraries and dependencies.
Connect the Arduino hardware components according to the circuit diagram provided.
Upload the Arduino sketch to the microcontroller.
Install and configure the mobile app for receiving notifications (if applicable).
Test the system by opening and closing the door to verify notification functionality.
