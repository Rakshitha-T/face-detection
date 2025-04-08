
# face-detection

A Python-based Face and Emotion Detection system using deep learning and computer vision techniques.  
This project uses OpenCV for real-time video processing, deep learning models for face detection, and a Convolutional Neural Network (CNN) to classify facial expressions into multiple emotions.

# Features

 Real-time face detection using Haar Cascades 
 Emotion recognition from facial expression
 Live video streaming from webcam
 Modular, clean, and extensible code
 Save processed video with bounding boxes and emotion labels 

# Tech Stack

 Python 3.x
 OpenCV
 TensorFlow / Keras
 NumPy
 Matplotlib (optional, for visualization)
 Pre-trained emotion detection model

# Getting Started

 1. Clone the repository

 2. Install dependencies

It is recommended to use a virtual environment.

pip install -r requirements.txt

 3. Download the pre-trained model

Place your pre-trained emotion recognition model in the `models/` directory.

4. Run the application

For webcam input:

python main.py --mode webcam

# Model Details

 The emotion detection model is a CNN trained on the FER-2013 dataset.
 Emotion categories include:
   😄 Happy
   😢 Sad
   😡 Angry
   😲 Surprise
   😐 Neutral
   😨 Fear
   😖 Disgust





