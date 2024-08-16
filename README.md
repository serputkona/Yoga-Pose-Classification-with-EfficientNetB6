# Yoga Pose Classification with EfficientNetB6

This repository contains a deep learning project focused on classifying yoga poses from images. The project uses an EfficientNetB6-based model, enhanced with custom convolutional layers, to achieve high classification accuracy. The dataset includes images of yoga poses, with corresponding labels for training and validation.

## Dataset

- `train.csv`: Contains the `image_id` and `class_6` columns, where `class_6` represents the class of the yoga pose.
- Images: Located in the `images` folder, used for training and testing.

## Code Overview

- **Data Augmentation:** `ImageDataGenerator` is used to augment the dataset with transformations like rotation, shifting, and flipping.
- **Model Architecture:** 
  - Base Model: EfficientNetB6 with weights pre-trained on ImageNet.
  - Custom Layers: Additional convolutional layers, batch normalization, max pooling, dropout, and dense layers.
- **Training:** Utilizes Adam optimizer with learning rate scheduling and early stopping to optimize model performance.

