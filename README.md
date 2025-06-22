# HandTrackingPy
🖐️ Hand Tracking and Finger Counter with Python
This project is a real-time hand tracking and finger counting application built using Python and OpenCV. The program uses your computer's camera to detect your hand and count how many fingers you are holding up. The number of fingers is then displayed live on the video feed.

📸 How It Works
The program opens your camera and continuously reads video frames.

It uses MediaPipe or OpenCV with landmarks detection to track your hand.

Based on the position of each finger, it determines how many fingers are raised.

The detected number is shown directly on the camera feed in real time.

🧰 Technologies Used
Python

OpenCV

MediaPipe (for hand landmark detection)

NumPy (optional for math operations)

🚀 Features
Real-time hand tracking

Accurate finger counting

Visual overlay showing the number of fingers detected

Works on most laptops and webcams

▶️ How to Run
Install the required libraries:

pip install opencv-python mediapipe
Run the script:

python hand_tracking.py
Allow camera access, and raise your hand in front of the camera. The app will show how many fingers are raised!
