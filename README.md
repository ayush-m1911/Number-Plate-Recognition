🚗 Automatic License Plate Recognition (ALPR)

This project implements an Automatic License Plate Recognition (ALPR) system using OpenCV, machine learning classifiers, and image processing techniques.
The system detects license plates from images, segments individual characters, and recognizes them using trained character and digit classifiers.

📌 Features

License plate localization

Character segmentation & scissoring

ML-based character recognition

Separate classifiers for letters and digits

Works on multiple images in a folder

Displays detected plate and recognized text on the image

🧠 Project Pipeline

The ALPR system follows a structured pipeline:

Localization
Detects the license plate region from the image.

Segmenting Characters
Extracts individual characters from the detected license plate.

Scissoring Characters
Refines character boundaries for better recognition.

First Try
Initial recognition using basic classifiers.

Gathering Character Examples
Collects character samples for training improved models.

Improving Classifier
Uses enhanced feature extraction and trained ML models for higher accuracy.

🛠️ Tech Stack

Python

OpenCV

NumPy

imutils

scikit-learn

cPickle

Custom image descriptors & detectors
