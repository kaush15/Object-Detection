# Real-Time Object Detection Using YOLO

## Overview

This project implements a real-time object detection system using the YOLO (You Only Look Once) deep learning model. The system can detect and localize objects in images, videos, and live webcam feeds with high accuracy and speed.

The project utilizes the Ultralytics YOLO framework along with OpenCV and Matplotlib for image processing and visualization.

## Features

* Object detection on images
* Object detection on video files
* Real-time object detection using webcam
* Bounding box visualization
* Support for YOLO pre-trained models
* Fast and efficient inference

## Technologies Used

* Python
* YOLO (Ultralytics)
* OpenCV
* Matplotlib
* Pillow
* Google Colab

## Installation

Install the required dependencies:

```bash
pip install ultralytics opencv-python-headless matplotlib pillow
```

## Project Workflow

1. Install required libraries.
2. Load the YOLO model.
3. Upload an image or video.
4. Perform object detection.
5. Draw bounding boxes around detected objects.
6. Display or save the processed output.
7. Enable real-time detection using webcam input.

## Usage

### Image Detection

* Upload an image.
* Run the YOLO model on the image.
* View the detected objects with bounding boxes.

### Video Detection

* Upload a video file.
* Process each frame using YOLO.
* Save the output as a processed video.

### Webcam Detection

* Capture an image using the webcam.
* Run object detection.
* Display detected objects in real time.

## Model

This project uses pre-trained YOLO models:

* YOLOv5n
* YOLOv8n

These lightweight models provide a balance between speed and detection accuracy.

## Future Improvements

* Custom object detection training
* Multi-object tracking
* Vehicle and pedestrian counting
* Face detection integration
* Deployment as a web application
* GPU optimization for faster inference

## Results

The system successfully detects multiple objects in images, videos, and webcam captures while displaying bounding boxes and class labels.

## Author

Developed as a Computer Vision and Deep Learning project using YOLO and OpenCV.
