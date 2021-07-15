# Real-time-Face-Detection-by-OpenCV
This project is done using Pycharm IDE and Python, it is a Real-Time Face recognition using OpenCV while performing object detection using Haar feature-based cascade classifiers for detecting face, eyes, and smile.
# 1. Import and initialize
Start by importing OpenCV and create a directory (ex: Cascades) to gather all Haar classifiers files that you want to use in you project, then use their path to load them into your project.
import cv2 
 
faceCascade = cv2.CascadeClassifier('Cascades/haarcascades/HAARCASCADE_FRONTALFACE_DEFAULT.xml')
