# ✋ Hand Gesture Recognition using OpenCV

## 🎯 Overview

This project demonstrates **real-time hand gesture recognition** using **OpenCV**. The model detects hand gestures and identifies specific gestures like "ONE", "TWO", "THREE", etc., based on convexity defects in the hand contour.  

✨ **Use Case**: This system can empower **specially-abled children** to study online without needing to attend special schools, by enabling interaction through hand gestures.

## 🛠️ Features

- Real-time hand gesture recognition using a webcam.
- Detects and identifies gestures like **ONE**, **TWO**, **THREE**, and more.
- Visualizes contours, convex hulls, and defects for understanding gesture anatomy.
- Accessible and adaptable for educational or interactive applications.

## 📷 How It Works

1. **Hand Detection**:
   - A sub-window (ROI) isolates the hand for detection.
   - Converts the image to grayscale and applies Gaussian blur.

2. **Thresholding**:
   - Thresholding is used to separate the hand region from the background.

3. **Contour and Convex Hull**:
   - Contours are extracted from the thresholded image.
   - Convex hull and convexity defects are computed to analyze the hand's shape.

4. **Gesture Recognition**:
   - Defects are analyzed using the **cosine rule** to determine the angle between fingers.
   - Gestures are recognized based on the number of defects detected.

5. **Real-Time Feedback**:
   - Displays the detected gesture on the screen in real-time.

---



