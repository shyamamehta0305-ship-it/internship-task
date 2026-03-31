# CODTECH Machine Learning Internship

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)](https://python.org)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-1.x-orange)](https://scikit-learn.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-red?logo=tensorflow)](https://tensorflow.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org)

This repository contains all four tasks completed for the **CODTECH Machine Learning Internship**.

---

## 📋 Tasks Overview

| Task | Topic | Key Tools | Deliverable |
|------|-------|-----------|-------------|
| Task 1 | Decision Tree Implementation | Scikit-Learn | Notebook + Tree Visualization |
| Task 2 | Sentiment Analysis with NLP | TF-IDF, Logistic Regression | Notebook + Evaluation |
| Task 3 | Image Classification (CNN) | TensorFlow/Keras, CIFAR-10 | Trained Model + Report |
| Task 4 | Recommendation System | Collaborative Filtering, SVD | Notebook + Metrics |

---

## 🗂️ Repository Structure

```
codtech-ml-internship/
├── task1_decision_tree.ipynb           # Decision Tree on Iris dataset
├── task2_sentiment_analysis.ipynb      # NLP Sentiment Analysis
├── task3_cnn_image_classification.ipynb# CNN on CIFAR-10
├── task4_recommendation_system.ipynb   # Recommendation System
└── README.md                           # This file
```

---

## 🚀 Task Details

### Task 1 — Decision Tree Implementation
- **Dataset:** Iris (150 samples, 4 features, 3 classes)
- **Algorithm:** Decision Tree Classifier (Gini, max_depth=4)
- **Features:** EDA, tree visualization, confusion matrix, feature importance
- **Accuracy:** ~97%

### Task 2 — Sentiment Analysis with NLP
- **Dataset:** 200 synthetic customer reviews (positive / negative)
- **Pipeline:** Text preprocessing → TF-IDF Vectorization → Logistic Regression
- **Features:** Word frequency analysis, top predictive features, live prediction demo
- **Accuracy:** ~95%+

### Task 3 — Image Classification (CNN)
- **Dataset:** CIFAR-10 (60,000 images, 10 classes)
- **Architecture:** 3 × Conv blocks + BatchNorm + Dropout + Dense head
- **Features:** Data augmentation, EarlyStopping, training curves, confusion matrix
- **Expected Accuracy:** 75–80%

### Task 4 — Recommendation System
- **Dataset:** Synthetic movie ratings matrix (100 users × 50 movies)
- **Methods:** User-Based CF, Item-Based CF, SVD Matrix Factorization
- **Features:** Similarity heatmaps, RMSE/MAE evaluation, recommendation comparison
- **SVD RMSE:** ~0.85

---

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/codtech-ml-internship.git
cd codtech-ml-internship

# Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter
```

---

## ▶️ Running the Notebooks

```bash
# Start Jupyter Notebook
jupyter notebook

# Or with JupyterLab
jupyter lab
```

Open any `.ipynb` file and run all cells (`Kernel → Restart & Run All`).

---

## 📌 Notes
- All code is well-commented for readability.
- Each notebook is self-contained and runs without external datasets (except Task 3 which auto-downloads CIFAR-10).
- Completion certificate will be issued on the internship end date.

---

*Submitted as part of the CODTECH Machine Learning Internship program.*
