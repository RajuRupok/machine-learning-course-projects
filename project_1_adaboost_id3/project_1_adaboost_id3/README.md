# Project 1 – Adaboost with ID3 (Letter Recognition Dataset)

## 📌 Objective
This project implements the AdaBoost algorithm using ID3 (decision tree) as the base learner to classify letters from the UCI Letter Recognition dataset.

## 📂 Files Included
- `AdaBoost_ID3_Letter_Recognition.ipynb` – Primary implementation
- `AdaBoost_ID3_Letter_Recognition_Evaluated.ipynb` – Version with evaluations
- `letter-recognition.data`, `.names`, `.data.Z` – Dataset and metadata
- `Index` – Dataset reference index

## 📊 Dataset
- **Source**: UCI Machine Learning Repository  
- **Features**: 16 numerical features per sample  
- **Classes**: 26 capital letters (A–Z)

## 🧠 Methodology
- ID3 trees are trained as weak learners
- Combined using AdaBoost to improve accuracy
- Evaluated model performance with metrics such as accuracy and confusion matrix

## ✅ Results
- Model accuracy reached **X%**
- Insights gained on how boosting improves weak learner performance

## 🛠️ Tools & Libraries
- Python 3.x
- `NumPy`, `Pandas`
- `scikit-learn`
- `Matplotlib`

## 📎 Notes
This was part of the MSc Machine Learning course at the University of New Brunswick.
