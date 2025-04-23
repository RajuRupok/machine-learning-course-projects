# machine-learning-course-projects
This repository contains academic work completed for the Machine Learning course during my MSc in Computer Science at the University of New Brunswick. It includes five programming projects using various machine learning algorithms in Python (Also a report of these projects) and a final survey-based report titled 'Phishing Detection Using Machine Learning'.
---
## 📂 Project 1 – Adaboost with ID3 (Letter Recognition Dataset)

### 📘 Overview
This project implements the Adaboost algorithm using ID3 (custom decision tree) as the base learner. The model is trained and evaluated on the **Letter Recognition Dataset** from the UCI Machine Learning Repository.

### 🧠 Algorithms Used
- ID3 Decision Tree (custom implementation)
- Adaboost Ensemble Learning

### 📊 Dataset
- UCI Letter Recognition Dataset
- 16 integer features
- Target: Capital letters A–Z

### 📈 Results
- Improved accuracy with Adaboost compared to standalone ID3
- Performance analysis included in `AdaBoost_ID3_Letter_Recognition_Evaluated.ipynb`

### 📁 Files Included
- `AdaBoost_ID3_Letter_Recognition.ipynb` – Model training
- `AdaBoost_ID3_Letter_Recognition_Evaluated.ipynb` – Evaluation
- `letter-recognition.data`, `.names`, `.data.Z` – Dataset files

📂 **Project 2 – Breast Cancer Diagnosis Using ANN (Breast Cancer Dataset)**

🔍 **Overview**  
This project builds a custom Artificial Neural Network (ANN) from scratch in Python to classify breast cancer cases using the Breast Cancer Wisconsin dataset.

📌 **Key Features**  
- Manual ANN implementation (forward/backward pass)
- Evaluation with accuracy and a confusion matrix
- Dataset preprocessing and binary classification

📎 [View Project Folder](./project_2_breast_cancer_ann)

## 📂 Project 3 – Car Evaluation Using Naive Bayes (UCI Car Dataset)

🔸 This project uses the Naive Bayes algorithm to classify car acceptability (`unacc`, `acc`, `good`, `vgood`) using the UCI Car Evaluation dataset.  
🔸 It includes training, evaluation, and performance analysis using a confusion matrix and accuracy.

🔗 [View Project Files](./project_3_car_evaluation)

Project 4 – MNIST Digit Classification using ANN
This project implements an Artificial Neural Network (ANN) from scratch using Python to classify handwritten digits from the MNIST dataset.

📌 Key Highlights
Built a multi-layer ANN without any ML libraries.
Preprocessed raw .idx MNIST files directly.
Achieved high classification accuracy on test data.
📂 Files Included
MNIST_ANN_Classification.ipynb: Main notebook
train-images.idx3-ubyte, train-labels.idx1-ubyte: Training data
t10k-images.idx3-ubyte, t10k-labels.idx1-ubyte: Test data

### Project 5 – MNIST Classification using CNN

This project applies a Convolutional Neural Network (CNN) on the MNIST dataset to classify handwritten digits. The architecture was built and tuned from scratch to enhance training and test data accuracy.

#### 🔍 Key Highlights
- Developed a CNN model using Keras
- Achieved over 98% accuracy on test data
- Compared different optimizers and layer configurations

#### 🛠 Technologies Used
- Python
- TensorFlow / Keras
- NumPy, Matplotlib

#### ▶️ How to Run
```bash jupyter notebook mnist_cnn_detailed_experiments.ipynb

📄 [📘 Download Final Report](./Machine_Learning_Programming_Project.pdf)  
A complete, detailed submission report covering all five programming assignments from my Machine Learning coursework at UNB.

## 📄 Final Survey-Based Report

- **Title:** Phishing Detection Using Machine Learning
- **Authors:** Raju Deb & Sadman Sakib Choudhury
- **Abstract:** This report surveys modern phishing detection strategies using ML techniques such as ensemble learning, NLP, and deep neural networks. It critically compares models, datasets, limitations, and future directions in adversarial resilience, scalability, and privacy.
- [📘 Read the Full Report](Survey_Report_Phishing_Detection_ML.pdf)
