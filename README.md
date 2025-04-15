# 🧠 Neural Networks for Handwritten Digit Recognition (Multiclass)

This project is a beginner-friendly implementation of a neural network to recognize handwritten digits (0-9) using multiclass classification. It uses the popular [MNIST dataset](http://yann.lecun.com/exdb/mnist/) and is inspired by Andrew Ng’s Deep Learning Specialization.

## 📌 Project Description

- Builds a simple feedforward neural network from scratch
- Trained on the MNIST dataset of handwritten digits
- Uses NumPy for matrix operations (no deep learning libraries!)
- Implements forward propagation, cost calculation, backpropagation, and gradient descent manually
- Evaluates accuracy on training and test data

This is a great learning project if you're starting out with machine learning and want to understand how neural networks work behind the scenes!

## 🗃️ Dataset

- **MNIST** — 70,000 grayscale images of handwritten digits (28x28 pixels)
- 60,000 for training, 10,000 for testing
- Each image is labeled with a digit from **0 to 9**

## 📁 Files

- `main.ipynb` – Main Jupyter Notebook with full implementation
- `data/` – Folder containing training and testing datasets in `.csv` format
- `weights/` – Optional: store model weights if saving/loading is implemented

## 📊 Model Architecture

- Input layer: 784 units (28x28 pixels)
- Hidden layers: You define the size! (e.g., 128, 64 neurons)
- Output layer: 10 units (one for each digit class)
- Activation: Sigmoid or ReLU (you can experiment!)

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Mehdix17/Neural-Networks-for-Handwritten-Digit-Recognition-Multiclass.git
   cd Neural-Networks-for-Handwritten-Digit-Recognition-Multiclass
