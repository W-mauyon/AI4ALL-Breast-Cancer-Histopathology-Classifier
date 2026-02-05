# AI4ALL-Breast-Cancer-Histopathology-Classifier
Final project for AI4ALL Ignite Program - A simple ResNet-18 model for classifying breast tumor images.

# Background
This project uses deep learning to classify breast cancer histopathology images as benign or malignant. The model is built with ResNet-18, a lightweight CNN that is effective for medical image tasks. The data used were images from the BreaKHis 400X dataset, containing microscopic tumor tissue samples.

# Model & Methods

Model: ResNet-18 (fine-tuned from ImageNet)
Data: BreaKHis 400X (benign vs. malignant)
Image resizing, normalization, and light data augmentation
Training: binary classification using cross-entropy loss and the Adam optimizer

# Purpose
The goal is to show how deep learning can help analyze histopathology slides by:
- Showing AI-assisted technology
- Giving quick predictions
- Supporting consistency in classification

# Performance
The model reaches an accuracy of ~96.15% on the evaluation dataset.
