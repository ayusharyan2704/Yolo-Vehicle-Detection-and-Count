# Yolo v8 -Vehicle-Detection-and-Count

This project is aimed at implementing vehicle detection using YOLO (You Only Look Once) algorithm. It uses pre-trained YOLO model to detect vehicles in a given video stream or video file.

## Introduction

This repository contains code for detecting vehicles in a video using YOLO algorithm. YOLO is a popular deep learning algorithm known for its real-time object detection capabilities.

## Features

- Real-time vehicle detection using YOLO algorithm
- Counting of vehicles crossing predefined lines
- Visualization of vehicle counts

## Detecting Vehicles 
![image](https://github.com/ayusharyan2704/Yolo-Vehicle-Detection-and-Count/assets/152168191/4a177c78-bbf9-485b-b975-2a4ed20ee580)

![image](https://github.com/ayusharyan2704/Yolo-Vehicle-Detection-and-Count/assets/152168191/3b3e9d14-4926-4cbd-b0e0-f87029421f55)

![image](https://github.com/ayusharyan2704/Yolo-Vehicle-Detection-and-Count/assets/152168191/04f5a34f-2ce2-44ba-9774-7230a6f29b29)



## Requirements

- Python 3.x
- OpenCV
- Pandas
- Ultralytics YOLO
- Tracker (External dependency)

## Installation

1. Clone the repository:

git clone https://github.com/ayusharyan2704/Yolo-Vehicle-Detection-and-Count.git

2. Download pre-trained YOLO model weights from [Ultralytics YOLO](https://github.com/ultralytics/yolov5) and place them in the `weights/` directory.

## Usage

1. Replace `trafficvideo.mp4` with the path to your video file in the code (`cap=cv2.VideoCapture('trafficvideo.mp4')`).
2. Run the script:python vehicle_detection.py
3. Press 'q' to quit the video stream.

## Configuration

- `class_list`: List of classes detected by YOLO model
- `tracker`: Instance of the tracker class for object tracking
- `counter_down`: List to store IDs of vehicles passing down a predefined line
- `counter_up`: List to store IDs of vehicles passing up a predefined line


## Acknowledgments

- The YOLO algorithm was originally developed by Joseph Redmon et al.
- The YOLOv5 model and Ultralytics YOLO Python package are maintained by Ultralytics LLC.
- The tracker module used in this project is adapted from an external source (not provided in the code snippet).






