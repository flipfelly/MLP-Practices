# 🚀 Pattern Classification with Perceptron Networks

This repository contains a pattern classification experiment using a Single-Layer Perceptron Network with Softmax activation, trained to distinguish eight distinct classes. The goal was to test different learning approaches and evaluate the model's performance.

Consider a pattern classification problem consisting of eight distinct classes. The pattern distribution forms a circle centered at the origin with a unit radius. Within this circle, there is a diamond also centered at the origin, with sides equal to the square root of 1.

The classes are distributed as follows:

- C1, C2, C3, and C4: Correspond to the four sectors within the diamond.
- C5, C6, C7, and C8: Correspond to the sectors defined by the circle and the sides of the diamond.


<p align="center">
  <img src="https://github.com/user-attachments/assets/54b930d1-8c63-4aa7-a822-5339575c34fb" alt="Descrição da imagem" width="500">
</p>



## 🧠 Model Architecture

✅ **Layers:** Single-layer Perceptron

✅ **Neurons:** 8 output layer neurons (one for each class)

✅ **Activation function:** Softmax, for multiclass classification

✅ **Training epochs:** 50

✅ **Learning methods:**

✔️ Conventional Delta Rule

✔️ Delta Rule with Momentum Term

## 🔍 What was tested?

📌 The impact of the momentum term on convergence 🚀

📌 The efficiency of the Perceptron in a non-linearly separable problem

## 📊 Key Findings

1️⃣ The Delta Rule with Momentum accelerated convergence and reduced oscillation, improving training stability and resulting in lower error.

2️⃣ The confusion matrix and classification report showed that the Momentum-enhanced version performed better in classifying all eight classes, reducing prediction errors.

3️⃣ The Softmax activation function enabled the Perceptron to perform multiclass classification, effectively distinguishing patterns.
