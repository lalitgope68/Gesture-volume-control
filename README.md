# Hand Gesture Volume Control using OpenCV & MediaPipe

This project enables **touchless control of system volume** using hand gestures via a webcam. By measuring the distance between the thumb and index finger, the script adjusts the volume accordingly.

## 🎯 Features

- Real-time hand detection using **MediaPipe**.
- Volume control by measuring distance between **thumb and index finger**.
- Volume bar overlay with visual feedback on screen.
- Smooth volume transition and gesture validation.
- Displays current FPS and volume level for monitoring.

## 🛠️ Technologies Used

- **OpenCV** – Image processing and UI rendering.
- **MediaPipe (Custom HandTrackingModule)** – Hand landmark detection.
- **PyCaw** – Python Core Audio Windows Library to control system volume.
- **NumPy** – For interpolation and calculations.

## 📦 Requirements

- Python 3.7+
- Webcam (external or built-in)
- Installed Python packages:
  ```bash
  pip install opencv-python mediapipe pycaw comtypes numpy

