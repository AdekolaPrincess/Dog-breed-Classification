# Dog Breed Classification using ResNet50

This project uses transfer learning with the ResNet50 architecture to classify dog breeds from images. It is designed to identify the breed of a dog given an image, making use of deep learning techniques to achieve high accuracy.

## Overview

The notebook walks through the entire pipeline of building an image classification model:
- Loading and exploring the dataset
- Preprocessing and augmenting image data
- Applying transfer learning using a pretrained ResNet50 model
- Fine-tuning the model for better performance
- Evaluating the model's accuracy and visualizing predictions

## Key Components

- **Transfer Learning:** Leverages a ResNet50 model pretrained on ImageNet for feature extraction.
- **Image Augmentation:** Improves model generalization with techniques like rotation and flipping.
- **Model Evaluation:** Accuracy and loss are tracked and visualized for both training and validation sets.
- **Prediction:** The model is tested on new images to identify dog breeds.

## Objective

To develop a model that can reliably predict the breed of a dog from an image by using a convolutional neural network enhanced with transfer learning techniques.
