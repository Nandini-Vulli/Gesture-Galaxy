 🖐 Gesture Galaxy – Game Application on Sign Language

Gesture Galaxy is a fun and interactive platform designed to teach sign language through real-time gesture recognition and engaging mini-games. It combines the power of computer vision and machine learning to make learning accessible and enjoyable, especially for young learners and beginners.


🎯 Objectives

1. Enhance Accessibility
2. Improve Engagement
3. Encourage Retention
4. Promote Practical Learning
5. Ensure Adaptability


🛠️ Tech Stack

Frontend

1. HTML, CSS, JavaScript
2. Flask (Python-based framework)

Machine Learning & Computer Vision

1.MediaPipe – Hand landmark detection
2. OpenCV – Video processing
3. Random Forest Classifier – Gesture recognition
4. Scikit-learn, NumPy, TensorFlow

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

1. Python 3.x
2. Flask
3. OpenCV
4. MediaPipe
5. TensorFlow
6. Scikit-learn
7. NumPy

Hardware

1. Webcam-enabled system
2. At least 4 GB RAM
3. Internet (for online version)


🚀 Features

1. Real-time gesture detection and translation
2. Interactive mini-games for practicing signs
3. SignWriting integration for visual reinforcement
4. Text and voice outputs for better understanding
5. Progressive difficulty levels


📈 Future Enhancements

1. User Accounts: Personalized experience with saved progress
2. Progress Tracking: Analyze learning speed and efficiency
3. Advanced Models: Improve recognition with deep learning
4. Educational Integration: Collaborate with schools
5. Offline Mode: Access without internet


📚 References

Key resources used during development:

1. Stanford CS231n papers on gesture recognition
2. MediaPipe and OpenCV documentation
3. Research papers on educational games and sign language learning



