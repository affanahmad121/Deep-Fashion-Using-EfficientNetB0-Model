# Deep-Fashion-Using-EfficientNetB0-Model
Deep Fashion multi-output classification (Gender + Product Type) using EfficientNetB0 and text feature integration.

# Deep Fashion Multi-Label Classification using EfficientNetB0

![Python](https://img.shields.io/badge/Python-3.9-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Keras](https://img.shields.io/badge/Keras-DeepLearning-red)
![GPU](https://img.shields.io/badge/GPU-Accelerated-green)
![Multi-Output](https://img.shields.io/badge/Model-MultiOutput-purple)

---

##  Project Overview

This project implements a **multi-label, multi-output deep learning model** for fashion image classification using **EfficientNetB0**.

The model simultaneously predicts:

-  **Gender** (Binary Classification)
-  **Product Type** (Multi-class Classification)

It also integrates **Text Vectorization** features along with image inputs to improve prediction performance.

---

##  Model Architecture

- Base Model: **EfficientNetB0 (Transfer Learning)**
- Multi-output architecture:
  - Output 1 → Gender (Binary Classification)
  - Output 2 → Product Type (Multi-class with AUC metric)
- Feature Inputs:
  - `image`
  - `gender`
  - `product_type`
  - `image_type`
- Text preprocessing using **TextVectorization layer**

---

##  Key Features

-  Transfer Learning with EfficientNetB0
-  Multi-Label / Multi-Output Learning
-  Image + Text feature integration
-  AUC metric monitoring for product classification
-  Separate loss tracking per output
-  Validation performance monitoring

---

##  Model Performance

###  Training Results

- **Gender Binary Accuracy:** `0.9958`
- **Gender Loss:** `0.0163`
- **Product AUC:** `0.9599`
- **Product Loss:** `0.3875`
- **Total Loss:** `0.4038`

###  Validation Results

- **Validation Gender Binary Accuracy:** `0.9978`
- **Validation Gender Loss:** `0.0103`
- **Validation Product AUC:** `0.9688`
- **Validation Product Loss:** `0.4706`
- **Validation Total Loss:** `0.4817`

 The model demonstrates **excellent generalization**, especially for gender prediction, with strong AUC performance for product classification.

---

##  Tech Stack

- Python
- TensorFlow / Keras
- EfficientNetB0
- NumPy
- Pandas
- Matplotlib
- TextVectorization Layer

---

##  Problem Type

- Multi-label Classification
- Multi-output Deep Learning
- Image + Text Feature Fusion
- Transfer Learning

---

##  Dataset Features Used

- `gender`
- `product_type`
- `image_type`
- image data

---


## 💻 How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3.Open and run the Jupyter Notebook
-Future Improvements
-Hyperparameter tuning
-Model ensembling
-Deployment using Streamlit / FastAPI
-Add Grad-CAM visualization for explainability
-Convert to production-ready pipeline


#Why This Project Matters

->Fashion classification systems are widely used in:
->E-commerce platforms
->Recommendation engines
->Smart retail systems
->Automated tagging systems

#This project demonstrates:

->Strong understanding of transfer learning
->Multi-output deep learning architecture
->Advanced evaluation metrics (AUC + binary accuracy)
->Real-world ML system design

#Author

Affan Ahmad
Deep Learning & Computer Vision Enthusiast
---
 
