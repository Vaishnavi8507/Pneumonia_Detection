# 🩺 Pneumonia Detection Using CNN

## 📚 Overview
This project involves developing a deep learning model to detect pneumonia from chest X-ray images using a Convolutional Neural Network (CNN). The goal is to accurately classify X-ray images as either normal or pneumonia-infected. The project uses a dataset of labeled X-ray images to train and validate the model.

## 🛠️ Tech Stack
- **Programming Language**: ![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python&logoColor=white)
- **Deep Learning Framework**: ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-2.x-red?logo=keras&logoColor=white)
- **Architecture**: Convolutional Neural Network (CNN)
- **Pre-trained Model**: VGG-16
- **Dataset**: [Kaggle X-ray Image Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

## 📄 Project Description
The project implements a CNN model using TensorFlow and Keras, featuring the following components:
- **Convolutional Layers**: Used to extract features from the input X-ray images.
- **Pooling Layers**: Applied to down-sample the feature maps, reducing computation and helping in feature selection.
- **Fully Connected Layers**: Integrated to perform the final classification.

### ✨ Key Features
- Developed a CNN model capable of identifying pneumonia from chest X-rays.
- Utilized a labeled dataset of X-ray images from Kaggle to train and validate the model.
- Implemented data preprocessing, augmentation, and normalization techniques to improve model accuracy.
- Integrated VGG-16 pre-trained architecture for feature extraction and transfer learning.

## 📊 Dataset
The dataset used for this project is available on Kaggle. It consists of chest X-ray images labeled as either "Normal" or "Pneumonia." The dataset was divided into training, validation, and test sets for accurate model evaluation.

- **Classes**: 
  - 🟢 Normal
  - 🔴 Pneumonia-Bacterial or Viral
    


