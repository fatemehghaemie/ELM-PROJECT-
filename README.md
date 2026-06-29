---

## 📌 Overview
This repository contains a **from-scratch implementation** of two popular neural network paradigms using **only NumPy**:
1. **Extreme Learning Machine (ELM):** A single-hidden layer feedforward network (SLFN) where hidden weights are randomly initialized and fixed, and output weights are analytically computed using the Moore-Penrose pseudo-inverse or Ridge regression.
2. **Multi-Layer Perceptron (MLP):** A traditional feedforward neural network trained fully with iterative Gradient Descent and Backpropagation.

This project was developed as part of the **Artificial Intelligence Lab at Amirkabir University of Technology (Tehran Polytechnic)** under the supervision of Dr. Ghaemi.

---

## 🛠️ Key Features
* **Zero Deep Learning Frameworks:** Implemented purely in vectorised NumPy without relying on PyTorch, TensorFlow, or Scikit-Learn.
* **ELM Solvers:** Supports both basic Pseudo-Inverse (`np.linalg.pinv`) and Ridge Regression solvers for advanced numerical stability.
* **MLP Components:** Includes full implementation of Forward Pass, Activation functions (`ReLU`, `Tanh`, `Sigmoid`), Analytical Derivatives, Cross-Entropy & MSE Loss, and Backpropagation logic.
* **Versatility:** Ready for both multi-class Classification and Regression tasks.

---

## 🚀 Getting Started

### Prerequisites
Make sure you have `numpy` installed:
```bash
pip install numpy









