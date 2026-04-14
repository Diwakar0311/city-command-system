# Smart Traffic System (AI Based Project)
### Project Description
This project is built to simulate a basic city traffic monitoring system using AI. The main idea is to detect vehicles in a video and check whether traffic rules are being followed or not.

The goal of this project is to create a working system that can be used as a foundation for future smart traffic control systems in cities.

### What this project does
* Detects vehicles from video input
* Tracks each vehicle using a unique ID
* Simulates a traffic signal system (Red, Yellow, Green)
* Detects traffic violations when a vehicle crosses the line on red signal
* Saves evidence images of violations
* Shows total violation count
* Provides a Streamlit dashboard for live video processing

### Technologies Used
* Python
* OpenCV (Computer Vision)
* YOLOv8 (Ultralytics AI model)
* Streamlit (for dashboard UI)
* Time-based logic for traffic signal system

### How it works
1 A video is loaded into the system
2 YOLO model detects vehicles in each frame
3 Each vehicle is assigned a tracking ID
4 A virtual traffic signal runs on a timer
5 If a vehicle crosses the stop line during RED signal:
