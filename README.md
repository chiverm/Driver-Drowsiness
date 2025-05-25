# Driver Drowsiness Detection System

This project implements a real-time **Driver Drowsiness Detection System** using computer vision and deep learning. It monitors a driver's eye activity via webcam and triggers an alarm if drowsiness is detected, helping to prevent fatigue-related road accidents.

## 🚀 Features

- Real-time video feed processing
- Eye state detection (open/closed) using a trained CNN model
- Face and eye detection using Haar Cascade classifiers
- Sound alarm alert for drowsiness
- Lightweight and easy to run locally

## 🧠 How It Works

1. The webcam captures the driver's face in real-time.
2. Haar cascades detect the face, left eye, and right eye regions.
3. A pre-trained CNN model classifies eye state (open/closed).
4. If both eyes remain closed for a number of frames, an alarm is triggered to wake the driver.



