# Virtual Mouse using Hand Gestures

This Python script enables you to control your computer's mouse cursor using hand gestures captured through your webcam. It utilizes the following libraries:

- **OpenCV (cv2)**: For capturing video frames from the webcam and processing them.
- **MediaPipe**: Specifically, the Hand module from MediaPipe is used to detect and recognize hand landmarks.
- **PyAutoGUI**: To control the mouse movements and clicks based on the detected hand gestures.

## Features

- **Hand Gesture Recognition**: The script detects the landmarks of your hand using the MediaPipe library, allowing you to control your computer's mouse cursor with hand movements.
- **Click Actions**: By forming specific hand gestures, such as bringing the index finger close to the thumb, you can perform left-click actions.
- **Responsive Cursor Movement**: The mouse cursor moves smoothly according to the movement of your hand.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- PyAutoGUI

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies using pip:



## Usage

1. Run the `main.py` script.
2. Ensure your webcam is correctly positioned and there's adequate lighting.
3. Hold your hand in front of the webcam, and the script will detect and track your hand movements.
4. Make specific gestures, such as closing your index finger and thumb, to perform left-click actions.
5. To exit the program, press `esc`.



