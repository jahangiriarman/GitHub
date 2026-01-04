# MNIST Handwritten Digit Classification (PyTorch)

This repository contains an implementation of neural-network classification of handwritten digits from the MNIST dataset using **PyTorch**.

The project includes preprocessing, model design, training loops, evaluation, and result analysis.

---

## Project Overview
- Dataset: MNIST handwritten digits (0–9)
- Framework: PyTorch
- Task: Multi-class image classification
- Input: 28×28 grayscale images (60,000 Traing + 10,000 Test)
- Output: Digit class (0–9)

---

## Models
- 1. Fully connected neural network (MLP)
  2. Convolutional neural network (CNN)
- ReLU activations
- Cross-entropy loss
- Optimized using stochastic SGD, Adam, AdamW, and RMSPROP
- Includes optional AMP on CUDA
- Includes learning-rate schedulers
---

## Results
The trained models achieve high classification accuracy, demonstrating effective learning of digit representations.

(97.25% with MLP and 98.83% with CNN)

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/mnist-pytorch-classifier.git
