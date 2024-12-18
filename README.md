# Iceberg-Detection-in-Satellite-Images-Using-Convolutional Neural Networks (CNN)

This project leverages Convolutional Neural Networks (CNN) to detect icebergs in satellite images, an important task for environmental monitoring and safety navigation. The model classifies satellite images into two categories: iceberg and non-iceberg.

# Project Overview

The goal of this project is to develop a deep learning model capable of accurately identifying icebergs from satellite imagery. Icebergs are often challenging to detect in remote areas, and having an automated system can significantly enhance navigation safety, especially in polar regions.

# Technologies Used

Python

Tensorflow / Keras (for building and training the CNN model)

OpenCV (for image processing)

Numpy (for data manipulation)

Flask (for deploying the model as a web application)

HTML, CSS, Javascript (for frontend)

# Dataset

The project uses the Iceberg Detection dataset available on Kaggle. The dataset contains satellite images labeled as icebergs or ships, and it is used to train the CNN model.

# Approach

# 1. Data Preprocessing:

Resizing the images to a consistent size (e.g., 128x128).

Normalizing pixel values.

Applying data augmentation (rotation, flipping, etc.) to improve model generalization.

# 2. Model Architecture:

Built a CNN model using multiple convolutional and pooling layers for feature extraction.

A fully connected layer at the end for classification (iceberg or non-iceberg).

Sigmoid activation function used for binary classification.

# 3. Training:

Trained the model on the processed dataset with a validation set to avoid overfitting.

Optimized using the Adam optimizer and cross-entropy loss.

# 4. Evaluation:

Evaluated the model performance using accuracy, precision, recall, and F1-score.

Visualized the confusion matrix to identify misclassifications.

# 5. Deployment:

Deployed the model as a web application using Flask, where users can upload new satellite images for iceberg detection.

# Features

Model Training: Trains the CNN model to detect icebergs in satellite images.

Prediction: Makes real-time predictions on uploaded satellite images.

Web Interface: Simple Flask-based web application for user interaction.

