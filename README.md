# Netlytics

## Introduction
Netlytics analyzes Tennis players in a video to measure their speed, ball shot speed and number of shots. Netlytics will detect players and the tennis ball using YOLO and also utilizes CNNs to extract court keypoints.

## Table of Contents
- [Installation](#installation)
- [Models Used](#models-used)
- [Training](#training)
- [Features](#features)

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/ramindu-Nimex/Netlytics.git
```

2. Install dependencies 
```bash
Netlytics> pip install ultralytics pandas numpy supervision opencv-python
```

## Models Used
* YOLO v8 for player detection
* Fine Tuned YOLO for tennis ball detection
* Court Key point extraction

* Trained YOLOV5 model: https://drive.google.com/file/d/1UZwiG1jkWgce9lNhxJ2L0NVjX1vGM05U/view?usp=sharing
* Trained tennis court key point model: https://drive.google.com/file/d/1QrTOF1ToQ4plsSZbkBs3zOLkVt3MBlta/view?usp=sharing

## Training
* Tennis ball detetcor with YOLO: training/tennis_ball_detector_training.ipynb
* Tennis court keypoint with Pytorch: training/tennis_court_keypoints_training.ipynb

## Features
* python3.8
* ultralytics
* pytroch
* pandas
* numpy 
* opencv
* supervision

## Output Videos
Here is a screenshot from one of the output videos:

![Screenshot](output_videos/screenshot.jpeg)

## Copyright
© 2025 # Netlytics. All rights reserved.