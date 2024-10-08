# [Deepfake Detection System] (https://murali127.github.io/sih_hackathon/)

## Overview

This project aims to detect deepfake videos by analyzing video sequences to identify fake or real content. Our system leverages advanced AI/ML techniques to ensure accuracy and efficiency in detecting manipulated media.

## Key Features

- **Video Frame Analysis**: Videos are split into frames for more granular examination.
- **Face Detection & Cropping**: Facial regions are isolated for more focused analysis.
- **LSTM Video Classification**: Uses Long Short-Term Memory (LSTM) networks to classify sequences of video frames.
- **ResNext Feature Extraction**: Applies ResNext, a Convolutional Neural Network (CNN) architecture, to extract key features from frames.
- **Prediction Flow**: Once trained, the model can predict whether new videos are real or fake.

## System Architecture

1. **Data Input**: The system begins with a dataset of real and fake videos.
2. **Preprocessing**: Videos are split into frames, faces are detected and cropped, forming the final dataset.
3. **Data Splitting**: The dataset is split into training and testing subsets.
4. **Model Training & Testing**: The LSTM and ResNext-based model is trained on the dataset and evaluated.
5. **Prediction Flow**: New videos are analyzed using the trained model to predict if they are real or deepfake.

## Model Evaluation

- **Confusion Matrix**: Used to evaluate model performance by showing correct and incorrect predictions for real and fake classes.
- **Exported Model**: The trained model is saved for future use in predicting new videos.

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/deepfake-detection.git
   cd deepfake-detection
