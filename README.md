# Federated Learning for MNIST Handwritten Digit Classification
# Copyright 2026 Tsung-Tang Lee (also known as Osborn Lee or Moe)

Objective
This project demonstrates a simple Federated Learning framework for handwritten digit classification using the MNIST dataset.

Unlike traditional centralized machine learning, Federated Learning allows each client to keep its own training data locally while only sharing model parameters with the server.

The server aggregates all local models using the Federated Averaging (FedAvg) algorithm to build a global model.
