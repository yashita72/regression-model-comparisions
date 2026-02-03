📊 Regression Models Comparison with Regularization
📌 Project Overview

This project focuses on a comparative analysis of regression models to understand the impact of:

feature scaling

polynomial feature expansion

regularization techniques (L1, L2)

The goal is not just prediction, but model interpretability and performance analysis, which is crucial in real-world machine learning applications.

🎯 Objectives

Implement and compare different regression models

Study the effect of overfitting and underfitting

Analyze coefficient shrinkage and feature selection

Understand the bias–variance tradeoff

📂 Dataset

California Housing Dataset (from sklearn.datasets)

Contains multiple numerical features related to housing

Target variable: MedHouseVal

Suitable for linear, polynomial, and regularized regression

🧠 Regression Models Implemented
1️⃣ Linear Regression

Baseline model

Uses multiple features to predict housing prices

2️⃣ Polynomial Regression

Captures non-linear relationships

Higher model complexity increases risk of overfitting

3️⃣ Ridge Regression (L2 Regularization)

Penalizes large coefficients

Reduces model variance

Retains all features

4️⃣ Lasso Regression (L1 Regularization)

Shrinks some coefficients to exactly zero

Performs automatic feature selection

5️⃣ Elastic Net Regression

Combines L1 and L2 penalties

Useful when features are highly correlated

⚙️ Methodology

Data loading and preprocessing

Train–test split

Feature scaling using StandardScaler

Model training and evaluation

Hyperparameter analysis (alpha)

Visualization of coefficients and errors

📏 Evaluation Metrics

R² Score – goodness of fit

RMSE – prediction error magnitude

📊 Key Results & Observations

Polynomial regression improves fit but may overfit

Ridge regression stabilizes coefficients and improves generalization

Lasso regression removes less important features

Elastic Net balances sparsity and stability

📈 Visual Analysis

Coefficient comparison across models

Alpha (λ) vs RMSE curves for Ridge and Lasso

Clear visualization of regularization effects

🧠 Key Learnings

Regularization is essential for controlling model complexity

Feature scaling is mandatory for regularized models

Model performance alone is not enough — interpretability matters

🛠️ Technologies Used

Python

NumPy

Pandas

Matplotlib

Scikit-learn

🚀 Next Steps

Extend the project to classification models

Add Logistic and Softmax Regression

Compare binary vs multiclass classification strategies

📌 Author

Yashi
B.Tech – AI & Data Science
Aspiring Machine Learning Engineer
