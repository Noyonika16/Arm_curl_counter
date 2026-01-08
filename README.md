Arm Curl Counter using MediaPipe: 

<img width="590" height="608" alt="image" src="https://github.com/user-attachments/assets/022cb688-7fb9-4d19-a1df-cbaf3cd6ea32" />


An AI-powered Arm Curl Counter that uses computer vision to detect human pose and automatically count arm curls in real time.
The project leverages MediaPipe for pose estimation and OpenCV for video processing.

Features:
Real-time arm curl detection
Automatic repetition counting
Angle-based movement analysis
Works with webcam input
Lightweight and fast

How It Works:
Captures live video from the camera of your laptop/pc
Detects human body landmarks using MediaPipe Pose
Tracks shoulder, elbow, and wrist
Calculates elbow joint angle
Counts one curl when: Arm moves from extended → contracted → extended

Tech Stack: Python, MediaPipe, OpenCV, NumPy

Uses joint angle calculation
Thresholds:
        Angle < 30° → Arm curled
        Angle > 160° → Arm extended
        A full cycle = 1 curl counted

Use Cases:
Fitness tracking
Home workout monitoring
AI-based exercise analysis
Computer vision learning project

Author: Noyonika Mukherjee
B.Tech Computer Science Student
Interest: AI, Computer Vision, Deep Learning, Reinforcement Learning
