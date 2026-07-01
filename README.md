# Python Data Science Teaching

Training material developed and delivered for the **Zindi Africa** data science community, on invitation from a Zindi Ambassador.

---

## About This Repository

This repository contains the complete material from a Data Science with Python training session organized within the **Zindi Africa** ecosystem — Africa's largest professional network and AI challenge platform for data scientists (+75,000 members across 185 countries).

The session was designed to take participants from Python fundamentals all the way to implementing neural networks **from scratch**, without any deep learning framework — just NumPy.

---

## Content Overview

### Task 1 — Data Science & Python Overview
- What is Data Science ? Workflow and real-world applications
- Why Python for Data Science ? Key libraries overview
- Setting up a Python environment (venv, pip, conda)

### Task 2 — Python for Data Science
- Basic operations, data types, string manipulation
- Lists, dictionaries, comprehensions
- NumPy and Pandas fundamentals

### Task 3 — Applied Machine Learning Projects

#### 3.1 Linear Regression with Scikit-learn
- Exploratory Data Analysis (EDA)
- Train/test split
- Model training and evaluation (MAE)
- Model serialization with `pickle`

#### 3.2 Perceptron — From Scratch 
Implementation of a Perceptron from scratch using only NumPy:
- Forward propagation
- Delta rule (weight update)
- Tested on OR, AND, XOR problems
- Demonstrated the XOR limitation → motivation for backpropagation

#### 3.3 Neural Network with Backpropagation — From Scratch
Full implementation of a multi-layer neural network using only NumPy:
- Configurable architecture (`layers=[2, 2, 1]`)
- Sigmoid activation function + derivative
- Forward propagation
- Backpropagation algorithm
- Weight update phase
- Loss tracking (MSE) across epochs
- XOR problem resolution (validates non-linear learning)

---

##  Repository Structure

```
python-ds-teaching/
│
├── README.md
│
├── main.ipnb # all the code 
│── data
```

# Launch Jupyter
jupyter 
```

---

## 🔑 Key Highlights

### Why implement Neural Networks from scratch ?

Using only NumPy (no PyTorch, no TensorFlow) to implement a neural network forces a deep understanding of:

- How **weights are initialized** and why normalization matters
- How **forward propagation** computes activations layer by layer
- How **backpropagation** computes gradients via the chain rule
- How **weight updates** reduce the loss iteratively

This is the foundation that makes frameworks like PyTorch understandable rather than magic.

### The XOR Problem — A Classic Teaching Case

The XOR problem (`0⊕0=0`, `0⊕1=1`, `1⊕0=1`, `1⊕1=0`) is **not linearly separable** — a single Perceptron cannot solve it (Minsky & Papert, 1969). This is demonstrated empirically in the training material, motivating the need for **multi-layer networks + backpropagation**.


##  Context — Zindi Africa

[Zindi](https://zindi.africa) is Africa's largest professional network and AI challenge platform, connecting data scientists across 185 countries. Their Ambassador Program supports data science community building across the continent through workshops, hackathons, and training events.

This training was delivered on invitation from a **Zindi Ambassador** as part of community capacity-building efforts in data science and AI.

---

## AI Usage

**No AI tools** were used to write the code or the teaching content of this repository.

All implementations — including the Perceptron and the Neural Network with backpropagation — were written manually, based on:


Rosebrock, A. (2017). Deep Learning for Computer Vision with Python. PyImageSearch.
— specifically the foundational chapters on Perceptron and backpropagation from scratch.


**Exception**: The README file of this repository was written with the assistance of an AI tool (Claude, Anthropic) for structure and English phrasing.

## License

MIT License — feel free to use this material for educational purposes.
If you have some suggestion or detect any problem, don't hesitated to improve it and made some comments

