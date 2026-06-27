# 🤖 Machine Learning Journey

Welcome to my Machine Learning learning repository.

This repository documents my journey of learning Machine Learning from scratch through hands-on implementation, notebooks, experiments, visualizations, and projects as part of my **#50DaysOfNotADataScientistYet** challenge.

The goal is not just to use machine learning libraries, but to understand the intuition, mathematics, preprocessing techniques, model evaluation, optimization, and interpretation behind every algorithm.

---

# 🎯 Objectives

* Build strong Machine Learning fundamentals
* Understand the intuition behind ML algorithms
* Learn data preprocessing and feature engineering
* Master model evaluation and validation techniques
* Apply concepts on real-world datasets
* Build an industry-ready Machine Learning portfolio

---

# 📚 Topics Covered

## Machine Learning Foundations

* [x] Introduction to Machine Learning
* [x] Supervised vs Unsupervised Learning
* [x] Features vs Target Variables
* [x] Train-Test Split
* [x] Linear Regression
* [x] Logistic Regression
* [x] Feature Engineering
* [x] Feature Scaling
* [x] Normalization
* [x] Standardization
* [x] Missing Value Imputation
* [x] Label Encoding
* [x] One-Hot Encoding

---

## Machine Learning Algorithms

* [x] Linear Regression
* [x] Logistic Regression
* [x] K-Nearest Neighbors (KNN)
* [x] Naive Bayes
* [x] Decision Trees
* [ ] Random Forest
* [ ] Support Vector Machines (SVM)
* [ ] K-Means Clustering

---

## Model Evaluation & Optimization

* [x] Accuracy
* [x] Precision
* [x] Recall
* [x] F1 Score
* [x] Confusion Matrix
* [x] Model Comparison
* [x] Hyperparameter Tuning
* [x] Cross Validation
* [x] K-Fold Cross Validation
* [x] Stratified K-Fold
* [x] Leave-One-Out Cross Validation (LOOCV)
* [x] Time Series Cross Validation
* [x] Bias vs Variance
* [x] Underfitting
* [x] Overfitting

---

# 📊 Statistical Concepts Applied

* Descriptive Statistics
* Probability
* Correlation Analysis
* Data Distributions
* Bias–Variance Tradeoff
* Feature Scaling

---

# 📂 Projects

* [x] Student Performance Prediction
* [x] Titanic Survival Prediction
* [ ] Google Play Store Machine Learning
* [ ] Customer Segmentation (K-Means)
* [ ] End-to-End Machine Learning Project

---

# 🛠 Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

# 📁 Repository Structure

```text
00_ML_Foundations/
01_Linear_Regression/
02_Model_Evaluation/
03_Feature_Engineering/
04_Feature_Scaling/
05_Logistic_Regression/
06_Model_Comparison/
07_Cross_Validation/
08_Decision_Trees/
09_Random_Forest/
10_SVM/
11_KMeans/
12_Projects/
```

---

# 📘 Repository Contents

| Notebook                            | Description                                                                            |
| ----------------------------------- | -------------------------------------------------------------------------------------- |
| Linear_Regression_Basics.ipynb      | Linear Regression implementation and evaluation                                        |
| Logistic_Regression.ipynb           | Binary classification using Logistic Regression                                        |
| KNN_Classification.ipynb            | K-Nearest Neighbors algorithm and hyperparameter tuning                                |
| Naive_Bayes.ipynb                   | Naive Bayes classification                                                             |
| Model_Evaluation.ipynb              | Accuracy, Precision, Recall, F1 Score & Confusion Matrix                               |
| Cross_Validation.ipynb              | K-Fold, Stratified K-Fold, LOOCV & Time Series Cross Validation                        |
| Decision_Trees_Classification.ipynb | Decision Tree implementation, visualization, feature importance & overfitting analysis |

---

# 📖 Learning Log

## ✅ Day 40 — Machine Learning Model Comparison

### Dataset

Titanic Dataset

### Concepts Applied

* Logistic Regression
* Naive Bayes
* K-Nearest Neighbors
* Decision Tree
* Hyperparameter Tuning
* Feature Scaling
* Model Comparison
* Confusion Matrix
* Precision, Recall & F1 Score

### Best Model

🏆 **K-Nearest Neighbors (KNN)**

* Best K = 18
* Accuracy = **82.12%**

### Key Learning

Comparing multiple models provides a better understanding of their strengths and weaknesses than relying on a single algorithm.

---

## ✅ Day 41 — Missing Value Handling

### Concepts Learned

* Missing Value Analysis
* Mean, Median & Mode Imputation
* SimpleImputer
* Data Leakage
* Feature vs Target Missing Values

### Key Learning

The choice of imputation strategy depends on the feature type and the machine learning problem. Missing target values should generally not be imputed.

---

## ✅ Day 42 — Bias, Variance & Clustering Fundamentals

### Concepts Learned

* Bias vs Variance
* Underfitting
* Overfitting
* K-Means Clustering
* WCSS
* Elbow Method

### Key Learning

High training accuracy alone is not a good indicator of model quality. A good model generalizes well to unseen data.

---

## ✅ Day 43 — Cross Validation

### Concepts Learned

* Cross Validation
* K-Fold Cross Validation
* Stratified K-Fold
* Leave-One-Out Cross Validation (LOOCV)
* Time Series Cross Validation

### Key Learning

Cross validation provides a more reliable estimate of model performance than a single train-test split.

---

## ✅ Day 44 — Decision Trees

### Dataset

Titanic Dataset

### Concepts Learned

* Decision Tree Classification
* Gini Impurity
* Entropy
* Information Gain
* Tree Visualization
* Feature Importance
* Decision Tree Depth
* Underfitting vs Overfitting

### Implemented

* Missing Value Handling
* Label Encoding
* Decision Tree Classifier
* Classification Report
* Confusion Matrix
* Feature Importance Analysis
* Decision Tree Visualization
* Accuracy vs Tree Depth Analysis

### Model Performance

* Test Accuracy: **79.33%**
* Best Tree Depth: **9**
* Best Test Accuracy: **81%**

### Key Insights

* Sex was the most influential feature in predicting survival.
* Fare and Age were also strong predictors.
* Increasing tree depth consistently improved training accuracy.
* Testing accuracy peaked around depth **9**, after which it declined due to overfitting.

### Key Learning

Decision Trees are highly interpretable but prone to overfitting. Limiting tree depth helps improve generalization while maintaining good predictive performance.

---

# 🚀 Upcoming Topics

* Random Forest
* Support Vector Machines (SVM)
* K-Means Clustering Implementation
* Ensemble Learning
* Principal Component Analysis (PCA)
* Pipeline & GridSearchCV
* End-to-End Machine Learning Project
* Model Deployment

---

# 🌱 Learning in Public

This repository is part of my **#50DaysOfNotADataScientistYet** challenge, where I share my daily progress, implementations, projects, visualizations, and key learnings while building a strong foundation in Machine Learning.

If you're learning Machine Learning too, feel free to explore the notebooks, suggest improvements, or learn along!
