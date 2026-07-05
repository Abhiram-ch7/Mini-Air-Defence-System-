# Mini-Air-Defence-System-
This project is an AI-powered Mini Air Defence System using YOLOv11, Arduino, Computer Vision, and IoT for real-time target detection, autonomous tracking, radar visualization, servo-based engagement, and Telegram alerts.Unlike the default YOLO model trained on the COCO dataset, this project uses a custom dataset specifically prepared for aerial object detection.

The model can detect the following objects:

* Drone

* Bird

* Helicopter

* Airplane


## Features

- Real-time object detection
- Custom-trained YOLO11 object detection model
- YOLOv11 based target classification
- Arduino servo control
- Radar visualization
- Telegram alerts
- Manual firing mode
- Automatic target detection
- CUDA GPU acceleration


## Technologies

- Python
- OpenCV
- YOLOv11
- Arduino
- Processing
- CPS

## Hardware

- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motors
- Webcam

## Applications

- Smart Surveillance
- Restricted Area Security
- CPS Research
  Mini-Air-Defence-System


## Project Structure


├── Arduino

├── Processing

├── Python

│   ├── main.py

│   ├── best.pt

│   └── requirements.txt

  
## Installation

Clone the repository.

git clone (https://github.com/Abhiram-ch7/Mini-Air-Defence-System-)
Move into the project directory.

cd Mini-Air-Defence-System
Install the required libraries.

pip install -r requirements.txt
Run the project.

python main.py
## How It Works

1. The webcam captures live video.

2. The custom YOLO11 model detects aerial objects.

3. If a valid target is detected, the Arduino receives the command through serial communication.

4. The turret performs the configured action.

5. The detected frame is saved.

6. A Telegram notification with the captured image is sent.

## Author

Chunduru Venkata Abhiram

