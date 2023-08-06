# Face-Detection
Simple Face Detection python program to detect faces in the webcam feed and draw a bounding box around it.

![Hand_Landmarks_detection_demo](https://github.com/shaikamirgh/Face-Detection/blob/main/FaceOutput1.jpg)

You can also use it to detect faces in images by changing the input source to the image path.
and add in your own classifier to detect other objects.
Here I'm using the haarcascade_frontalface_default.xml classifier to detect faces.


To use it, just git clone the repo and run the FaceDetection.py file.
```bash
git clone https://github.com/shaikamirgh/Face-Detection

cd Face-Detection
```

## Installation
Run this in your terminal to install libraries.

```bash
pip install opencv-python
pip install mediapipe
pip install numpy
```
or just run the following command to install all the dependencies at once.
```bash
pip install -r requirements.txt
```

## Usage
```bash
python FaceDetection.py
```
or just click run in VS code.

