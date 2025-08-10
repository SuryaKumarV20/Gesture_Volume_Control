<img width="810" height="634" alt="Screenshot 2025-08-10 101715" src="https://github.com/user-attachments/assets/958aa232-a85f-497b-9576-b6592e1b4b98" /># Gesture_Volume_Control
# 🎛️ Gesture-Based Volume Control

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)](https://opencv.org/)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-Latest-orange.svg)](https://mediapipe.dev/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A Python project that allows you to control your system's volume **using hand gestures** detected via your webcam.  
Perfect for touch-free, real-time control using **finger distance mapping** to adjust audio levels.

---

## 📌 Features
- 🖐 **Real-time hand tracking** using [MediaPipe](https://mediapipe.dev/).
- 🎚 **Volume control** by changing the distance between your thumb and index finger.
- 🎥 Works with any webcam.
- ⚡ Lightweight & fast — runs locally without internet.
- 💻 Cross-platform (Windows, macOS, Linux).

---

## 📂 Project Structure
GestureVolumeControl-main/
│
├── VolumeHandControl.py # Main script to run gesture control
├── handTrackingModule.py # Helper module for hand detection
├── README.md # Project documentation


---

## 🚀 Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/SuryaKumarV20/Gesture_Volume_Control.git
   cd Gesture_Volume_Control
   
2. Install Dependencies
Run the following command to install everything at once:
pip install opencv-python mediapipe pycaw numpy comtypes

3.Run the Project
python VolumeHandControl.py


🛠 How It Works:
The script uses MediaPipe Hands to detect landmarks on your hand.
The distance between your thumb tip and index finger tip is calculated.
This distance is mapped to your system's volume range using pycaw.
Move fingers apart to increase volume, bring them closer to decrease it.

📸 Screenshot:
<img width="810" height="634" alt="Screenshot 2025-08-10 101715" src="https://github.com/user-attachments/assets/cffcf453-dd9a-4f43-9fd9-d347af4c89e6" />





