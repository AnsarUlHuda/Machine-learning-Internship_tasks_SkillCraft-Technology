# 🤖 Machine Learning Internship Tasks — SkillCraft Technology

> A collection of end-to-end Machine Learning projects built with Python and Jupyter Notebook, covering regression, clustering, computer vision, and deep learning.

---

## 📁 Projects Overview

| # | Project | Algorithm | Domain |
|---|---------|-----------|--------|
| 1 | [House Price Prediction](#1-house-price-prediction-using-linear-regression) | Linear Regression | Regression |
| 2 | [Mall Customer Segmentation](#2-mall-customer-segmentation-using-k-means-clustering) | K-Means Clustering | Unsupervised Learning |
| 3 | [Dogs vs Cats Classification](#3-dogs-vs-cats-image-classification-using-svm) | Support Vector Machine | Computer Vision |
| 4 | [Hand Gesture Recognition](#4-hand-gesture-recognition-system) | Deep Learning (CNN) | Computer Vision |

---

## 1. House Price Prediction using Linear Regression

### 📌 Project Description
This project predicts house prices using supervised machine learning, specifically **Linear Regression**, based on key structural features of a property.

### 🔢 Features Used
- `OverallQual` — Overall material and finish quality
- `GrLivArea` — Above-grade (ground) living area in square feet
- `GarageCars` — Size of garage in car capacity
- `TotalBsmtSF` — Total square feet of basement area
- `FullBath` — Number of full bathrooms above grade

### 🔄 Workflow
1. Data loading
2. Feature selection
3. Train-test split
4. Model training
5. Prediction
6. Evaluation

### 📊 Output
- Mean Squared Error (MSE) score
- R² score
- Regression plots and visualizations

---

## 2. Mall Customer Segmentation using K-Means Clustering

### 📌 Overview
This project uses **K-Means Clustering** to segment mall customers based on their annual income and spending score, helping businesses better understand customer behavior and design targeted marketing strategies.

### 🛠️ Technologies Used
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

### 📂 Dataset
**Mall Customers Dataset** containing:
- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

### ✨ Features
- Data preprocessing
- Elbow Method to find optimal clusters
- Customer segmentation
- Data visualization
- Cluster plotting

### 📊 Output
Customers are divided into distinct clusters based on spending behavior, enabling data-driven business decisions.

---

## 3. Dogs vs Cats Image Classification using SVM

### 📌 Project Overview
This project implements a **Support Vector Machine (SVM)** model to classify images of cats and dogs using the Kaggle Dogs vs Cats dataset. The model processes raw image data, extracts numerical features, and performs binary classification.

### 🎯 Objective
Build an image classification system using ML techniques (SVM) to distinguish between cat and dog images.

### 🛠️ Technologies Used
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

### 📂 Dataset
**[Dogs vs Cats Dataset](https://www.kaggle.com/c/dogs-vs-cats)** from Kaggle, containing:
- Images of cats
- Images of dogs
- Binary classification labels

### 🔄 Project Workflow
1. Load image dataset
2. Resize images to uniform dimensions
3. Convert images into numerical arrays
4. Preprocess and normalize data
5. Split dataset into training and testing sets
6. Train SVM classifier
7. Evaluate model accuracy
8. Predict image classes

### 🧠 Machine Learning Model
**Support Vector Machine (SVM)** — a supervised algorithm that finds the optimal hyperplane separating classes.

| Label | Class |
|-------|-------|
| `0`   | Cat   |
| `1`   | Dog   |

### ✨ Features
- Image preprocessing using OpenCV
- Binary image classification
- Model training and testing
- Accuracy evaluation
- Prediction on new images

---

## 4. Hand Gesture Recognition System

### 📌 Project Overview
A **Machine Learning / Deep Learning** project that identifies and classifies hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems.

### 🎯 Applications
- 🖥️ Human-Computer Interaction (HCI)
- 🕹️ Virtual Control Systems
- 📱 Smart Devices
- 🎮 Gaming Applications
- 🤟 Sign Language Recognition
- ✋ Touchless Interfaces

### 🛠️ Technologies Used
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

### 📂 Dataset
The dataset contains labeled hand gesture images used for training and testing the model across multiple gesture classes.

### ✨ Features
- Real-time hand gesture detection
- Image and video-based gesture recognition
- Deep Learning-based classification
- High-accuracy gesture prediction
- User-friendly implementation

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install numpy pandas matplotlib seaborn scikit-learn opencv-python tensorflow keras jupyter
```

### Clone the Repository
```bash
git clone https://github.com/your-username/Machine-Learning-Internship-Tasks-SkillCraft-Technology.git
cd Machine-Learning-Internship-Tasks-SkillCraft-Technology
```

### Run a Project
```bash
jupyter notebook
```
Navigate to the desired project folder and open the `.ipynb` file.

---

## 🏢 About

These projects were developed as part of a **Machine Learning Internship** at **SkillCraft Technology**. Each project demonstrates a complete ML workflow from data preprocessing to model evaluation.

---

## 📄 License

This repository is for educational and internship purposes.
