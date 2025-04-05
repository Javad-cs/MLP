# Multilayer Perceptron (MLP) — NumPy Implementation

This project implements a Multilayer Perceptron (MLP) for binary classification from scratch using only NumPy. The model is trained and evaluated on the synthetic "moons" dataset. All components including forward pass, backpropagation, loss computation, and parameter updates are manually implemented without using any machine learning libraries.

---

## Features

- Manual implementation of forward and backward passes
- Two hidden layers with ReLU activations
- Sigmoid output layer for binary classification
- Trained using binary cross-entropy loss and gradient descent
- Visualizations of training data and model predictions

---

## Dataset

The model uses the `make_moons` dataset from scikit-learn, which generates a 2D binary classification task with moderate noise.

- 500 total samples
- Binary targets
- 80/20 train-test split

---

## Architecture

Input (2D)  
↓  
Linear → ReLU  
↓  
Linear → ReLU  
↓  
Linear → Sigmoid  
↓  
Output (1D)

## Project Structure

MLP/  
├── Multilayer_Perceptron_(MLP)_neural_network.ipynb   # Main Jupyter notebook  
├── README.md                                           # Project documentation

## How to Run

### In Google Colab

Simply upload the notebook and run all cells.

### Locally

Install the required packages and open the notebook:

```bash
pip install numpy matplotlib scikit-learn
jupyter notebook