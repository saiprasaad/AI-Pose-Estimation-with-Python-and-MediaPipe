Rep Counter using MediaPipe and OpenCV
======================================

This Python script utilizes the MediaPipe library along with OpenCV to count repetitions of a specific exercise based on the movement of a person's arm. The program detects the keypoints of a person's pose using the MediaPipe Pose model and calculates the angle between the shoulder, elbow, and wrist to determine the movement phase (up or down) of the exercise.

Features
--------

*   Real-time pose detection using MediaPipe
*   Angle calculation to determine exercise phase
*   Repetition counting based on movement phases
*   Visual feedback through OpenCV window
*   Simple and easy to understand implementation

Dependencies
------------

*   OpenCV (`cv2`)
*   MediaPipe (`mediapipe`)

Configuration
-------------

*   You can adjust the `min_detection_confidence` and `min_tracking_confidence` parameters of the `Pose` object to fine-tune the performance of the pose detection.
