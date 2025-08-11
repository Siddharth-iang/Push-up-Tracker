# 🏋️‍♂️ Push-Up Tracker using Python, OpenCV & MediaPipe

A real-time push-up counter powered by computer vision — no sensors, no wearables, just your webcam and smart pose estimation.

## 📹 Demo


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
