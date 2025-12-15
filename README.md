# Bank Customer Churn Prediction using Artificial Neural Networks

## Overview
This project implements an **Artificial Neural Network (ANN)** to predict **bank customer churn (exit probability)** using structured (tabular) customer data.  
The objective is to demonstrate an **end-to-end deep learning workflow**, including data preprocessing, model training, and evaluation for a real-world business classification problem.

This repository is intended as a **foundational deep learning project**, focusing on clarity and correctness rather than model complexity.

---

##  Key Concepts Covered
- Data preprocessing and feature scaling
- Train–test split
- Building an ANN using **TensorFlow / Keras**
- Dense layers with ReLU activation
- Binary classification using Sigmoid activation
- Model compilation and training
- Performance evaluation using accuracy

---

##  Tech Stack
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Scikit-learn**
- **TensorFlow (Keras API)**

---

## Project Structure
ANN/
├── ANN.ipynb
├── requirements.txt
└── README.md

---

## Model Architecture
- Input layer based on feature count
- Hidden layers with **ReLU** activation
- Output layer with **Sigmoid** activation
- Optimizer: **Adam**
- Loss function: **Binary Cross-Entropy**

---

## How to Run
1. Clone the repository
   ```bash
   git clone https://github.com/HarmanBhangu1313/bank-customer-churn-prediction-ann

---

## Installing Dependenices
pip install -r requirements.txt

---

## Results
The ANN successfully learns patterns from the dataset and achieves reasonable classification accuracy, demonstrating the effectiveness of neural networks on structured data.

---

## Learning Outcome
This project helped strengthen understanding of:
	•	Neural network fundamentals
	•	Backpropagation and optimization
	•	Practical implementation of ANN using Keras
	•	End-to-end deep learning workflow