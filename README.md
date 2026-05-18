# Introduction to JAX
### Embedded Machine Learning — MSc Assignment
**Based on:** [learn-jax by agwr](https://github.com/agwr/learn-jax)

---

## 📌 Overview

This repository contains a comprehensive, self-contained tutorial 
on JAX — a high-performance numerical computing library developed 
by Google for machine learning research and deployment.

The tutorial covers all core JAX concepts with practical, 
hands-on examples and is designed for students and practitioners 
working with embedded machine learning systems.

---

## 📚 Topics Covered

| # | Topic | Description |
|---|-------|-------------|
| 1 | Just-In-Time Compilation | Speed up Python with JAX's JIT and XLA |
| 2 | Automatic Vectorization | Batch computation using vmap |
| 3 | Automatic Differentiation | Gradients with grad and value_and_grad |
| 4 | PyTrees | Handle nested data structures |
| 5 | Distributed Computing
| 6 | Stateful computations
| 7 | 7. Control flow and logical operators with JIT
| 8 | Embedded ML Applications | Lightweight inference for edge devices |

---

## 🗂️ Repository Structure

```text
learn-jax-tutorial/
├── README.md
├── .gitignore
├── requirements.txt
│
├── notebooks/
│   ├── 0. Introduction to JAX.ipynb
│   ├── 1. jit_compilation.ipynb
│   ├── 2. automatic_vectorization.ipynb
│   ├── 3. automatic_differentiation.ipynb
│   ├── 4. pytrees.ipynb
│   ├── 5. distributed computing.ipynb
│   ├── 6. stateful computation.ipynb
│   ├── 7. distributed Computing.ipynb
│   └── 08_embedded_ml.ipynb
│
├── src/
│   ├── 01. Linear Regression.ipynb
│   ├── 02. Neural Network Classifier.ipynb
│   ├── 03. Gradient Descent Visualization.ipynb
│   ├── EMBEDDED ML 1_ Lightweight Model for Edge Devices.ipynb
│   ├── EMBEDDED ML 2_ Model Quantization.ipynb
│   ├── EMBEDDED ML 3_ Efficient Batch Inference.ipynb
│   └── Practical Examples_Combined.ipynb
│
└── docs/
    └── Introduction to JAX_Tutorial.pdf
