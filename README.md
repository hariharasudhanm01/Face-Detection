# Face Detection Using MediaPipe

## Overview

This project implements a real-time face detection system using the [MediaPipe](https://mediapipe.dev) framework. MediaPipe provides a fast and efficient pipeline for detecting and tracking faces across video frames. This project is ideal for applications requiring accurate face detection with minimal computational overhead.

## Features

- Real-time face detection
- High accuracy with low latency
- Easy-to-integrate with other computer vision systems
- Supports both video files and webcam input

## Installation

### Prerequisites

- Python 3.7+
- OpenCV
- MediaPipe

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/hariharasudhanm01/Face-Detection/
   cd face-detection-mediapipe
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Running the Face Detection

To run the face detection on a webcam feed:
```bash
python face_detection.py
```

### Output

The program will display the video with detected faces highlighted by bounding boxes. The number of detected faces is displayed on the screen.

## Project Structure

- `face_detection.py`: Main script for running face detection.
- `requirements.txt`: List of dependencies.
- `README.md`: Project documentation.

## How It Works

This project leverages MediaPipe’s Face Detection module, which uses machine learning models to detect facial landmarks with high precision. The detected faces are then tracked across frames to ensure real-time performance.

### Key Modules

- **MediaPipe Face Detection**: The core module used for detecting faces.
- **OpenCV**: Used for handling video input and output.

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## Acknowledgements

- [MediaPipe](https://mediapipe.dev) for providing the face detection framework.
- [OpenCV](https://opencv.org) for video handling.


