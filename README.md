# Handwritten-Digits-Image-Processing
Computer Vision and Machine Learning project using MNIST to recognize handwritten digits (0–9). Compares Logistic Regression, SVM, KNN, MLP, and CNN models, covering data analysis, preprocessing, evaluation, and performance comparison. CNN achieved 99.32% test accuracy.
# Handwritten Digits Recognition using Machine Learning and Deep Learning

## Project Overview

This project focuses on recognizing handwritten digits from 0 to 9 using the MNIST dataset. It explores computer vision and classification techniques by training and comparing five machine learning and deep learning models to identify the most effective classifier.

## Objectives
- Perform exploratory data analysis on the MNIST dataset.
- Preprocess and normalize handwritten digit images.
- Build classification models using machine learning and deep learning.
- Compare model accuracy, training time, and prediction time.
- Recommend the most suitable model for production use.

## Models Implemented
- Logistic Regression
- Support Vector Machine (SVM) with RBF kernel
- K-Nearest Neighbors (KNN)
- Multi-Layer Perceptron (MLP)
- Convolutional Neural Network (CNN)

## Dataset
The project uses the MNIST dataset, containing 70,000 grayscale handwritten digit images:
- 60,000 training images
- 10,000 test images
- Image dimensions: 28 × 28 pixels
- Classes: digits 0–9

## Results
The Convolutional Neural Network achieved **99.32% test accuracy**, outperforming the other evaluated models.

The project also compares training and inference times to understand the trade-offs between predictive performance and computational cost.

## Technologies Used
Python, Jupyter Notebook, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, TensorFlow, and Keras.

## Key Learnings
- Exploratory data analysis and image preprocessing
- Machine learning classification techniques
- Neural networks and convolutional neural networks
- Model evaluation and performance comparison
- Identifying trade-offs between accuracy and computational efficiency

## Conclusion
This project demonstrates how classical machine learning algorithms and deep learning architectures can be applied to handwritten digit recognition. Based on the experimental results, CNN is the recommended model when classification accuracy is the primary objective.
