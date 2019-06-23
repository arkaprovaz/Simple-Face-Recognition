# Simple Face Recognition

This program uses OpenCV and Haarcascade classifier to detect faces.

There are three programs.

`face_detection.py` is for detecting faces.

By changing the `max_face` variable in the `face_detection.py` script, the maximum number of faces detected can be changed.

`face_data.py` is used to train the custom face data.

`face_recognition.py` is the code to detect and recognize the faces based on the trained models.

all the trainned models save to the directory `face_data`

`face_data.py` is mandatory to run at least once before running the `face_recognition.py` otherwise it will not be able to find any face data.

Press `q` to terminate the program.
