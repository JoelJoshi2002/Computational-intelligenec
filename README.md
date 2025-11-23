# 🧠 Computational Intelligence – Lab Projects

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=for-the-badge&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Red?style=for-the-badge&logo=keras)

This repository contains my lab projects for the **Computational Intelligence** course at the **University of South Bohemia (Jihočeská univerzita v Českých Budějovicích)**.

The aim of these labs is to build, understand, and experiment with neural network architectures from the ground up. This repository serves both as my personal progress log and as a resource for others beginning their journey into neural networks and deep learning.

---

## 🚀 Topics Covered

These labs explore a range of foundational concepts in Computational Intelligence, organized by key themes:

### 🔹 Neural Network Fundamentals
* Implementing basic feedforward networks.
* Understanding training loops, loss functions, optimizers, and activation functions.

### 🔹 TensorFlow & Keras
* Building models using both the **Sequential** and **Functional** APIs.
* Training, validating, and tracking performance metrics.
* Visualizing learning curves (Loss/Accuracy over epochs).

### 🔹 Convolutional Neural Networks (CNNs)
* Image classification tasks using datasets like **MNIST** and **Fashion-MNIST**.
* Feature extraction using **Convolution** and **Pooling** layers.
* Implementing regularization techniques (Dropout, Batch Normalization).

### 🔹 Autoencoders
* Designing Encoder–Decoder architectures.
* Dimensionality reduction.
* Reconstruction analysis.

### 🔹 Data Preprocessing
* Normalization, reshaping, and one-hot encoding.
* Inspecting and visualizing datasets.
* Preparing image data specifically for CNN models.

### 🔹 Model Evaluation
* Analyzing Accuracy & Loss metrics.
* Generating Confusion Matrices.
* Identifying patterns of overfitting and underfitting.

---

## 🛠️ Tools & Technologies

The projects are built using the following stack:

* **Language:** Python 3.x
* **Frameworks:** TensorFlow 2.x, Keras
* **Libraries:** NumPy, Matplotlib, Pandas
* **Environment:** Jupyter Notebook / Google Colab

---

## 🚀 Getting Started

You can run the notebooks in this repository either via the cloud (Google Colab) or on your local machine.

### ✔️ Option 1: Run on Google Colab (Recommended)
This is the easiest way to start as it requires no local environment setup.

1.  Navigate to any lab folder in this repository (e.g., `Lab 3 - CNNs and Autoencoders`).
2.  Click on the `.ipynb` file.
3.  Click the **"Open in Colab"** badge (if available) or change the URL domain from `github.com` to `github.dev` to view, or copy the GitHub URL directly into [Google Colab](https://colab.research.google.com/).
4.  Run the cells instantly!

### ✔️ Option 2: Run Locally
To run these projects on your own machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```

2.  **Create a virtual environment (Optional but recommended):**
    ```bash
    python -m venv venv
    # Windows
    venv\Scripts\activate
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install tensorflow numpy matplotlib jupyter
    ```

4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

---

## 📂 Repository Structure

* `Lab 1/` - Introduction to Neural Networks & TensorFlow
* `Lab 2/` - Deep Feedforward Networks & Optimization
* `Lab 3/` - Convolutional Neural Networks (CNNs) & Autoencoders
* `Data/` - (Optional: Scripts for downloading specific datasets)

---

## 📜 License

This project is for educational purposes related to the coursework at the University of South Bohemia.
