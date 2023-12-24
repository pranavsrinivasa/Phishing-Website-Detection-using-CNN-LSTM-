# Phishing Website Detection using CNN - LSTM

## Overview

This repository contains the code and resources for a deep learning-based approach to detect phishing websites. The project focuses on comparing the performance of 1D CNN and CNN-LSTM models on two subdatasets: one with prior feature extraction and another without feature extraction.

## Dataset

The dataset used for this project is divided into two subdatasets:

1. **With Prior Feature Extraction:** This subdataset includes features extracted from phishing websites.
2. **No Feature Extraction:** This subdataset contains raw data without any prior feature extraction.

Each of these datasets has been used for training and evaluating both the 1D CNN and CNN-LSTM models. 
The 2nd dataset was created to allow the neural network to identify the features in the url rather than just pattern recognition.

## Models

The following deep learning models are implemented and compared:

1. **1D CNN:** A one-dimensional convolutional neural network is trained on both subdatasets to evaluate its performance.
2. **CNN - LSTM:** A combination of Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) is implemented and trained on both subdatasets.

# Results : 
- Each of the sub-datasets are paired with the 2 models and the results are compared to find the best pairing. 
- You can further analyze and visualize the comparison results in the Jupyter notebooks available in the https://github.com/pranavsrinivasa/Phishing-Website-Detection-using-CNN-LSTM-/commit/da7c840267bd4f998e97887867eab7682b38ea74 directory.

# Dataset :
https://www.kaggle.com/datasets/shashwatwork/web-page-phishing-detection-dataset
