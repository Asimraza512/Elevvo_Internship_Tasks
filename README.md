📊 Student Performance Prediction

This project is part of my internship task, where I built regression models to predict students’ exam scores based on their study hours. The dataset comes from Kaggle - Student Performance Factors
.

🚀 Project Overview

The goal is to:

Perform data cleaning (handle missing values).

Build a Linear Regression model to estimate exam scores.

Build a Polynomial Regression (degree=2) model for comparison.

Evaluate both models using R² Score and Root Mean Squared Error (RMSE).

Visualize actual vs predicted exam scores.

🛠️ Tools & Libraries

Python

Pandas → data handling

NumPy → numerical operations

Matplotlib → visualization

Scikit-learn → regression models & evaluation metrics

📂 Dataset

Name: Student Performance Factors

Source: Kaggle

Important Features used:

StudyHours → Independent variable (X)

ExamScore → Dependent variable (y)

📌 Steps

Load dataset with Pandas.

Handle missing values using median imputation.

Select features (StudyHours) and target (ExamScore).

Split dataset into training (80%) and testing (20%).

Train models:

Linear Regression

Polynomial Regression (degree=2)

Evaluate both models with:

R² Score

RMSE

Visualize results with Matplotlib.

📊 Results

Both Linear and Polynomial models give predictions close to the actual values.

Comparison is based on R² and RMSE:

Higher R² → better fit

Lower RMSE → better accuracy

📸 Visualization

The plot shows actual exam scores vs. predictions from both models:

🔵 Blue → Actual values

🔴 Red → Linear Regression predictions

🟢 Green → Polynomial Regression predictions

📝 Conclusion

Linear regression provides a simple baseline model.

Polynomial regression can sometimes capture non-linear trends better.

Final evaluation depends on metrics (R² & RMSE) for your dataset.
