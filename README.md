Adafruit MEMENTO Camera Project (Arduino IDE)
📷 Project Overview

This project demonstrates how to use the Adafruit MEMENTO Camera Board with the Arduino IDE
 for basic camera initialization and image capture using the ESP32-S3 microcontroller.

The project can be extended for:

Smart camera systems
IoT image capture
AI vision projects
SD card image storage
Wi-Fi image streaming
🛠 Hardware Required
Component	Quantity
Adafruit MEMENTO Camera Board	1
USB-C Cable	1
Computer/Laptop	1

Optional:

MicroSD card
Li-ion battery
💻 Software Required
Arduino IDE
ESP32 Board Package
USB Drivers (if needed)
⚙ Arduino IDE Setup
Step 1 — Install Arduino IDE

Download from:

Arduino IDE Download

Step 2 — Add ESP32 Board URL

Open:

File → Preferences

Add this URL in:

Additional Boards Manager URLs

https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

Step 3 — Install ESP32 Package

Go to:

Tools → Board → Boards Manager

Search:

ESP32

Install:

ESP32 by Espressif Systems
🔌 Board Connection

Connect the MEMENTO board using the USB-C port.

Select board:

Adafruit pyCamera S3 

Choose the correct COM port from:

Tools → Port
📸 Camera Test Code

▶ Upload Steps
Connect USB-C cable
Open Arduino IDE
Select board and COM port
Paste code
Click Upload

Open Serial Monitor:

115200 baud

Expected output:

Starting Camera...
Camera Ready!
Capturing...
📦 Features
ESP32-S3 based
Camera support
USB programming
Display support
Wi-Fi + BLE
Arduino compatible
🚀 Future Improvements
Save photos to SD card
Live camera streaming
Motion detection
AI image recognition
Web server camera feed
