# Color Recognition Using OpenCV

## Project Description

This project implements real-time color recognition using OpenCV.

The system captures video from a webcam, converts the image from BGR color space to HSV, detects specific colors using predefined color ranges, and draws bounding boxes around detected objects.

The project can recognize three colors:
- Red
- Green
- Blue




## Technologies Used

- Python
- OpenCV
- NumPy
- Anaconda
- Visual Studio Code


## Libraries Used

- OpenCV: For computer vision and color detection.
- NumPy: For image data processing.


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
