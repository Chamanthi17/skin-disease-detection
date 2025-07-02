## 🩺 Skin Disease Detection Using Machine Learning

This project helps detect 7 types of skin diseases using Convolutional Neural Networks (CNN) and an ensemble of powerful pre-trained models like VGG16, InceptionV3, and DenseNet.

## 🌟 Overview

Many people suffer from various skin diseases. Traditional diagnosis is often time-consuming and requires expert knowledge. This project uses deep learning to automatically analyze skin images and help with early disease detection.

## 🔍 Features

Detects 7 skin disease types:

  - Actinic Keratoses
  
  - Basal Cell Carcinoma
  
  - Benign Keratosis
  
  - Dermatofibroma
  
  - Melanoma
  
  - Melanocytic Nevi
  
  - Vascular Lesions

-Custom CNN model from scratch

-Ensemble of VGG16, InceptionV3 & DenseNet models for better accuracy

## 📚 Dataset

Uses the HAM10000 dataset from Harvard Dataverse

Contains 10,015 labeled dermatoscopic skin images.

## 🛠️ Requirements

🐍 Language: Python

📝 IDE: Jupyter Notebook

📦 Libraries: pandas, numpy, matplotlib, seaborn, sklearn, tensorflow, keras, PIL, tkinter

## 🧰 Methodology

  📥 Data Collection from HAM10000

  🧹 Data Cleaning & Augmentation

  ✂️ Split dataset into training, validation & test sets

  🏗️ Build CNN architecture with convolution, pooling, normalization & dropout layers

  🚂 Train CNN and pre-trained models (VGG16, DenseNet, InceptionV3)

  🤝 Combine pre-trained models with ensemble weighted average

  📊 Evaluate models using accuracy, precision, recall & F1-score

## ⚙️ Usage

Run the Jupyter notebooks for data preprocessing, model training, and evaluation.
