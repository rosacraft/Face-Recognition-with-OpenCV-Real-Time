# Real-Time Face Recognition System
A real-time face recognition system built with Python, OpenCV, and the `face_recognition` library.

## Features
* Real-time face detection using webcam
* Face recognition from a custom dataset with multiple images per person

## Technologies Used
* Python 3.13
* OpenCV
* face_recognition
* NumPy
* dlib

## Installation
Clone the repository:
```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

## Dataset
Create or use our `known_people` folder.
Each person should have their own folder containing one or more images:

## Run
```bash
python main.py
```
Press `Q` to exit the application.

The program:
1. Loads all known faces.
2. Computes an average face encoding for each person.
3. Opens the webcam.
4. Detects and recognizes faces in real time.
5. Draws a bounding box and displays the name.

This project is for educational purposes.
