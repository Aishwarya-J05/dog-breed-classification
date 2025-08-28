# dog-breed-classification
# 🐶 Dog Breed Classification using TensorFlow & Transfer Learning

This project builds an **end-to-end multiclass image classifier** for the [Kaggle Dog Breed Identification Competition](https://www.kaggle.com/competitions/dog-breed-identification).  
It uses **TensorFlow 2.x, TensorFlow Hub, and Transfer Learning** to classify images into **120 different dog breeds**.

---

## 📌 Problem
Given an image of a dog, predict its **breed** out of 120 possible classes.

---

## 📂 Dataset
- Data Source: [Kaggle Dog Breed Identification](https://www.kaggle.com/competitions/dog-breed-identification/data)  
- ~10,000+ labeled training images  
- ~10,000+ unlabeled test images  
- 120 breeds (classes)

---

## ⚙️ Approach
1. Load and preprocess images into Tensors  
2. Build a **transfer learning model** using MobileNetV2 from TensorFlow Hub  
3. Train with callbacks (TensorBoard + Early Stopping)  
4. Evaluate and visualize predictions  
5. Save & reload trained models  
6. Generate submission files for Kaggle  

---

## ✨ Features
- End-to-end TensorFlow pipeline  
- Transfer Learning with MobileNetV2  
- Data batching, preprocessing, and augmentation  
- TensorBoard integration for monitoring  
- Model saving & reloading  
- Kaggle submission CSV generator  
- Custom image prediction support  

---

## 📊 Results
- Trained on full dataset (~10k+ images)  
- Achieved competitive accuracy with MobileNetV2  
- Generates Kaggle submission-ready CSV  

---

## 🚀 How to Run

### Clone the repo
```bash
git clone https://github.com/Aishwarya-J05/dog-breed-classifier.git
cd dog-breed-classifier
