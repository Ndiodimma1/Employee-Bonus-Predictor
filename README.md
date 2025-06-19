# Employee-Bonus-Predictor


<p align="center">
  A simple neural network regression model built with PyTorch to predict employee bonuses based on performance, experience, and project completion rate.
</p>

---

## 🚀 Overview

This project demonstrates how to build and train a neural network to predict employee bonuses using three key features:

- **Performance Score**
- **Years of Experience**
- **Projects Completed**

The model is trained using PyTorch and optimized with Mean Squared Error (MSE) loss and Stochastic Gradient Descent (SGD).

---

## 🧠 Model Architecture

A simple feedforward neural network with:
- Input Layer: 3 features
- Output Layer: 1 neuron (for bonus prediction)

You can optionally upgrade the model with hidden layers and activation functions for more complexity.

```python
self.network = nn.Sequential(
    nn.Linear(3, 1)  # Basic linear regression
)
