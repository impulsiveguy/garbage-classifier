# TrashNet CNN – Waste Classification using Deep Learning

A Convolutional Neural Network (CNN) built and trained from scratch using TensorFlow/Keras to classify images of waste into six categories:  
cardboard, glass, metal, paper, plastic, and trash.

This project also includes a Streamlit web app for real-time waste classification.

---

## Project Overview

The goal is to automatically classify different types of recyclable waste from images using a CNN trained on the TrashNet dataset.  
The model is trained with advanced data augmentation and regularization for better generalization.

---

## Features

- End-to-end training from scratch (no pretrained backbone).
- Stratified data split ensuring balanced train/val/test sets.
- Advanced augmentations (rotation, zoom, shift, shear, flips).
- Class weighting to handle dataset imbalance.
- Callbacks: Early stopping, learning rate reduction, model checkpoint.
- Visualization: Training curves and confusion matrix.
- Streamlit UI for easy waste classification via image upload.

---

## Requirements

Make sure you have the following Python packages installed:

```bash
pip install tensorflow numpy matplotlib seaborn scikit-learn pillow streamlit requests
