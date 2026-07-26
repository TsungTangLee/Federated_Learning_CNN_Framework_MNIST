# Federated Learning for MNIST Handwritten Digit Classification
Copyright 2026 Tsung-Tang Lee (also known as Osborn Lee or Moe)

# Objective
# Python Data Analysis Project

This project demonstrates a simple Federated Learning framework for handwritten digit classification using the MNIST dataset.

Unlike traditional centralized machine learning, Federated Learning allows each client to keep its own training data locally while only sharing model parameters with the server.

The server aggregates all local models using the Federated Averaging (FedAvg) algorithm to build a global model.

---

# Project Overview

This project implements and compares **Centralized Learning** and **Federated Learning (FedAvg)** using TensorFlow/Keras on the MNIST handwritten digit dataset.

The notebook demonstrates:

- CNN image classification
- Centralized Learning
- Federated Learning (FedAvg)
- Model aggregation
- Accuracy comparison
- Loss comparison
- Time complexity analysis
- Discussion and conclusions

This project is intended for educational, academic, and research purposes.

---

# Features

- TensorFlow / Keras implementation
- CNN for handwritten digit recognition
- Centralized Learning
- Federated Learning
- FedAvg Algorithm
- Accuracy Comparison
- Loss Comparison
- Model Saving
- Time Complexity Analysis
- Discussion

---

# Environment

- Python 3.10+
- TensorFlow 2.x
- NumPy
- Matplotlib
- Google Colab

Install

```bash
pip install tensorflow numpy matplotlib
```

---

# Dataset

MNIST Handwritten Digits

- 60,000 Training Images
- 10,000 Testing Images

---

# Repository Structure

```
Python_Data_Analysis_Project/

│
├── Python_Data_Analysis_Project.ipynb
├── README.md
├── LICENSE
├── Centralized_Model.keras
├── Federated_Model.keras
└── figures/
```

---

# Applications

Centralized Learning

- Enterprise AI
- Manufacturing
- Data Centers
- Cloud AI

Federated Learning

- Healthcare
- Banking
- IoT
- Mobile AI
- Autonomous Vehicles
- Satellite Networks
- Edge AI

---

# License

This repository **is NOT open-source for commercial use**.

Permission is granted for:

- Personal learning
- Educational use
- Academic research

Commercial use, redistribution, integration into commercial software, paid courses, consulting services, or products **requires a separate commercial license from the copyright holder.**

See the LICENSE file for details.

---

# Citation

If you use this project in academic work, please cite this repository appropriately.

The Federated Averaging (FedAvg) algorithm implemented in this repository is based on:

Brendan McMahan et al.

Communication-Efficient Learning of Deep Networks from Decentralized Data

AISTATS 2017
