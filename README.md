# Speech Emotion Recognition (SER) Project


## Overview
This project focuses on using machine learning to detect emotions from speech. Leveraging deep learning techniques like LSTM (Long Short-Term Memory) networks and features extracted from audio using MFCC (Mel-frequency cepstral coefficients), the model can classify emotions such as anger, happiness, sadness, fear, and others. The project is built using the TESS Toronto Emotional Speech Set.


## Key Features
**Data Preprocessing:** Audio data is processed using Librosa to extract key features like MFCC, which capture the unique characteristics of emotions in speech.

**Model Architecture:** A sequential LSTM model is designed to classify 7 emotions based on audio input. The LSTM helps in understanding the temporal relationships in the audio sequences.

**Model Evaluation:** The model's performance is evaluated using accuracy metrics, confusion matrices, and classification reports to understand how well it distinguishes between different emotions.

## Dataset
The project uses the TESS Toronto Emotional Speech Set, consisting of 2800 audio samples labeled with 7 emotions:

Angry

Disgust

Fear

Happy

Neutral

Pleasant Surprise

Sad


## Tools & Libraries
Librosa for audio analysis and feature extraction.

Keras for building and training the LSTM model.

Pandas and NumPy for data manipulation.

Matplotlib and Seaborn for data visualization.

Scikit-learn for data preprocessing and evaluation.


## Installation
To run the project, clone the repository and ensure you have the required dependencies installed, including Pandas, NumPy, Librosa, Keras, and TensorFlow.


## Project Workflow
**Data Loading & Visualization:** Audio files are loaded, and visualizations like waveplots and spectrograms are created to understand the patterns of each emotion.

**Feature Extraction:** MFCCs are extracted from the audio files to represent the speech data in a format suitable for the model.

**Model Training:** The LSTM model is trained to classify emotions with dropout layers added to reduce overfitting.

**Evaluation:** The model's performance is measured using confusion matrices and classification reports to analyze the accuracy and effectiveness of the classification.


## Results
The model achieves good accuracy in classifying different emotions from speech.

Visualization of the confusion matrix and classification report shows how well the model distinguishes between emotions.
