

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








## 📌 Overview (Phase 2)
In this phase, the custom-built **Extreme Learning Machine (ELM)** and **Multi-Layer Perceptron (MLP)** networks (implemented from scratch using NumPy) are deployed and benchmarked against a real-world financial/agricultural engineering dataset: **Meat Freshness Classification**. 

The main goal is to evaluate their generalization capabilities, computational efficiency, and robust behavior during model persistence (saving/loading for production).

This project was developed as part of the **Artificial Intelligence Lab at Amirkabir University of Technology (Tehran Polytechnic)** under the supervision of Dr. Mehdi Dehghan and Lab Instructor Behnam Yousefi Mehr.

---

## 🛠️ Advanced Features & Technical Aspects
* **Real-World Dataset:** Evaluated on a comprehensive tabular dataset for multi-class classification (predicting whether meat is Fresh, Semi-Fresh, or Spoiled).
* **Statistical Performance Analysis:** In-depth evaluation using **Accuracy**, **Cross-Entropy Loss curves**, and execution time benchmarks.
* **Model Serialization (Production Ready):** Implemented saving and loading pipelines:
  * ELM weights saved directly as serialized `.model` parameters.
  * MLP architectures exported cleanly using `.joblib` format.
* **Continuous Retraining Analysis:** Critical evaluation of which network fits best into a continuous data streaming pipeline (CI/CD for Machine Learning).

---

## 📊 Performance & Architecture Benchmark

| Metric / Feature | Extreme Learning Machine (ELM) | Multi-Layer Perceptron (MLP) |
| :--- | :--- | :--- |
| **Dataset Application** | Meat Freshness Dataset | Meat Freshness Dataset |
| **Training Execution Time**| ⚡ **Milliseconds** (Single-step matrix calculation) | ⏳ **Seconds/Minutes** (Iterative Backpropagation over 1000+ epochs) |
| **Loss Convergence** | Instant analytical minimum | Smooth gradient descent convergence |
| **Production Export** | `.model` file | `.joblib` / `.pkl` bundle |
| **Continuous Streaming** | Highly Suitable (Incremental low-cost matrix update) | High cost (requires full or partial weight adaptation) |

---

## 🚀 How to Run Phase 2
Ensure you have the required analytical libraries installed:
```bash
pip install numpy joblib matplotlib









