# Hand Gesture Volume Control

A Python project that controls your system volume using hand gestures captured via webcam.  
It uses OpenCV for video processing, MediaPipe for hand tracking, and Pycaw for Windows audio control.

---

## **Features**

- Adjust system volume by moving your thumb and index finger.
- Visual feedback with dynamic volume bar.
- FPS counter for performance monitoring.
- Works on Windows (requires Pycaw for audio control).

---

## **Requirements**

- Python 3.8 or higher
- Packages:
  - `opencv-python`
  - `numpy`
  - `mediapipe`
  - `pycaw`
  - `comtypes`

You can install all dependencies using:

```bash
pip install -r requirements.txt
