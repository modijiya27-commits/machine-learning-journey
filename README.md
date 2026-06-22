## Machine Learning Algorithms

* [ ] Decision Trees
* [ ] Random Forest
* [x] K-Nearest Neighbors (KNN)
* [ ] Support Vector Machines (SVM)
* [ ] Naive Bayes
* [ ] K-Means Clustering

---

## Advanced Concepts

* [x] Feature Engineering
* [x] Feature Scaling
* [ ] Cross Validation
* [x] Hyperparameter Tuning
* [ ] Overfitting
* [ ] Underfitting
* [ ] Bias vs Variance

---

## Day 39

### K-Nearest Neighbors (KNN)

#### Dataset

Titanic Dataset

#### Concepts Applied

* Distance-Based Learning
* Euclidean Distance
* KNN Classification
* Feature Scaling using StandardScaler
* Model Evaluation
* Hyperparameter Tuning

#### Model Development

* Applied StandardScaler to numerical features
* Trained KNN Classifier
* Generated survival predictions
* Evaluated model using Accuracy, Confusion Matrix, and Classification Report
* Tested K values from 1 to 20
* Identified the optimal K value based on model accuracy

#### Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 77.09%   |
| KNN                 | 79.89%   |

#### Hyperparameter Tuning Results

* Tested K values from 1 to 20
* Best K Value = 18
* Highest Accuracy Achieved = 82.12%

#### Classification Report

| Class       | Precision | Recall | F1-Score |
| ----------- | --------- | ------ | -------- |
| No Survival | 0.80      | 0.88   | 0.84     |
| Survival    | 0.80      | 0.69   | 0.74     |

#### Key Insights

* KNN outperformed Logistic Regression on the Titanic dataset.
* Feature scaling significantly improved KNN performance.
* Passenger survival patterns were effectively captured using neighborhood-based classification.
* Selecting an appropriate K value improved model accuracy and reduced prediction variance.
* Hyperparameter tuning demonstrated the importance of model optimization.
