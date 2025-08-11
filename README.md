# 🏋️‍♂️ Push-Up Tracker using Python, OpenCV & MediaPipe

A real-time push-up counter powered by computer vision — no sensors, no wearables, just your webcam and smart pose estimation.

## 📹 Demo
https://www.linkedin.com/posts/siddhartha-reddy-054321341_python-opencv-mediapipe-activity-7360493210772598784-o8ko?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFWnnQABq0G5pIuH2HRM3JXaXmGVTg8aTxI


## 🛠️ Tech Stack

- **Python**
- **OpenCV**
- **MediaPipe**
- **NumPy**

## 🚀 How It Works

1. Captures webcam feed using OpenCV
2. Uses MediaPipe Pose to detect key landmarks
3. Calculates elbow angle to determine push-up motion
4. Counts reps and displays feedback in real time

cd pushup-tracker
pip install -r requirements.txt
python pushup_tracker.py
