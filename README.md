# CNN-Based-Object-Recognition-System
Product image classification, visual search, and automated catalog tagging

## Project Summary: Object Recognition using CNN and ResNet50
Objective

To develop an accurate object recognition system capable of classifying images into predefined categories using deep learning, and to evaluate the effectiveness of traditional neural networks versus advanced convolutional architectures.

## Methodology

The project employs deep learning–based image classification using:

A baseline Artificial Neural Network (ANN) for comparison

An advanced Convolutional Neural Network (CNN) with ResNet50 as a pretrained backbone
Transfer learning is applied to leverage learned visual features from large-scale datasets, improving accuracy and training efficiency.

## Workflow

Dataset Acquisition: CIFAR-10 dataset downloaded using Kaggle API

Data Preprocessing: Image resizing, normalization, and label encoding

Data Splitting: Training and testing datasets created

Model Development:

Baseline ANN model

ResNet50-based CNN with custom classification layers

Model Training: Optimized using RMSprop optimizer and cross-entropy loss

Evaluation: Performance assessed using validation and test accuracy

Visualization: Training/validation loss and accuracy curves plotted

## Results

Baseline ANN achieved limited performance due to lack of spatial feature learning

ResNet50-based CNN achieved:

~94% validation accuracy

~93.8% test accuracy

Demonstrated strong generalization and minimal overfitting

## Applications

Computer Vision Systems: General object recognition tasks

Autonomous Vehicles: Object and obstacle classification

E-Commerce & Online Marketing: Product image categorization and visual search

## Conclusion
Deployed a ResNet50-based computer vision model on CIFAR-10 (50K images) achieving ~94% accuracy for multi-class image classification.

Engineered a production-ready ML pipeline using TensorFlow/Keras with data preprocessing and train–test validation.

Enhanced model robustness using transfer learning, batch normalization, and dropout (0.5).

Healthcare: Medical image classification

Surveillance & Security: Object identification in video streams
