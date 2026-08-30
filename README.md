# Traffic Sign Detection using YOLOv8

A computer vision project that uses **YOLOv8** to detect and localize traffic signs in images and video using a custom dataset prepared with Roboflow.

## Overview

This project demonstrates object detection using the YOLOv8 architecture. A custom traffic-sign dataset was used to train the model so that it could identify traffic signs and locate them using bounding boxes.

The trained model produces the detected object's class along with a confidence score, making it possible to identify traffic signs in unseen images and video.

## Features

- Custom traffic-sign dataset
- YOLOv8-based object detection
- Bounding-box localization
- Confidence score for detections
- Image and video inference
- Custom-trained detection model
- Dataset prepared using Roboflow

## Technologies Used

- Python
- YOLOv8
- Ultralytics
- Roboflow
- Google Colab

## Dataset

The dataset was obtained/prepared using **Roboflow** and contains annotated traffic-sign images suitable for object detection.

Each object is annotated using bounding boxes and corresponding class labels.

The dataset was divided into training and validation/testing sets for model development and evaluation.

## Model

The project uses **YOLOv8** for object detection.

YOLO (You Only Look Once) performs object detection by predicting:

- Object class
- Bounding box coordinates
- Confidence score

 ## 👨‍💻 Author

**Mohammad Arif Khan**  
*B.Tech. in Computer Engineering*  
**Aligarh Muslim University**
