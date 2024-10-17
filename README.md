# Gesture-Controlled Virtual Mouse

This project allows users to control their computer's mouse using hand gestures detected via a webcam. It leverages Python, OpenCV, MediaPipe, and PyAutoGUI to track hand movements and map them to mouse functions such as cursor movement and clicking.

## Features
- Real-time hand gesture detection using a webcam.
- Cursor movement controlled by the index finger's position.
- Left mouse click performed by bringing the thumb and index finger together.

## Technologies Used
- **Python**: Programming language.
- **OpenCV**: For real-time video capture and image processing.
- **MediaPipe**: For hand landmark detection.
- **PyAutoGUI**: For controlling the mouse.

## How It Works
1. The webcam captures the video feed.
2. MediaPipe processes the video to detect hand landmarks (such as fingertips).
3. The index finger controls the mouse cursor's movement on the screen.
4. When the thumb and index finger come close together, a mouse click is triggered.

## Setup Instructions
1. Clone this repository to your local machine:
   ```bash
   git clone:- https://github.com/kingprince35/Gesture-Controlled-Virtual-Mouse/blob/main/thumb_finger_virtual_mouse.py 
