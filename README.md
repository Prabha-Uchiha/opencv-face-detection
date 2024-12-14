# opencv-face-detection
 Real-time face detection using OpenCV and a pre-trained Caffe model. The project captures video from a webcam, detects faces, and displays bounding boxes around them with confidence scores and inference time.

# Real-time Face Detection using OpenCV

This project demonstrates real-time face detection using OpenCV's DNN module and a pre-trained Caffe model. The code captures video from a webcam, detects faces, and displays bounding boxes around detected faces along with the confidence score and inference time.

## Features
- Real-time face detection using a pre-trained Caffe model (`res10_300x300_ssd_iter_140000_fp16.caffemodel`).
- Displays bounding boxes around faces with a confidence score.
- Shows inference time for each frame.
- Downloads and extracts assets (pre-trained model and configuration file) from a URL if not present.

## Requirements
- Python 3.x
- OpenCV (`opencv-python` and `opencv-python-headless`)
- Caffe model files (downloaded automatically)
- A webcam or video source for input

## Installation

### 1. Install Dependencies
To run this project, first, install the required dependencies:

```bash
pip install opencv-python opencv-python-headless

