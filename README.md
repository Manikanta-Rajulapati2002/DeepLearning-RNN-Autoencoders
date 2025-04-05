# Deep Learning Assignments – Autoencoders & RNNs

## 👨‍🎓 Student Information
- **Name:** Manikanta Rajulapati
- **Student ID:** 700762001
- **University:** University of Central Missouri
- **Semester:** Spring 2025

---

## 📝 Overview

This repository contains 4 Jupyter Notebook assignments focused on implementing **Autoencoders** and **Recurrent Neural Networks (RNNs)** using TensorFlow/Keras.

---

## 📘 Assignment Breakdown

### ✅ **Question 1: Basic Autoencoder**
- Dataset: MNIST
- Goal: Train a fully connected (Dense) autoencoder to reconstruct input digits.
- Features:
  - Encoder (784 → 32)
  - Decoder (32 → 784)
  - Visualization of reconstruction quality

---

### ✅ **Question 2: Denoising Autoencoder**
- Dataset: MNIST with Gaussian noise (mean=0, std=0.5)
- Goal: Train a denoising autoencoder to remove noise from images.
- Output: Visual comparison between noisy input, reconstructed output, and ground truth.

---

### ✅ **Question 3: Text Generation using RNN**
- Dataset: Shakespeare (via TensorFlow download)
- Model: LSTM (character-level) with Embedding → LSTM → Dense
- Features:
  - Predict next character
  - Use of **temperature scaling** to control randomness in output
  - Text generated with multiple temperature values

---

### ✅ **Question 4: Sentiment Classification using RNN**
- Dataset: IMDB Reviews (Binary sentiment: Positive or Negative)
- Model: Embedding → LSTM → Dense
- Output:
  - Accuracy, Precision, Recall, F1-Score
  - Confusion Matrix
  - Discussion on **Precision-Recall Tradeoff**

---

## ▶️ How to Run

### 🔧 Requirements
- Python ≥ 3.8
- TensorFlow ≥ 2.12
- NumPy
- Matplotlib
- scikit-learn

### 🛠️ Run the Notebooks
1. Open in Jupyter Notebook / JupyterLab / VS Code
2. Execute each cell step-by-step

Example:
```bash
jupyter notebook Question_1.ipynb
