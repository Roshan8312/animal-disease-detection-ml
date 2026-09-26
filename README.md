# Animal Disease Detection Using Machine Learning

An image-based livestock disease classification system developed using deep learning and transfer learning. The project uses an EfficientNetB0 model to classify livestock images into different disease categories and provides an interactive Gradio interface for image-based prediction.

## 📌 Project Overview

Livestock diseases can significantly affect animal health and productivity. Early identification of diseases through image analysis can assist in timely intervention.

This project develops a deep learning-based image classification system that analyzes livestock images and predicts the corresponding disease category. EfficientNetB0 is used as the backbone model through transfer learning to achieve effective image classification with relatively fewer parameters.

## 🎯 Objectives

- Develop an automated livestock disease classification system.
- Apply image preprocessing and augmentation to improve model performance.
- Use EfficientNetB0 transfer learning for multi-class image classification.
- Evaluate the model using standard classification metrics.
- Develop an interactive interface for image-based disease prediction.

## 🧠 Model

The project uses **EfficientNetB0** with transfer learning.

EfficientNetB0 was selected because of its efficient architecture and ability to provide good classification performance with a relatively lightweight model.

### Model Workflow

```text
Input Image
     ↓
Image Preprocessing
     ↓
Image Resizing & Normalization
     ↓
Data Augmentation
     ↓
EfficientNetB0
     ↓
Feature Extraction
     ↓
Classification Layer
     ↓
Predicted Disease
