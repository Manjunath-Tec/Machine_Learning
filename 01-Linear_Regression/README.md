# 📈 Simple Linear Regression using Python

A beginner-friendly Machine Learning project that demonstrates how to build, train, evaluate, and visualize a **Simple Linear Regression** model using Python and Scikit-learn.

This project predicts an employee's **Salary** based on their **Years of Experience** while explaining every step with theory, code, visualizations, and evaluation metrics.

---

# 📖 Table of Contents

- Introduction
- Problem Statement
- Objectives
- Dataset
- Technologies Used
- Project Workflow
- Exploratory Data Analysis (EDA)
- Data Visualization
- Correlation Analysis
- Feature Selection
- Train-Test Split
- Model Training
- Model Prediction
- Model Evaluation
- Model Performance
- Regression Line Visualization
- Save and Load Model


---

# 📌 Introduction

Linear Regression is one of the simplest and most widely used supervised Machine Learning algorithms. It models the relationship between an independent variable and a dependent variable by fitting the best straight line through the data.

In this project, we use **Years of Experience** to predict an employee's **Salary**.

---

# 🎯 Problem Statement

Estimate an employee's salary based on their years of experience using a Simple Linear Regression model.

---

# 🎯 Objectives

- Understand the fundamentals of Linear Regression.
- Perform Exploratory Data Analysis (EDA).
- Visualize relationships between variables.
- Train a Machine Learning model.
- Make predictions on unseen data.
- Evaluate model performance using regression metrics.
- Understand Good Fit, Underfitting, and Overfitting.
- Save and reload the trained model.

---

# 📂 Dataset

**Dataset:** Salary_Data.csv

| Feature | Description |
|----------|-------------|
| YearsExperience | Employee's years of experience |
| Salary | Employee's annual salary |

Target Variable:

- Salary

Feature Variable:

- YearsExperience

---

# 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

# 🚀 Project Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Data Cleaning
5. Scatter Plot Visualization
6. Correlation Analysis
7. Correlation Heatmap
8. Feature Selection
9. Train-Test Split
10. Model Training
11. Salary Prediction
12. Model Evaluation
13. Training vs Testing Performance
14. Good Fit / Underfitting / Overfitting Analysis
15. Regression Line Visualization
16. Save and Load Model
17. Conclusion

---

# 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset Shape
- Head and Tail
- Data Types
- Statistical Summary
- Missing Value Analysis
- Duplicate Detection
- Data Cleaning
- Outlier Analysis

---

# 📈 Data Visualization

Visualizations included in this project:

- Scatter Plot
- Correlation Heatmap
- Regression Line

These visualizations help understand the relationship between experience and salary.

---

# 🤖 Model Training

Algorithm Used:

- Simple Linear Regression

Steps:

- Split the dataset into Training and Testing data.
- Train the Linear Regression model.
- Learn the relationship between Years of Experience and Salary.
- Predict salaries for unseen data.

---

# 📊 Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

The project also compares:

- Training Performance
- Testing Performance

to understand the model's generalization capability.

---

# 📉 Model Performance

The notebook explains:

- Good Fit
- Underfitting
- Overfitting
- Bias
- Variance
- Bias–Variance Trade-off

using both theory and practical examples.

---

# 💾 Save and Load Model

The trained model is saved using **Joblib**.

```python
joblib.dump(model, "linear_regression_model.pkl")
```

Later, the model can be loaded without retraining.

```python
loaded_model = joblib.load("linear_regression_model.pkl")
```

---

# 📁 Project Structure

```text
01-Linear-Regression/
│
├── Linear_Regression.ipynb
├── Salary_Data.csv
├── linear_regression_model.pkl
├── requirements.txt
└── README.md
```

---

# ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/Machine-Learning.git
```

Go to the project folder:

```bash
cd Machine-Learning/01-Linear-Regression
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Linear_Regression.ipynb
```

Run all cells.

---

# 📌 Future Improvements

- Multiple Linear Regression
- Polynomial Regression
- Regularization (Ridge & Lasso)
- Feature Engineering
- Model Deployment using Flask or FastAPI
- Interactive Web Application

---

# 🎯 Conclusion

This project demonstrates the complete implementation of **Simple Linear Regression** using Python and Scikit-learn. It covers the entire Machine Learning workflow, from data preprocessing and visualization to model training, evaluation, prediction, and model persistence.

The notebook is designed to help beginners understand both the theoretical concepts and practical implementation of Linear Regression through detailed explanations, visualizations, and real-world examples.

---

## 👨‍💻 Author

**Manjunath F Kalasanagoudra**

Computer Science & Engineering

Interested in Data Analytics, Data Science, and Machine Learning.

---

## ⭐ If you found this project helpful

Please consider giving this repository a **Star ⭐** on GitHub.