# 🐶🐱 Dog vs Cat Classification using Transfer Learning

A Deep Learning project that classifies images of dogs and cats using Transfer Learning with MobileNetV2.
This project leverages a pretrained CNN model to achieve high accuracy with reduced training time and computational cost.

## Project Overview

Image classification is a core computer vision task widely used in automation, healthcare, security, and recommendation systems.
In this project, a MobileNetV2 feature extractor from TensorFlow Hub is used to build an efficient binary image classifier.

The model learns to distinguish between dog and cat images using transfer learning and achieves strong performance even with limited data.

## Objectives

✅ Build a deep learning image classifier
✅ Apply transfer learning using MobileNetV2
✅ Perform image preprocessing and augmentation
✅ Train and evaluate a binary classification model
✅ Visualize predictions and performance

## Tech Stack

Python

TensorFlow / Keras

TensorFlow Hub

NumPy & Matplotlib

Kaggle API (Dataset download)

## Dataset

The dataset used is the popular Kaggle Dogs vs Cats dataset.

Thousands of labeled dog and cat images

Balanced binary classification dataset

Real-world image variations

## Dataset Source: Kaggle Dogs vs Cats

## Workflow

Dataset extraction using Kaggle API

Image preprocessing and resizing (224×224)

Train–validation split

Loading MobileNetV2 pretrained feature extractor

Adding custom classification layer

Model training and evaluation

Prediction visualization

## Model Architecture

MobileNetV2 (Pretrained Feature Extractor)

Non-trainable convolutional base

Dense output layer with 2 classes

Adam optimizer with sparse categorical crossentropy

This approach significantly reduces training time while maintaining high accuracy.

## Results

* Fast convergence due to transfer learning
* Strong classification accuracy
* Robust performance on unseen images

## Key Learnings

Practical understanding of transfer learning

Working with TensorFlow Hub pretrained models

Efficient image preprocessing pipeline

Binary classification with CNNs

## Future Improvements

Fine-tuning MobileNet layers

Deploying with Streamlit / Flask

Adding real-time webcam prediction

Converting model to TensorFlow Lite
