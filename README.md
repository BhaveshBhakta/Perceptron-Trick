# Perceptron Trick

This repository demonstrates the **Perceptron Trick** algorithm for binary classification using a toy dataset created with `sklearn.datasets`. The Perceptron algorithm is implemented from scratch in Python to train a linear classifier and visualize the decision boundary.

---

## Overview

The project uses the following key components:

1. **Dataset Generation**: 
   - A two-class dataset with two features is created using the `make_classification` function from Scikit-learn. 
   - The data points are visualized in a 2D plot.

2. **Perceptron Algorithm**: 
   - A Perceptron model is implemented from scratch to find a linear decision boundary.
   - The weights are updated iteratively using a learning rate and the misclassified points.

3. **Decision Boundary Visualization**: 
   - The decision boundary learned by the Perceptron model is plotted alongside the dataset points.

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/BhaveshBhakta/Perceptron-Trick.git
   ```
2. Install required libraries:
   ```bash
   pip install numpy matplotlib scikit-learn
   ```
---
