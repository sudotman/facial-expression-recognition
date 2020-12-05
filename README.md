# Facial Expression Recognition
Keras modelled application to detect facial expression namely: anger, sadness, digust, surprise, neutral, fear, happiness.
Uses OpenCV for face detection.

# For dependencies installation / running:
>cd \path\to\Project\
>pip install pipenv

>pipenv install

>pipenv run python3 main.py

# To modify the video stream to something other than your webcam
Navigate to camera.py, edit it and replace 
>self.video = cv2.VideoCapture(0)
with
>self.video = cv2.VideoCapture("/path/to/your/video/kanyewestsleeping.mp4")
