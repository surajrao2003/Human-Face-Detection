# Face Detection using OpenCV and Haar Cascades

[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](https://opencv.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)

A real-time face detection system implemented using Python and OpenCV, leveraging Haar feature-based cascade classifiers for efficient face detection in images and video streams.

## Table of Contents
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [About Face Detection](#-about-face-detection)
- [BrightSense Enhancement](#-brightsense-enhancement)
- [Documentation](#-documentation)

## Features
- Real-time face detection using webcam
- High accuracy face detection using Haar Cascades
- Integration with OpenCV for computer vision tasks

## Technologies Used
- Python 3.x
- OpenCV (cv2)
- NumPy
- Matplotlib (for visualization)
- Haar Cascade Classifier

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Human-Face-Detection.git
   cd Human-Face-Detection
   ```

2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the face detection script:
   ```bash
   python face_detection.py
   ```

2. Press 'q' to quit the application.

## Project Structure
```
Human-Face-Detection/
├── face_detection.py    # Main face detection script
├── haarcascade_frontalface_default.xml  # Pre-trained Haar Cascade model
├── requirements.txt     # Project dependencies
└── README.md           # Project documentation
```

## About Face Detection
Face detection is a fundamental computer vision technology that identifies and locates human faces in digital images or video frames. This implementation uses Haar feature-based cascade classifiers, an effective object detection method proposed by Paul Viola and Michael Jones in their 2001 paper, "Rapid Object Detection using a Boosted Cascade of Simple Features."

### How It Works
1. The system captures video frames from the webcam
2. Each frame is converted to grayscale for processing
3. The Haar Cascade classifier scans the image at different scales
4. Detected faces are highlighted with bounding boxes
5. The processed frame is displayed in real-time

## BrightSense Enhancement
I encountered challenges in recognizing faces under varying lighting conditions. To address this issue, I developed BrightSense, a system designed to adjust brightness based on detected distances. This project enhanced face detection accuracy across different environments with varying lighting conditions.

## Documentation
- [Project PPT](https://docs.google.com/presentation/d/1e0vmbY6F83I9GmaH8D2ZEcaXehlpDGbP/edit?usp=sharing&ouid=105191186790125380243&rtpof=true&sd=true)
- [Project Report](https://drive.google.com/file/d/1LBdxuZEWiI-9gqcPyN9z9oD-qHFhJRBj/view?usp=sharing)
- [Working Demo Video](https://drive.google.com/file/d/12ZLr9cyhbyTYz9MWIBst0Tjez1baydjf/view?usp=sharing)

### BrightSense Documentation
- [BrightSense PPT](https://docs.google.com/presentation/d/1bndGP8R9k3IKqMpPGDFpAthG3LcXOAl5UYwC4_mEKc0/edit?usp=drive_link)
- [BrightSense Report](https://docs.google.com/document/d/1HV-TX6uW3hEVhUnwGSnAelkMzuj9ZBQue56XjTWuI9k/edit?usp=sharing)



