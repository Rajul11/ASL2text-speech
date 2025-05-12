# ASL2text-speech
## Overview  
This project focuses on the recognition of American Sign Language (ASL) gestures using Convolutional Neural Networks (CNN). The system is designed to identify static hand gestures corresponding to ASL letters or signs. The project consists of two main components: the deep learning-based gesture recognition model and the potential integration with real-time video or image processing systems.  
## Features 
Hand Detection: Uses MediaPipe for precise hand landmark detection.

Data Augmentation: Employs flipped hand landmarks to expand dataset diversity.

Custom Dataset: Loads and processes a directory-structured ASL image dataset.

Neural Network Model: Trained on normalized hand landmarks using a Dense Neural Network.

Real-Time Prediction: Predicts gestures live via webcam.

Smoothing & Autocorrection: Reduces noise in predictions and corrects spelling errors.

Visualization Tools: Confusion matrix, accuracy metrics, and bounding boxes during detection.

## Technologies Used
1.TensorFlow / Keras: Model training and evaluation

2.MediaPipe: Real-time hand landmark detection

3.OpenCV: Webcam interaction and image preprocessing

4.Matplotlib / Seaborn: Visualization

5.Scikit-learn: Evaluation metrics and data splitting

6.TextBlob: Spelling autocorrection

7.Pandas: Data manipulation


# How to Run
1.Clone the repository

2.Install dependencies

3.Train the model

4.Run the webcam app
