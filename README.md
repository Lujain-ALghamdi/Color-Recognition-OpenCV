# Color Recognition Using OpenCV

## Project Description

This project implements real-time color recognition using OpenCV.

The system captures video from a webcam, converts the image from BGR color space to HSV, detects specific colors using predefined color ranges, and draws bounding boxes around detected objects.

The project can recognize three colors:
- Red
- Green
- Blue

https://github.com/user-attachments/assets/93c4c883-366f-45df-9cf8-f5245cfc1271

## Technologies Used

- Python
- OpenCV
- NumPy
- Anaconda
- Visual Studio Code

## Libraries Used

- OpenCV: For computer vision and color detection.
- NumPy: For image data processing.

## Installation

Follow these steps to set up and run the project on your local machine:

### 1. Clone the Repository

```bash
git clone https://github.com/Lujain-ALghamdi/Color-Recognition-OpenCV.git
```

### 2. Navigate to the Project Directory

```bash
cd Color-Recognition-OpenCV
```

### 3. Install the Required Libraries

Make sure Python 3 is installed, then install the required dependencies:

```bash
pip install opencv-python numpy jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the `openCV.ipynb` file from the Jupyter interface.

### 5. Run the Project

Run the notebook cells in order. Make sure your webcam is connected and that Jupyter has permission to access the camera.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Jupyter Notebook
- Webcam
  
## Features

- Real-time color recognition using OpenCV
- Detects colors from images or camera input
- Simple and lightweight Python implementation

## How It Works

1. Open the webcam using OpenCV.
2. Capture video frames in real-time.
3. Convert the frames from BGR color space to HSV color space.
4. Define HSV ranges for Red, Green, and Blue colors.
5. Create color masks to identify specific colors.
6. Detect colored objects using contours.
7. Draw bounding boxes around detected objects.
8. Display the detected color name on the screen.


## Camera Selection

The camera index can be changed depending on the available camera devices.

Example:

```python
cv2.VideoCapture(1)
