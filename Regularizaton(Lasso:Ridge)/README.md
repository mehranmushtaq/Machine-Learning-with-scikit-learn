## Insurance Cost Prediction using Lasso and Ridge Regression

This project demonstrates regularized regression modeling using scikit-learn pipelines to predict medical insurance charges.
It compares Lasso (L1 regularization) and Ridge (L2 regularization) using GridSearchCV hyperparameter tuning.

The notebook includes well-commented code explaining each step of the machine learning workflow, from preprocessing to model evaluation.

⸻

## Project Objective

Predict insurance charges using demographic and health-related features while comparing the performance of Lasso and Ridge regression models.

⸻

## Dataset

The dataset contains insurance beneficiary information with the following features:
	•	age
	•	sex
	•	bmi
	•	children
	•	smoker
	•	region

## Target variable:

charges

## Machine Learning Workflow

The notebook follows a structured ML pipeline:
	1.	Data loading and preprocessing
	2.	Encoding categorical variables
	3.	Train-test split
	4.	Feature scaling using StandardScaler
	5.	Lasso regression with GridSearchCV
	6.	Ridge regression with GridSearchCV
	7.	Model evaluation using regression metrics
	8.	Visualization of results

Both models use a pipeline:

## StandardScaler → Regression Model
This prevents data leakage and ensures reproducibility.

Results

Lasso Regression

Best alpha:100

Metric        Value
R² Score      :0.7690
MSE           :33,867,535.59
RMSE          :5,819.58
