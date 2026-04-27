# 🧠 Binary Classification Neural Network

This project implements a deep learning model for binary classification using TensorFlow and Keras. The model is built using a fully connected Artificial Neural Network (ANN) and achieves strong performance on the dataset.

---

## 📌 Project Overview

- 🔍 Problem Type: Binary Classification (0 or 1)
- 🧠 Model: Deep Neural Network (ANN)
- ⚙️ Framework: TensorFlow / Keras
- 📊 Evaluation Metric: Accuracy

---

## 🏗️ Model Architecture

The model consists of multiple dense layers with ReLU activation and a sigmoid output layer:

- Dense (256) → ReLU  
- Dense (128) → ReLU  
- Dense (64) → ReLU  
- Dense (32) → ReLU  
- Output Layer (1 neuron) → Sigmoid  

Loss Function: `binary_crossentropy`  
Optimizer: `Adam`  

---

## 📈 Model Performance

| Metric   | Value  |
|----------|--------|
| Accuracy | 87.4%  |
| Loss     | 1.0438 |

---

## ⚙️ Installation

```bash
pip install tensorflow numpy pandas scikit-learn
