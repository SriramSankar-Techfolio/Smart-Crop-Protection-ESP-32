![Smart Crop Protection System using ESP32-CAM](https://raw.githubusercontent.com/SriramSankar-Techfolio/Smart-Crop-Protection-ESP-32/main/file_00000000ac3061fda94e6138a7d74b42.png)
Smart Crop Protection System using ESP32-CAM

Overview
This smart system protects crop fields by detecting animals using both motion sensors and a camera. It instantly alerts the farmer through SMS and calls, while also triggering light and sound deterrents to scare animals away.

Key Features:

Animal Detection with ESP32-CAM – Captures real-time images when movement is detected
-IR and Ultrasonic Sensors– Monitor for intrusion near the crop boundary
-Farmer Alerts – Sends SMS and makes phone calls using GSM module
Instant Action– Flashes LED light and activates siren to scare away intruders

Components Used:

ESP32-CAM Module
IR Sensor
Ultrasonic Sensor
LED Light
Buzzer / Siren
GSM Module (SIM800L or similar)

How It Works:

1. Sensors detect motion near the field.
2. ESP32-CAM captures a photo of the intruder.
3. GSM module sends:
An SMS with alert
A phone call to the farmer
4. The system triggers:
A siren
A flashing LED to scare off the animal

Future Enhancements:

Upload captured images to cloud or mobile app
Use AI to identify animal type
Add night vision IR camera support

Skills & Tools Demonstrated:

ESP32-CAM integration & camera streaming
GSM-based messaging and call alerts
Arduino IDE programming
Sensor simulation in Proteus

Contact:
Feel free to reach out for collaboration or improvements!

