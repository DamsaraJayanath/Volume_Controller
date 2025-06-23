Hand Gesture-Based Volume Control System
This project is a real-time hand gesture-based volume control system built using Python, OpenCV, MediaPipe, and PyCAW. It allows users to control the system volume by simply moving their fingers in front of the webcam.

🔧 Features
Detects hand landmarks using MediaPipe

Tracks thumb and index finger tips

Calculates the distance between fingers to adjust system volume

Displays a live volume bar and percentage on the screen

Provides real-time feedback with smooth and responsive UI

Runs directly from webcam input

🛠 Technologies Used
Python

OpenCV

MediaPipe

Pycaw (Python Core Audio Windows Library)

NumPy

📂 File Structure
handTrack.py: Hand tracking module using MediaPipe

test.py: Main application to control volume based on finger distance

📌 How It Works
The system captures video from the webcam.

Detects the user's hand and tracks landmarks.

Measures the distance between the thumb tip and index finger tip.

Maps that distance to the system's audio volume level.

Updates the volume and shows a visual representation on the screen.
