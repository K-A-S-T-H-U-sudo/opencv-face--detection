# Face Detection using OpenCV Haar Cascade

## Project Overview
This project detects human faces in real-time using OpenCV and Haar Cascade Classifier.

## Features
- Real-time webcam face detection
- Face bounding box
- Fast detection using Haar Cascade

## Technologies Used
- Python
- OpenCV
- Haar Cascade Classifier

## Installation
pip install -r requirements.txt

## Run
python face_detection.py

## System Architecture
Webcam
   │
   ▼
Capture Frame
   │
   ▼
Convert to Grayscale
   │
   ▼
Haar Cascade Classifier
   │
   ▼
Detect Face
   │
   ▼
Draw Bounding Box
   │
   ▼
Display Output
