# Face-Recognition
Automatic attendance calculator using face detection
This project was done with this fantastic “Open Source Computer Vision Library”, the OpenCV.
### Mainly divided into 3 phases
* Face Detection and Data Gathering
* Training the data
* Face Recognition
### 1.Face Detection and Data Gathering
The most basic task on Face Recognition "Face Detecting". Before anything, you must "capture" a face (Phase 1) in order to recognize it, when compared with a new face captured on future (Phase 3).The classifier used in this project is "Haarcascade_frontalface_default".
### 2.Training
The data from our dataset and “trainer” the OpenCV Recognizer is taken. This is done directly by a specific OpenCV function. The result will be a .yml file that will be saved on a “trainer/” directory.
### 3.Face Recognition
Here, face present on our camera is captured and if this person had his face captured and trained before, our recognizer will make a “prediction” returning its id and an index, shown how confident the recognizer is with this match.
