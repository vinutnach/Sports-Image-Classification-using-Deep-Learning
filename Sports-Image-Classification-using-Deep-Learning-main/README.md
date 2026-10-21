# Sports Image Classification using Deep Learning

This project implements a **Deep learning model to classify images into 100 sports categories** using **transfer learning with EfficientNetB0**. The model is trained on the Kaggle Sports Classification dataset and can accurately predict the sport shown in any image.

## Project Overview
- **Objective:** Build an AI model that automatically identifies the sport depicted in an image and visualizes the prediction.
- **Dataset:** Kaggle Sports Classification Dataset with separate **train, validation, and test directories**.
- **Approach:** 
  - Feature extraction using **EfficientNetB0** from TensorFlow Hub.
  - Fully connected **softmax layer** for 100-class classification.
  - Image preprocessing with **ImageDataGenerator** for normalization and augmentation.
  - Model training over 20 epochs and evaluation on a separate test set.

## Key Features
- **Transfer Learning:** EfficientNetB0 for robust image feature representation.
- **Data Preprocessing:** Rescaling and resizing images for model compatibility.
- **Prediction & Visualization:** Functions to load new images, make predictions, and plot results with predicted class names.
- **High Accuracy:** Achieves ~97% classification accuracy on the test dataset.

## Technologies & Libraries
- **Programming Language:** Python
- **Libraries:** TensorFlow, TensorFlow Hub, OpenCV, NumPy, Pandas, Matplotlib
- **Deep Learning:** Convolutional Neural Networks (CNN) via EfficientNetB0

## Results
Accurately classifies images into 100 sports categories.
Provides a real-time prediction and visualization pipeline using the pred_and_plot() function.

## DataSet Link 
-> Kaggle Sports Classification Dataset: https://www.kaggle.com/datasets/gpiosenka/sports-classification
