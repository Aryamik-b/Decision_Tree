# Decision Trees: Fundamentals to Practical Classification

A collection of Decision Tree implementations, experiments, pruning techniques, and a practical e-commerce classification project using Python and Scikit-learn.

## 📂 Contents

- Decision Tree Classification
- Pre-Pruning
- Post-Pruning
- Model Evaluation
- Hyperparameter Tuning
- ShopSmart E-Commerce Classification Project

## ✂️ Pruning Techniques

### Pre-Pruning
Pre-pruning limits the growth of the tree during training using parameters such as:

- `max_depth`
- `min_samples_leaf`
- `min_samples_split`
- `class_weight`

### Post-Pruning
Post-pruning reduces unnecessary branches after training and helps control overfitting. The project also uses `GridSearchCV` to find suitable tree parameters.

## 🛒 ShopSmart E-Commerce Project

ShopSmart is a mini machine learning project that uses a Decision Tree Classifier to predict the `Revenue` outcome from e-commerce customer/session data.

### Techniques Used

- Train-Test Split
- Stratified Sampling
- Numerical Feature Scaling
- Categorical Feature Encoding
- `ColumnTransformer`
- `Pipeline`
- Decision Tree Classification
- Class Weight Balancing
- Pre-Pruning
- Grid Search Cross-Validation
- F1 Score
- Classification Report
- Confusion Matrix

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## 🎯 Objective

The goal of this repository is to understand Decision Trees from fundamentals to practical implementation, including how preprocessing, pruning, class imbalance, and hyperparameter tuning can improve model performance.

## 👨‍💻 Author

Aryamik Bal