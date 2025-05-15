# Bone Fracture Detection Using CNN with K-Fold Validation

This project presents a deep learning-based solution for detecting bone fractures in X-ray images using a custom Convolutional Neural Network (CNN) architecture. The solution was developed as part of the *Artificial Intelligence and Machine Learning* course at Princess Sumaya University for Technology and culminated in the publication of a scientific paper.

## Project Summary

Bone fractures are among the most common injuries treated in medical settings. Early and accurate detection is critical for timely intervention. This project builds a reliable, automated fracture detection system that classifies X-ray images as either *fractured* or *unfractured*. The model was trained on a merged dataset composed of over 9,500 labeled X-ray images sourced from two publicly available repositories, ensuring a diverse and representative sample.

## Key Features

- **Custom CNN Architecture**  
  Designed and fine-tuned specifically for binary classification of bone fractures.

- **Data Engineering & Cleaning**  
  Combined two separate datasets, removed duplicate images, balanced class distribution, and normalized image intensity.

- **Data Augmentation**  
  Implemented image transformations (rotation, shift, zoom, flipping) to improve generalization.

- **K-Fold Cross-Validation**  
  Used 5-fold cross-validation to evaluate model robustness and mitigate overfitting.

- **Evaluation Metrics**  
  Achieved up to **99.17% accuracy** and **0.99 F1-score** on validation data, and **99.06% accuracy** on the test set. Evaluated using precision, recall, and confusion matrix.

## Tech Stack

- **Languages & Libraries:** Python, TensorFlow, Keras, NumPy, Pandas, Scikit-learn, Matplotlib  
- **Techniques:** CNN, K-Fold Cross-Validation, Data Augmentation, Transfer Learning (explored), Image Preprocessing

## Dataset Sources

- [Bone Fracture Multi-Region X-ray Data – by M. Rodrigo (Kaggle)](https://www.kaggle.com/datasets/bmadushanirodrigo/fracture-multi-region-x-ray-data)
- [Bone Fracture Detection Using X-rays (Kaggle)](https://www.kaggle.com/datasets/vuppalaadithyasairam/bone-fracture-detection-using-xrays)

## Paper

You can read the full paper here:  
**[Bone Fracture Detection Using Convolutional Neural Network (CNN) K-Fold Validation Method](./Bone%20Fracture%20Detection%20Using%20Convulutional%20Neural%20Network%20(CNN)%20K-Fold%20Validation%20Method.pdf)**
