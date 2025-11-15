# Face-Detection-Recognition-System-Using-OpenCV
This project uses OpenCV to perform real-time face detection and recognition through a webcam. It captures face samples, trains an LBPH model, and verifies identities by matching live faces with stored images. The system supports dataset creation, model training, and accurate person verification.
📖 Overview

This application demonstrates a traditional face recognition workflow using OpenCV. It detects faces from the webcam, stores captured face samples, trains a recognition model, and verifies a user in real time. It is suitable for academic projects, biometric demonstrations, and learning computer vision.

✨ Features

🔹 Real-Time Face Detection

-->Uses Haar Cascade classifier

-->Detects faces from webcam feed

-->Draws bounding rectangles

🔹 Face Dataset Creation

-->Press c to capture samples

-->Saves 30 grayscale face images per person

-->Automatically organizes images in folders

🔹 Model Training

-->Uses LBPH (Local Binary Patterns Histograms) recognizer

->Trains with captured face samples

-->Generates label-to-name mapping

🔹 Face Recognition & Verification

-->Press v to verify a person

-->Predicts name and confidence

-->“Verified” vs. “Not Verified” displayed in real time


⚙️ Installation
pip install opencv-python opencv-contrib-python numpy

▶️ How to Run
python face_recognition.py

-->Keyboard Controls

Key	Function

-->c	Capture face samples

-->	Verify a person

-->q	Quit application

-->Face detection window

-->Capturing face samples

-->Verification screen

-->Dataset folder

🏁 Conclusion

This project delivers a complete face detection and recognition system using OpenCV. It includes dataset creation, model training, live detection, and verification — making it ideal for biometric applications, learning projects, and college submissions.
