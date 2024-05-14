# A deep Learning Approach to Real-Time Emotion Detection System

This repository contains the source code for a real-time emotion detection system that utilizes facial recognition. The system leverages pre-trained models to identify faces in a video stream and predict the emotions of the individuals detected.

Key Features:

Real-time processing: Analyzes emotions in a video stream without significant delays.
Facial recognition: Identifies faces within the video frame using a pre-trained Caffe model (RFB-320).
Emotion recognition: Predicts emotions (neutral, happiness, surprise, sadness, anger, disgust, fear) based on facial expressions using a pre-trained ONNX model.
Pre-processing: Applies necessary transformations (resizing, color conversion) to facial images before feeding them to the emotion recognition model.
Dependencies:

OpenCV
NumPy
dnn (deep learning module from OpenCV)
onnxruntime (optional, for running ONNX models)
Instructions:

Install the required dependencies (refer to documentation for each library).
Download the pre-trained models (Caffe model and ONNX model) and place them in the appropriate directory within the project structure.
Run the script FER_live_cam.py. This script will access the webcam by default, but you can modify it to use a video file as input.
Further Exploration:

Experiment with different pre-trained emotion recognition models.
Explore techniques to improve accuracy, such as data augmentation or utilizing more advanced deep learning models.
Integrate the emotion detection system into a larger application.
Note:

This project utilizes pre-trained models whose accuracy can vary depending on factors like lighting, pose, and facial expressions.
The provided code serves as a foundational example and can be further customized and extended.
