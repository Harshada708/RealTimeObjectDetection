# Real-Time Object Detection Web App

This project is a real-time object detection web application built using YOLO and OpenCV, integrated with Flask. It allows users to perform object detection in real-time as well as from stored video files.


## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
  - [YOLO](#yolo)
  - [OpenCV](#opencv)
- [Features](#features)
- [Setup Instructions](#setup-instructions)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Real-Time Object Detection Web App is designed to showcase the power of machine learning and computer vision. By leveraging YOLO (You Only Look Once) and OpenCV, this app provides a platform for detecting objects in video streams in real-time.

## Technologies Used

### YOLO (You Only Look Once)

YOLO is a state-of-the-art, real-time object detection system. It is extremely fast and accurate, making it a popular choice for various applications. YOLO divides the image into a grid and predicts bounding boxes and probabilities for each region. These bounding boxes are weighted by the predicted probabilities.

### OpenCV

OpenCV (Open Source Computer Vision Library) is an open-source computer vision and machine learning software library. It contains more than 2500 optimized algorithms, which can be used for various tasks such as object detection, facial recognition, and image processing.

## Features

- **Real-Time Detection:** Stream video from a webcam and perform real-time object detection.
- **Stored Video Detection:** Upload a video file and perform object detection on it.
- **Bounding Boxes and Labels:** Annotate detected objects with bounding boxes and labels.
- **User-Friendly Interface:** A clean and intuitive web interface built with React and Flask.

## Setup Instructions

### Prerequisites

- Python 3.7 or higher
- Virtual environment tool (recommended: `venv` or `virtualenv`)

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Harshada708/RealTimeObjectDetection.git
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Running the Application

1. **Start the Flask server:**

    ```bash
    python flaskapp.py
    ```

2. **Open your web browser and go to:**

    ```
    http://127.0.0.1:5000
    ```

## Usage

- **Real-Time Detection:**
  - Click on the "Start Real-Time Detection" button to start streaming from your webcam.
  - The app will display the video feed with detected objects annotated in real-time.

- **Stored Video Detection:**
  - Upload a video file by clicking on the "Upload Video" button.
  - The app will process the video and display the annotated video.

## Contributing

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) to get started.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Output

![image 1](https://github.com/user-attachments/assets/b54690de-a6c9-4cb3-8d4b-584c6e0e3d29)

![image 2](https://github.com/user-attachments/assets/c2aa86dd-ef97-4934-bd97-19798d33c081)



![image 3](https://github.com/user-attachments/assets/23c22bb3-f247-47fe-a95c-b6dcfb58c28c)

![image 4](https://github.com/user-attachments/assets/0a03f9cc-fd5f-4764-8b6c-b97c28ee90ae)

