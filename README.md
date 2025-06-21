 🖐 Gesture Galaxy – Game Application on Sign Language

Gesture Galaxy is a fun and interactive platform designed to teach sign language through real-time gesture recognition and engaging mini-games. It combines the power of computer vision and machine learning to make learning accessible and enjoyable, especially for young learners and beginners.


🎯 Objectives

Enhance Accessibility: Provide an inclusive learning tool for all users.
Improve Engagement: Use game-based learning with puzzles and challenges.
Encourage Retention: Reinforce memory with rewards and repetition.
Promote Practical Learning: Enable hands-on sign language practice.
Ensure Adaptability: Support various learning speeds and levels.


🛠️ Tech Stack

Frontend

HTML, CSS, JavaScript
Flask (Python-based framework)

Machine Learning & Computer Vision

MediaPipe – Hand landmark detection
OpenCV – Video processing
Random Forest Classifier – Gesture recognition
Scikit-learn, NumPy, TensorFlow

Architecture Overview

1. User Interface: Choose categories like alphabets, colors, animals, etc.
2. Sign Input: Webcam captures user hand gestures.
3. Processing Module:

   - MediaPipe extracts hand landmarks.
   - Random Forest model predicts the sign.
4. Output Module: Displays corresponding text/image/video.
5. Game Interface: Includes memory games and SignWriting elements.


💻 System Requirements

Software

Python 3.x
Flask
OpenCV
MediaPipe
TensorFlow
Scikit-learn
NumPy

Hardware

Webcam-enabled system
At least 4 GB RAM
Internet (for online version)


🚀 Features

Real-time gesture detection and translation
Interactive mini-games for practicing signs
SignWriting integration for visual reinforcement
Text and voice outputs for better understanding
Progressive difficulty levels


📈 Future Enhancements

User Accounts: Personalized experience with saved progress
Progress Tracking: Analyze learning speed and efficiency
Advanced Models: Improve recognition with deep learning
Educational Integration: Collaborate with schools
Offline Mode: Access without internet


📚 References

Key resources used during development:

Stanford CS231n papers on gesture recognition
MediaPipe and OpenCV documentation
Research papers on educational games and sign language learning



