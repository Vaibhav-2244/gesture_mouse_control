# Gesture Mouse Control
================================================

This project uses hand gestures to control a virtual mouse using Python, OpenCV, MediaPipe, and PyAutoGUI.

## Features

* Move the mouse cursor using hand gestures
* Perform left, right, and double clicks using hand gestures
* Take screenshots using hand gestures

## Requirements

* Python
* OpenCV
* MediaPipe
* PyAutoGUI
* pynput

## Usage

1. Clone the repository: `git clone https://github.com/Vaibhav-2244/gesture-mouse-control.git`
2. Install the required packages: `pip install -r requirements.txt`
3. Run the script: `python main.py`

## How it works

The script uses MediaPipe's hand tracking model to detect hand gestures. It then uses OpenCV to process the video feed and PyAutoGUI to control the mouse cursor. The util.py file contains utility functions for calculating distances and angles between hand landmarks.

## Hand Gestures

### Move mouse cursor

Hold your hand with fingers extended and move your index finger to control the cursor.

### Left click

Make a fist with your thumb on top of your index finger.

### Right click

Make a fist with your thumb on top of your middle finger.

### Double click

Make a fist with your thumb on top of your ring finger.

### Take screenshot

Make a fist with your thumb on top of your pinky finger.
