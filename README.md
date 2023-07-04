# Object Tracker using OpenCV and Python

## Introduction
This is a simple object tracking program using OpenCV and Python. The program tracks content inside a bounding\ box and draws a rectangle around it. The program uses the OpenCV library to capture video from the webcam and uses the CSRT algorithm to track the object.

## Demo
![Object Tracker](demo.gif)

## Requirements
* Python 3.6+
  * opencv-python

## Installation
To install the required packages, run the following command in the terminal:
```python -m pip install opencv-contrib-python```

## Usage
To run the program, simply run the following command in the terminal:
```
python object_tracker.py
```
The program will open a window with the video feed from the webcam. To select the object to track, simply draw a bounding box around it using the mouse. Once the bounding box is drawn, press the spacebar to start tracking the object. To stop tracking, press the spacebar again. To exit the program, press the 'q' key.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.