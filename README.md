# Drowsiness-detection-using-computer-vision-and-OpenCV

This project is a Python-based drowsiness detection system that can detect when a person is becoming drowsy or falling asleep while driving. The system uses computer vision techniques to analyze the position and movement of the eyes to determine whether the person is becoming drowsy. If drowsiness is detected, the system can alert the person with an alarm or notification to prevent accidents.

## Dependencies

The project requires the following dependencies to be installed:\
Python 3\
OpenCV\
dlib

You can install these dependencies using pip:
```bash
pip install opencv-python
pip install dlib

```
## Usage

To use the drowsiness detection system, simply run the 'detection.py' script:
python detection.py

The system will start analyzing the video feed from your computer's camera and detect drowsiness in real-time. If drowsiness is detected, an alarm will sound to alert the person.

## Files

The project consists of the following files:

1)'Drowsiness Detection using open cv and computer vision.ipynb': The main Python script that contains the code for the drowsiness detection system.\
2)'landmark.dat': A pre-trained model file that contains the facial landmark data required for the detection process.\
3)'alert(1).mp3': A audio file to get alert sound when the user gets asleep with and warning indication.\

