# Project-of-Deep-Learning

## Flower Classification Project

This repository focuses on creating an optimal Convolutional Neural Network (CNN) model to accurately classify flowers into five distinct categories. The dataset comprises 3,670 RGB images of size 224×224×3, evenly distributed across the following classes:

- Roses: 641 images
- Dandelions: 898 images
- Daisies: 633 images
- Sunflowers: 699 images
- Tulips: 799 images
The dataset weighs approximately 218 MB and features a balanced class distribution, making accuracy a suitable evaluation metric.

## Project Objective

The goal is to design and train the most effective CNN model for flower classification. 

This repository includes:

- Custom-built CNN architectures: Models created from scratch to explore innovative solutions.
Pre-trained models: Architectures like MobileNet, VGG, and ResNet using transfer learning to adapt features learned from large datasets to this specific task.
- Transfer learning allows the model to leverage pre-trained knowledge, enhancing its ability to generalize to flower classification with fewer training samples.

## Key Features

- Performance Metrics: The models are evaluated using accuracy and loss on the training, validation, and test datasets.
- Early Stopping: The Keras EarlyStopping callback is employed to prevent overfitting by halting training when performance ceases to improve.
  
## Notable Models

The file FinalModels.ipynb contains the most performant models in terms of both loss and accuracy.

### This project was created in collaboration with Eleonora Brambatti and Francesco Angiulli, fellow students at the University of Milano-Bicocca.

