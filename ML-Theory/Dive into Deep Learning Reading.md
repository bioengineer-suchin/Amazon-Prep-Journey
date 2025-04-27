# Dive Into Deep Learning (D2L.ai) - Theory Notes 📚

Welcome to my full structured notes for the **Dive Into Deep Learning** book, an essential part of my preparation for Applied Scientist roles!

These notes focus on theory, core formulas, and practical understanding to build real-world AI/ML systems.

---

## 📖 Chapters Overview

---

### 1. Introduction

- **Machine Learning (ML)**: Algorithms that improve from experience/data without being explicitly programmed.
- **Deep Learning**: A subset of ML focused on multi-layered neural networks that learn complex data representations.

---

### 2. Preliminaries

- **Tensors**: Multidimensional arrays (scalars, vectors, matrices, tensors).
- **Operations**: Elementwise addition/multiplication, broadcasting, matrix multiplication.
- **Gradients**: Essential for training ML models; automatic differentiation frameworks like PyTorch simplify this.

---

### 3. Linear Regression

- **Model**:  
  \[
  \hat{y} = Xw + b
  \]
- **Loss Function**: Mean Squared Error (MSE)
- **Optimization**: Stochastic Gradient Descent (SGD)

---

### 4. Multilayer Perceptrons (MLP)

- **Neural Network Structure**: Layers of linear transformations + non-linear activations.
- **Activations**:
  - ReLU
  - Sigmoid
  - Tanh
- **Purpose**: Introduce non-linearity for learning complex patterns.

---

### 5. Optimization Algorithms

- **Challenges**: Choosing learning rate, avoiding slow convergence.
- **Popular Optimizers**:
  - SGD
  - Momentum
  - AdaGrad
  - Adam

---

### 6. Overfitting and Regularization

- **Overfitting**: Poor generalization despite good training accuracy.
- **Solutions**:
  - Weight Decay (L2 Regularization)
  - Dropout Layers
  - Early Stopping

---

### 7. Computation and Efficiency

- **Mini-batch Training**: Increases training speed.
- **Parallelism**: Utilize CPUs and GPUs for faster model training.
- **Numerical Stability**: Techniques like log-sum-exp for preventing overflow.

---

### 8. Convolutional Neural Networks (CNNs)

- **Purpose**: Process spatial data (images).
- **Core Concepts**:
  - Convolutional layers
  - Pooling layers
  - Local Receptive Fields
- **Advantages**: Shared weights, translation invariance.

---

### 9. Recurrent Neural Networks (RNNs)

- **Purpose**: Model sequential data (time series, text).
- **Challenges**: Vanishing/exploding gradients.
- **Solutions**:
  - Long Short-Term Memory (LSTM)
  - Gated Recurrent Units (GRU)

---

### 10. Attention Mechanisms and Transformers

- **Attention**: Focus on important parts of input sequences.
- **Transformer Model**:
  - Self-Attention
  - Multi-Head Attention
  - Positional Encoding
- **Impact**: Replaced RNNs in many NLP tasks (e.g., BERT, GPT).

---

### 11. Evaluation Metrics

- **Regression**:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - \( R^2 \) Score
- **Classification**:
  - Accuracy
  - Precision, Recall, F1 Score
  - ROC-AUC

---

# 🧠 Key Insights

- Understanding **gradients**, **loss functions**, and **optimization** is critical for any ML system.
- Deep Learning models are **function approximators** — they learn mappings between data and labels/features.
- **Theory is essential**, but **building real-world projects** is where true learning happens.

---

# 📢 Note

These notes are concise summaries for quick revision.  
For full explanations, visualizations, and mathematical proofs, please refer to [Dive Into Deep Learning](https://d2l.ai/).

---
