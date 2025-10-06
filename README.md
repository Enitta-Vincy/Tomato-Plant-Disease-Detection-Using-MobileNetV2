# Tomato-Plant-Disease-Detection-Using-MobileNetV2
This project focuses on detecting and classifying diseases in tomato plants using deep learning. By leveraging a pre-trained MobileNetV2 model, it can identify 9 disease categories along with healthy tomato leaves, helping farmers and gardeners take timely action to prevent crop loss.

Dataset
Source: Kaggle
Number of Classes: 8 disease classes + 1 healthy class
Description: The dataset consists of tomato leaf images representing various diseases and healthy leaves.

Model Architecture
Base Model: MobileNetV2 (pre-trained)

Modifications:
Removed the original classification layers
Added Global Average Pooling
Added Dense layers
Final layer uses Softmax activation for multi-class classification

Features
Real-time detection of tomato leaf diseases
Classifies multiple disease types and healthy leaves
Easy to integrate with applications for farmers or plant monitoring systems
