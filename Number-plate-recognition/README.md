# 🚗 Automatic License Plate Recognition (ALPR)

This repository contains an **Automatic License Plate Recognition (ALPR)** system built using **Python and OpenCV**.  
The system detects vehicle license plates from images, segments individual characters, and recognizes them using **machine learning–based classifiers**.

The project demonstrates a complete **computer vision pipeline**, from image preprocessing to character recognition.

---

## ✨ Key Features

- Automatic license plate detection from images  
- Character segmentation and refinement (scissoring)  
- Machine learning–based character recognition  
- Separate classifiers for **letters** and **digits**  
- Batch processing of images from a folder  
- Visual output showing detected plate and recognized text  

---

## 🧠 System Workflow

The ALPR system follows a structured, multi-stage pipeline:

1. **License Plate Localization**  
   Identifies and extracts the license plate region from the input image.

2. **Character Segmentation**  
   Separates individual characters from the detected license plate.

3. **Character Scissoring**  
   Refines character boundaries to improve recognition accuracy.

4. **Initial Recognition**  
   Performs a first-pass prediction using baseline classifiers.

5. **Character Sample Collection**  
   Gathers character examples for training improved models.

6. **Classifier Improvement**  
   Trains enhanced machine learning models using extracted features for better accuracy.

---

## 🛠️ Tech Stack

- **Python**
- **OpenCV**
- **NumPy**
- **imutils**
- **scikit-learn**
- **cPickle**
- Custom image descriptors and detection algorithms

---

## 📂 Project Structure (Example)

