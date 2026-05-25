# 🧠 Image Classification: Exploring ML Algorithms from Scratch

This repository is a hands-on, deep-dive exploration into foundational Machine Learning algorithms for image classification. Using the **FashionMNIST dataset** (70,000 grayscale images of clothing and shoes, 28x28 pixels), we build, tune, and evaluate various models to deeply understand their inner workings, strengths, and limitations.

> ⚠️ 
> This README is just a quick directory of the repository. **For the full, step-by-step mathematical analysis, architectural choices, and detailed conclusions, please read the included PDF Documentation files.** The true depth of this project lies within those reports.

## 📂 What's Inside (Repository Structure)

The project is divided into three main experimental phases, each containing its respective Jupyter Notebook and a detailed PDF report:

### 1. Distance-Based Algorithms 
* **Files:** `KnnTests.ipynb` | 📄 `documentation.pdf`
* **Contents:**
  * Implementation and testing of **K-Nearest Neighbors (K-NN)** and the **Nearest Centroid Classifier**.
  * Extensive hyperparameter tuning (e.g., finding the optimal $k$ neighbors).
  * Comparing distance metrics (Euclidean vs. Manhattan distance).
  * Best achieved accuracy: ~86.3%.

### 2. Linear Classifiers & Perceptrons
* **Files:** `linear_classifiers.ipynb` | 📄 `documentation.pdf`
* **Contents:**
  * Building the **Perceptron** algorithm and understanding linear separability.
  * Implementing multi-class classification techniques from scratch: **One-vs-One (OvO)** and **One-vs-All (OvA)**.
  * Exploring advanced perceptron variants to stabilize weights: **Averaged Perceptron** and the **Pocket Algorithm**.

### 3. Dimensionality Reduction & Clustering
* **Files:** `notebook.ipynb` | 📄 `documentation.pdf`
* **Contents:**
  * Applying **Principal Component Analysis (PCA)** for dimensionality reduction and evaluating information retention (variance).
  * Unsupervised grouping using the **K-Means** clustering algorithm.
  * Advanced distance metrics: Exploring the difference between standard Euclidean distance and **Mahalanobis distance** for better decision boundaries.

## 🔬 Core Methodology

Throughout all notebooks, we avoided a static "plug-and-play" approach. Instead, we focused on systematic exploration:

* **Feature Extraction:** Altering and testing various data representation methods before feeding the images into the models.
* **Algorithm Exploration:** Understanding *why* an algorithm fails or succeeds based on the specific visual overlap of the FashionMNIST classes (e.g., Shirts vs. T-shirts).
* **Robust Evaluation:** Using **K-Fold Cross-Validation** to find optimal hyperparameters and prevent overfitting, evaluating models with Accuracy, Precision and Confusion Matrices.

---
