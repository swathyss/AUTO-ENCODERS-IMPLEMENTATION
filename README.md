# 🔢 MNIST Autoencoder using Deep Learning

![Python](https://img.shields.io/badge/Python-3.9-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Autoencoder](https://img.shields.io/badge/Model-Autoencoder-green)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-yellow)

A deep learning project focused on building and evaluating an **Autoencoder model** for **image reconstruction** using the **MNIST handwritten digits dataset**.
---

# 📘 Project Overview

This project implements an **Autoencoder neural network** to learn compressed representations of images and reconstruct them.

The project covers the complete deep learning pipeline including:

- Dataset loading and preprocessing  
- Encoder–decoder architecture design  
- Model training and validation  
- Loss curve visualization  
- Image reconstruction and comparison  

The goal is to build a **model that can efficiently compress and reconstruct handwritten digit images**.

---

# 🎯 Objective

The main objectives of this project are:

🔹 Understand autoencoder architecture  
🔹 Learn dimensionality reduction using neural networks  
🔹 Build encoder and decoder networks  
🔹 Train the model on image data  
🔹 Evaluate reconstruction quality  
🔹 Visualize original vs reconstructed images  

---

# 📂 Dataset Information

The dataset used is the **MNIST Handwritten Digits Dataset**.

### Dataset Details

| Feature | Description |
|--------|------------|
| Image Size | 28 × 28 pixels |
| Color Type | Grayscale |
| Classes | Digits (0–9) |
| Training Samples | 60,000 |
| Test Samples | 10,000 |

---

# 🧹 Data Preprocessing

Before training the model, the following preprocessing steps were applied:

### ✔ Normalization
- Pixel values scaled to range **0–1**

### ✔ Reshaping
- Images reshaped into appropriate input format for the model

### ✔ Train/Test Split
- Predefined MNIST training and test datasets used

---

# 🧠 Autoencoder Architecture

The model consists of two main components:

### 🔹 Encoder
- Compresses input image into a **latent representation**
- Reduces dimensionality

### 🔹 Decoder
- Reconstructs image from latent space
- Attempts to recreate original input

### Architecture Components

✔ Dense / Flatten Layers  
✔ Latent Space Representation  
✔ Decoder Layers  
✔ Output Layer (same size as input)  

---

# ⚙ Model Training

The autoencoder was trained using the MNIST training dataset.

### Training Configuration

- Loss Function: Mean Squared Error (MSE)  
- Optimizer: Adam  
- Batch Size: 32  
- Epochs: 20–50  

### Monitoring

- Training Loss vs Validation Loss curves  
- Model convergence behavior  

---

# 📊 Model Evaluation

The model was evaluated using the test dataset.

### Evaluation Methods

- Reconstruction loss  
- Visual inspection of reconstructed images  

---

# 🔍 Reconstruction Visualization

To analyze performance:

- Original images were displayed  
- Reconstructed images were shown side-by-side  

This helps in understanding how well the model learned the data representation.

---

# 🛠 Tech Stack

| Tool | Purpose |
|----|----|
| Python | Programming language |
| TensorFlow / Keras | Deep learning framework |
| NumPy | Numerical computation |
| Matplotlib | Visualization |
| Scikit-learn | Utility functions |
| Google Colab | Development environment |

---

# 📁 Repository Structure

```
mnist-autoencoder/

│
├── DL_Assignment_3_AutoEncoders.ipynb
├── README.md
└── DL Assignment 3 - Auto Encoders.pdf
```

---

# 🚀 How to Run the Project

### 1️⃣ Open the Notebook

Click the **Google Colab button above**.

---

### 2️⃣ Install Required Libraries

```python
pip install tensorflow numpy matplotlib scikit-learn
```

---

### 3️⃣ Run the Notebook

Run all cells sequentially to:

- Load MNIST dataset  
- Preprocess data  
- Build autoencoder model  
- Train the model  
- Plot loss curves  
- Visualize reconstructed images  

---

# 🧠 Key Learning Outcomes

✔ Understanding autoencoders  
✔ Dimensionality reduction using neural networks  
✔ Image reconstruction techniques  
✔ Model training and evaluation  
✔ Visualization of deep learning results  

---

# 📌 Academic Submission

This project was developed as part of a **Deep Learning assignment** to demonstrate the implementation of an **Autoencoder model for image reconstruction using the MNIST dataset**.
