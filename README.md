# Machine Learning – Logistic Regression

## 📌 Project Overview
This project focuses on implementing Univariate and Multivariate Logistic Regression using Python and the Titanic dataset. The objective is to predict passenger survival based on individual and multiple features. It covers data preprocessing, model training, prediction, accuracy evaluation, coefficient analysis, and confusion matrix visualization.

## 🎯 Project Objectives
- Understand the fundamentals of Logistic Regression.
- Perform data cleaning and preprocessing.
- Implement Univariate Logistic Regression using a single feature.
- Implement Multivariate Logistic Regression using multiple features.
- Encode categorical variables into numerical values.
- Split data into training and testing sets.
- Train and evaluate classification models.
- Analyze model coefficients and intercepts.
- Compare model accuracy using confusion matrices.

## 📂 Dataset Information

**Dataset:** Titanic Dataset  
**Source:** Seaborn Built-in Dataset

- Total Features: 15 columns (original dataset).
- Target Variable: `survived`
- Target Values:
  - `0` – Not Survived
  - `1` – Survived

### Selected Features

| Feature | Description |
|---|---|
| fare | Passenger ticket fare |
| pclass | Passenger ticket class |
| age | Passenger age |
| sibsp | Number of siblings/spouses aboard |
| sex | Passenger gender |

## 🛠️ Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## ⚙️ Project Workflow

### 1. Data Loading and Exploration
- Imported required Python libraries.
- Loaded the Titanic dataset using Seaborn.
- Checked dataset shape, data types, and missing values.

### 2. Data Cleaning and Preprocessing
- Handled missing values using the `dropna()` method.
- Identified the target variable (`survived`).
- Encoded the categorical `sex` column into numerical values.

### 3. Univariate Logistic Regression
- Selected `fare` as the single independent variable.
- Defined `survived` as the target variable.
- Split the dataset into 80% training and 20% testing data.
- Trained the Logistic Regression model.
- Generated survival predictions.
- Evaluated accuracy, coefficients, and intercept.
- Visualized results using a confusion matrix.

### 4. Multivariate Logistic Regression
- Selected five independent features:
  - pclass
  - age
  - fare
  - sibsp
  - sex_encoded
- Applied StandardScaler for feature scaling.
- Split data into training and testing sets.
- Trained the Multivariate Logistic Regression model.
- Generated predictions and evaluated accuracy.
- Analyzed feature coefficients and intercept.
- Visualized classification performance using a confusion matrix.

## 📊 Model Evaluation

The project evaluates both models using:

| Evaluation Metric | Purpose |
|---|---|
| Accuracy Score | Measures correct predictions |
| Confusion Matrix | Evaluates classification results |
| Coefficients | Shows feature influence |
| Intercept | Represents the model's baseline term |

## 📈 Visualizations
The notebook includes:
- Univariate Logistic Regression Confusion Matrix.
- Multivariate Logistic Regression Confusion Matrix.

## 🔍 Model Comparison

| Model | Independent Variables |
|---|---|
| Univariate Logistic Regression | fare |
| Multivariate Logistic Regression | pclass, age, fare, sibsp, sex_encoded |

Both models are compared based on their accuracy scores to understand how using multiple independent variables affects survival prediction.

## 🧠 Key Learning Outcomes
- Understanding binary classification using Logistic Regression.
- Learning the difference between Univariate and Multivariate models.
- Handling missing values and categorical variables.
- Applying feature scaling using StandardScaler.
- Understanding model coefficients and intercepts.
- Evaluating classification models using accuracy and confusion matrices.

### DATA:
<img width="1473" height="734" alt="Screenshot 2026-11-16 175516" src="https://github.com/user-attachments/assets/a1085a79-8697-4d8c-a307-66ec1fdfae31" />

---
### DATA:
<img width="1367" height="683" alt="Screenshot 2026-11-16 175536" src="https://github.com/user-attachments/assets/16080ebe-2b13-4b48-8438-516c6a8e4f68" />

---
### DATA:
<img width="1458" height="717" alt="Screenshot 2026-11-16 175550" src="https://github.com/user-attachments/assets/62864eba-bc62-44d8-ab83-b43a3ce24ce4" />

---
### DATA:
<img width="1310" height="643" alt="Screenshot 2026-11-16 175611" src="https://github.com/user-attachments/assets/c73d6cc6-bbfe-413f-85b8-e0f8f8e69570" />

---
### DATA:
<img width="1198" height="628" alt="Screenshot 2026-11-16 175622" src="https://github.com/user-attachments/assets/db0f0bdc-2e4d-4fae-8564-630f377b1299" />

---
