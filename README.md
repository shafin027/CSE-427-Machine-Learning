# 🧠 CSE427: Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![Sklearn](https://img.shields.io/badge/Library-Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> **Welcome!** This repository contains the laboratory works for the CSE427 Machine Learning course. It covers the implementation of fundamental ML algorithms—both from scratch and using `scikit-learn`—ranging from data preprocessing to Neural Networks.

---

## 📑 Table of Contents

* [🛠️ Tech Stack](#-tech-stack)
* [📂 Lab Summaries](#-lab-summaries)
    * [Lab 1: Introduction & NumPy](#lab-1-introduction--numpy)
    * [Lab 2: Decision Trees & Random Forest](#lab-2-decision-trees--random-forest)
    * [Lab 3: Boosting (AdaBoost)](#lab-3-boosting-adaboost)
    * [Lab 4: Logistic Regression](#lab-4-logistic-regression)
    * [Lab 5: K-Nearest Neighbors (KNN)](#lab-5-k-nearest-neighbors-knn)
    * [Lab 6: Neural Networks (MLP)](#lab-6-neural-networks-mlp)
* [📊 Datasets Used](#-datasets-used)
* [🚀 Getting Started](#-getting-started)

---

## 🛠️ Tech Stack

The following libraries were utilized throughout the course:

| Library | Usage |
| :--- | :--- |
| **NumPy** | Matrix operations, linear algebra, and math functions. |
| **Pandas** | Data manipulation, ingestion, and preprocessing. |
| **Matplotlib** | Data visualization and plotting training curves. |
| **Scikit-Learn**| Standard ML models, metrics, and dataset splitting. |

---

## 📂 Lab Summaries

### Lab 1: Introduction & NumPy
**Focus:** Linear Algebra basics and Python environment setup.
* **Concepts:**
    * Introduction to Python for Machine Learning.
    * Array creation, reshaping, and indexing.
    * Matrix multiplication (Scalar and Dot product).
    * Handling random number generation.
* **Key Code:**
    ```python
    import numpy as np
    a = np.random.randint(1, 100, 20)
    matrix_A = a.reshape(5, 4)
    ```

### Lab 2: Decision Trees & Random Forest
**Focus:** Supervised Learning and Exploratory Data Analysis (EDA).
* **Concepts:**
    * **EDA:** Handling missing values, encoding categorical variables (Titanic Dataset).
    * **Decision Tree:** Building a tree classifier, understanding gini impurity/entropy.
    * **Random Forest:** Implementing an ensemble of trees to reduce overfitting.
    * **Metrics:** Calculating Accuracy Scores.
* **Files:** `23101109_Shafin Mahamud_CSE427Lab2.ipynb`

### Lab 3: Boosting (AdaBoost)
**Focus:** Ensemble Learning using Boosting techniques.
* **Concepts:**
    * Understanding Weak Learners (Stumps).
    * Implementing **AdaBoost** from scratch.
    * Handling weights and errors iteratively.
    * Comparing custom implementation vs. `sklearn` implementation.
* **Dataset:** Australian Rainy Weather Prediction.
* **Files:** `23101109_SHAFIN_MAHAMUD_CSE427Lab3.ipynb`, `Lab_3_AdaBoost_Classification.ipynb`

### Lab 4: Logistic Regression
**Focus:** Binary Classification and Probabilistic modeling.
* **Concepts:**
    * The Sigmoid Activation Function.
    * Cost Function (Log Loss).
    * Gradient Descent optimization.
    * Predicting probabilities vs. hard class labels.
* **Files:** `[Student_View]_Logistic_Regression.ipynb`

### Lab 5: K-Nearest Neighbors (KNN)
**Focus:** Instance-based Learning.
* **Concepts:**
    * Implementing KNN from scratch using Euclidean Distance.
    * Determining the optimal value of `K`.
    * Majority voting mechanism.
    * Comparison with `KNeighborsClassifier` from sklearn.
* **Dataset:** Iris Dataset.
* **Files:** `23101109_ShafinMahamud_CSE427Lab5.ipynb`

### Lab 6: Neural Networks (MLP)
**Focus:** Deep Learning foundations.
* **Concepts:**
    * Solving the **XOR Problem** (Non-linear separability).
    * Architecture: Input Layer $\rightarrow$ Hidden Layer $\rightarrow$ Output Layer.
    * **Forward Propagation:** Calculation of neuron activations.
    * **Backpropagation:** Updating weights based on error gradients.
    * Training loop with Epochs and Learning Rate.
* **Files:** `23101109_ShafinMahamud_CSE427Lab6.ipynb`

---

## 📊 Datasets Used

| Lab | Dataset Name | Description | Target Variable |
| :--- | :--- | :--- | :--- |
| **Lab 2** | Titanic | Passenger survival data | `Survived` (0/1) |
| **Lab 3** | Australian Weather | Rainfall weather prediction | `RainTomorrow` |
| **Lab 5** | Iris | Flower species classification | `Species` |
| **Lab 6** | XOR (Synthetic) | Logic gate simulation | Binary Output |

---

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/CSE427-Machine-Learning.git](https://github.com/your-username/CSE427-Machine-Learning.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install numpy pandas matplotlib scikit-learn
    ```
3.  **Run Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

---

<div align="center">

**CSE427 Machine Learning** | Created by Shafin Mahamud

</div>
