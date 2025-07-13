
# 💼 Decision Tree Salary Prediction

This project implements a **Decision Tree Regression** model to predict employee salaries based on their position level, years at the company, and performance score. It uses a dataset with missing values and applies preprocessing steps like imputation before training the model.

---

## 📂 Dataset

A realistic employee dataset with the following columns:

- `Position` : Job title (e.g., Intern, CEO)
- `Level` : Numerical level representing role seniority
- `Years_at_Company` : Time spent at the company (some values are missing)
- `Performance_Score` : Annual performance rating out of 5 (some values are missing)
- `Salary` : Target variable (annual compensation, includes NaNs)

> 🧩 Some rows contain missing data and are preprocessed using `SimpleImputer`.

---

## ⚙️ Features

- 🧼 **Imputation of Missing Values** using mean strategy
- 📊 **Feature Extraction** from numerical and categorical columns
- 🌳 **Decision Tree Regression** to model salary trends across levels
- 📈 **Prediction** of salary for unseen levels or incomplete records
- 🖼️ **Graphical visualization** of the Decision Tree results

---

## 🧪 Results

<img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/e5b6ca6e-942c-45e4-8506-a8aa3100764a" />


📉 Model output for level = `6.5`:
```python
Predicted Salary = 150000.0

