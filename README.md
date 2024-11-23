[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/KPIpT6T5)

# Fashion-MNIST Image Classification and Product Recommendation System

## Overview

This repository contains a machine learning project that leverages the **Fashion-MNIST dataset** to classify images of clothing and recommend similar products based on the predicted category. It uses **TensorFlow/Keras** for building and training a neural network and **Matplotlib** for visualization.

## Features

- **Image Classification**:
  - A neural network trained on the Fashion-MNIST dataset to classify clothing into 10 categories.
- **Visualization**:
  - Displays sample images and their labels.
  - Visualizes the input image along with the recommended similar products.
- **Recommendation System**:
  - Suggests 5 similar products based on the predicted category of the input image.

---

## Dataset

- **Fashion-MNIST**:
  - 70,000 grayscale images of size 28x28 pixels.
  - 10 clothing categories:
    - T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot.
  - Dataset is automatically loaded using TensorFlow's `keras.datasets.fashion_mnist`.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/fashion-mnist-recommendation.git
   cd fashion-mnist-recommendation
