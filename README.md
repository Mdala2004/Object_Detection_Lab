# Real Time Object Detection Lab with YOLOv8
This project demonstrates real-time object detection and tracking using the YOLOv8 model.
It detects objects in images, videos, and live webcam feeds, drawing bounding boxes around detected objects and assigning tracker IDs.

The system uses:
- YOLOv8 for object detection
- OpenCV for video capture and visualization
- Ultralytics Python library for model integration
- The output shows labeled objects with bounding boxes and tracking IDs in real time.

## Features
- Real-time object detection from a webcam
- Object tracking across frames
- Detection in images and video files
- Bounding boxes with object labels
- Tracker IDs showing movement across frames
- Simple Python implementation

## Requirements
Before running the project, ensure you have:
Python 3.9 or newer
pip (Python package manager)

Recommended editor:
Visual Studio Code

Required Python libraries:
ultralytics
opencv-python

## Installation
Use pip install ultralytics opencv-python to download the Ultralytics library.
If you don't have Python on your computer, please visit www.python.org/downloads and download the latest version for Windows.

## How to run the project
Run the Python script from the command line or through your preferred IDE:
python lab_1.py

- To analyse a picture, go to source and modify the variable with the link to your preferred picture.
- To analyse a pre recorded video, go to source and modify the variable with the link to your preferred video.
- To analyse live video feed, go to source and modify the variable with "0". This will activate your webcam when running the script.

If you are using a webcam, the program will open a video window displaying live object detection results.
Terminate the python window from where you see the live feed to stop the program.
