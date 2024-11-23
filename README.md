# Voice-Controlled Object Detection System
## Overview
This project integrates voice commands with object detection to create an interactive system. Using a microphone, the system listens for activation commands and performs real-time object detection. Detected objects are announced via text-to-speech.

## Features
**Voice Commands:**
-  Say "Activate" to start object detection.
-  Say "Stop" to stop the object detection.
-  Say "Exit" to terminate the program.


**Object Detection:**
-  Detects objects using the YOLOv8 model.
-  Displays bounding boxes with labels on the video stream.
-  Announces the name of the detected objects.

## Credits
-  YOLOv8: For real-time object detection.
-  SpeechRecognition: For recognizing voice commands.
-  gTTS and Pygame: For converting text to speech.
