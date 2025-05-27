# AIML-TASK-2-EDA-
# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 🎯 Objective
This project is part of the **AI & ML Internship Task 2**. The goal is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python and libraries like Pandas, Matplotlib, Seaborn, and Plotly. The aim is to understand data characteristics and uncover patterns that influence survival.

---

## 📁 Dataset
- **Source:** [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
---

## 🔧 Tools & Libraries
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Plotly (optional, for interactive plots)
- Jupyter Notebook or any IDE of choice

---

## 📊 Steps Performed

### 1. Data Loading and Inspection
- Loaded the Titanic dataset using `pandas.read_csv()`
- Displayed basic dataset information using `.head()`, `.info()`, `.describe()`, and `.isnull().sum()`

### 2. Data Cleaning
- Identified missing values in features such as `Age`, `Cabin`, and `Embarked`

### 3. Summary Statistics
- Displayed measures like **mean, median, std**
- Calculated **skewness** using `df.skew()`

### 4. Visualizations

#### 🔹 Univariate Analysis
- **Histograms** for `Age`, `Fare`, and other numerical columns
- **Boxplots** for visualizing distributions and outliers

#### 🔹 Bivariate/Multivariate Analysis
- **Correlation Matrix** using `.corr()` and `sns.heatmap()`
- **Pairplot** for multivariate relationships
- **Count Plots** to analyze survival by class and gender

#### 🔹 Interactive (Optional)
- **Plotly scatter plot**: Age vs Fare colored by survival

---

## 📈 Key Findings
- Passengers in **1st class** had higher survival rates.
- **Females** had significantly higher survival rates than males.
- **Fare** is right-skewed; most passengers paid lower ticket prices.
- Missing data is mostly in `Cabin`, which can be dropped or imputed.
- Some outliers in `Fare` and `Age` need attention before modeling.

---

## 🧠 Interview Preparation Questions Covered
- What is the purpose of EDA?
- How do boxplots help in understanding data?
- What is correlation and why is it useful?
- How do you detect skewness in data?
- What is multicollinearity?
- What tools did you use for EDA?
- Did EDA help uncover any issues in the data?
- What is the role of visualization in machine learning?

---

## 📌 Submission Instructions
This GitHub repository contains:
- Python code (`.ipynb`)
- Dataset reference
- This `README.md` file
---

## ✅ Conclusion
EDA is a vital step in the machine learning pipeline. It helps in:
- Understanding the dataset deeply
- Identifying patterns, trends, and anomalies
- Making decisions for data preprocessing and feature engineering

This Titanic dataset EDA builds a strong foundation for future tasks like feature selection and model building.

---
**Submitted by:MUMMADI RAMCHARAN  

