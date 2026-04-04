# Image Classification: Exploring K-NN and Nearest Centroid
This project is a hands-on exploration of distance-based Machine Learning algorithms (like K-Nearest Neighbors and Nearest Centroid).

We trained and tested our models on the FashionMNIST dataset, which contains 70,000 grayscale images (28x28 pixels) of clothes and shoes.

Important Note: This README is just a quick summary of our results. For the full, step-by-step analysis, the math behind our choices, and detailed code explanations, please read the Documentation file included in this repository.

## Methodology & Experimentation

Throughout this project, we focused on the systematic exploration and optimization of the machine learning pipeline. Our approach was not static; rather, it was based on continuous experimentation across the following areas:

* **Feature Extraction Process:** We experimented extensively with data representation. We altered and tested various feature extraction methods to find the optimal way to transform the raw information before feeding it into the models.
* **Algorithm Exploration:** We developed and evaluated multiple machine learning algorithms to practically examine which approach (or family of models) best fits the specific nature of our problem.
* **K-Fold Cross-Validation & Hyperparameter Tuning:** To find the optimal hyperparameters and prevent overfitting, the evaluation of the models was not conducted using a simple train/test split. Instead, we integrated K-Fold Cross-Validation techniques, assessing the stability and generalization capabilities of the algorithms across multiple different data subsets (folds).

## 🔬 What the Notebook Includes
Inside the Jupyter Notebook, you will find a complete workflow that covers:

* **Experiments & Fine-Tuning:** * Tuning the **k** parameter (number of neighbors) to observe its effect on overfitting and underfitting.
  * Testing different distance metrics (e.g., Euclidean vs. Manhattan distance).
  * (Optional) Applying dimensionality reduction techniques (like PCA) to speed up training and inference.
* **Evaluation:** Assessing the model using metrics such as Accuracy, Precision, and Recall, along with visualizations like the Confusion Matrix.
* **Nearest Centroid Classifier:** Implementation of the Nearest Centroid Classifier for image classification and experiments/evaluation.

