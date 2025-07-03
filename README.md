# Digit_classification_mnist_dataset
# 🧠 MNIST Digit Classification

This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify handwritten digits from the MNIST dataset. The model achieved an accuracy of **95.14%** on the test set.

---

## 💡 Objective

To develop a deep learning model that can accurately recognize handwritten digits (0–9) from grayscale 28x28 pixel images using CNNs.

---

## 🗃️ Dataset Overview

- **Dataset:** MNIST
- **Source:** `tensorflow.keras.datasets`
- **Training Samples:** 60,000  
- **Test Samples:** 10,000  
- **Image Size:** 28 x 28 pixels (Grayscale)  
- **Number of Classes:** 10 (digits 0–9)

---

## 🏗️ Model Architecture
Input: 28x28x1
↓
Conv2D (32 filters, 3x3) + ReLU
↓
MaxPooling2D (2x2)
↓
Conv2D (64 filters, 3x3) + ReLU
↓
MaxPooling2D (2x2)
↓
Flatten
↓
Dense (128) + ReLU
↓
Dense (10) + Softmax

Evaluation Metric: Accuracy

Test Accuracy: ⭐ 95.14%
