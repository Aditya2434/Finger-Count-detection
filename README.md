# Finger-Count-detection

Finger Counting Using Hand Tracking

Overview
This project is a real-time finger-counting application that uses computer vision techniques to detect and count the number of fingers a user raises in front of a camera. It leverages OpenCV for image processing and MediaPipe's hand-tracking module to accurately identify hand landmarks.

Features
Real-Time Hand Detection: Utilizes MediaPipe's hand-tracking technology to detect hands and track landmarks with high accuracy.
Finger Counting: Identifies which fingers are raised or folded to compute the total count of fingers raised.
Custom Overlays: Displays images based on the number of fingers detected, enhancing visual feedback.
FPS Display: Provides real-time feedback on the application's performance by displaying frames per second (FPS).
Installation
To run this project, you need to have Python installed along with the following libraries:

OpenCV
MediaPipe
You can install the required libraries using pip:

pip install opencv-python mediapipe

How It Works
Hand Detection and Landmark Extraction: The application captures video from a webcam and uses MediaPipe to detect hands and extract landmarks for each detected hand.
Finger Counting Algorithm: By analyzing the positions of key landmarks, the algorithm determines which fingers are raised and computes the total number.
Overlay Display: Based on the number of fingers detected, a corresponding image is displayed as an overlay on the video feed.
Performance Monitoring: The application calculates and displays the FPS to monitor real-time performance.

Clone the repository:

git clone https://github.com/Aditya2434/Finger-Count-detection.git

Project Structure
FingerCount.py: The main script that captures video, detects hands, counts fingers, and displays the results.
HandTrackingModule.py: A custom module for hand detection and landmark extraction using MediaPipe.
FingerImages/: A folder containing images used for overlays based on the number of fingers detected.

Contributing
Feel free to fork this project, create a pull request, or open an issue if you have suggestions or improvements!
