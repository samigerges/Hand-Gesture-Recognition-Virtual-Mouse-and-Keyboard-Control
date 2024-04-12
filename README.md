# Hand-Gesture-Recognition-Virtual-Mouse-and-Keyboard-Control

This repository contains Python code for hand gesture recognition, virtual mouse control, and keyboard emulation using computer vision techniques. It leverages the following technologies:

.OpenCV: Utilized for image processing and computer vision tasks such as hand detection and tracking.
.MediaPipe: Provides pre-trained models for hand landmark detection and gesture recognition.
.PyAutoGUI: Enables control of the mouse cursor, interaction with the desktop environment, and keyboard emulation.

Features:
1.Hand Detection and Tracking:

Utilizes the MediaPipe library to detect and track the user's hand in real-time video streams.
Draws landmarks on detected hands for visualization.

2.Gesture Recognition:

Detects various hand gestures, including finger counting and finger positions, to perform actions such as mouse control and keyboard emulation.

3.Virtual Mouse Control:

Maps hand movements to control the mouse cursor on the screen.
Implements left-click, right-click, and scroll functionalities based on specific hand gestures.

4.Virtual Keyboard Control:

Emulates keyboard input based on hand gestures to simulate typing and control of keyboard functions.

Usage:
1.Hand Gesture Recognition:
Run the HandDetector class to detect hand gestures and visualize hand landmarks in real-time video streams.

2.Virtual Mouse Control:
Utilize the PyAutoGUI library to control the mouse cursor and perform actions such as clicking and scrolling based on detected hand gestures.

2.Virtual Keyboard Control:
Emulate keyboard input using the PyAutoGUI library based on specific hand gestures recognized by the system.

Dependencies:
.Python 3.x
.OpenCV
.MediaPipe
.PyAutoGUI
