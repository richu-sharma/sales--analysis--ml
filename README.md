# 📊 Sales Forecasting using Machine Learning

## 📌 Project Overview

This project focuses on predicting future sales using historical sales data.
Machine Learning regression models are applied to learn patterns from past records and forecast sales values accurately.

The project demonstrates the complete **Data Science workflow**:

**Data → Cleaning → Visualization → Model Training → Evaluation → Comparison**

---

## 🎯 Problem Statement

Businesses need accurate sales predictions to plan inventory, marketing strategies, and resource allocation.
The objective of this project is to build machine learning models that can predict sales based on historical data.

---

## 📂 Dataset Description

* File Used: `sales.xlsx`
* The dataset contains historical sales information.
* Key column:

  * `Date` – transaction date
  * Other feature columns (categorical/numerical)
  * `sales` – Target variable (value to be predicted)

---

## 🧹 Data Cleaning & Feature Engineering

Steps performed:

* Checked dataset structure using `info()` and missing values.
* Converted **Date** column into datetime format.
* Extracted:

  * Year
  * Month
  * Day
* Removed original Date column.
* Applied **One-Hot Encoding** using `pd.get_dummies()` for categorical variables.

---

## 📊 Exploratory Data Analysis (EDA)

Visualizations created:

* Sales Distribution Histogram
* Correlation Heatmap

These plots help understand:

* Sales spread and trends
* Relationships between features

Saved plots:

* `sales_distribution.png`
* `correlation_heatmap.png`

---

## 🤖 Model Training

Two regression models were used:

### 1️⃣ Linear Regression

* Simple baseline model
* Assumes linear relationship between features and sales

### 2️⃣ Random Forest Regressor

* Ensemble learning method
* Captures nonlinear relationships
* Generally provides higher accuracy

---

## 📈 Model Evaluation Metrics

Models were evaluated using:

* **R² Score** → Model accuracy
* **MAE (Mean Absolute Error)** → Average prediction error
* **MSE (Mean Squared Error)** → Penalizes large errors

---

## 🔍 Model Comparison

| Model             | Description                         |
| ----------------- | ----------------------------------- |
| Linear Regression | Fast but limited to linear patterns |
| Random Forest     | Better performance for complex data |

✅ Random Forest achieved better prediction performance.

---

## ✅ Conclusion

The project successfully predicted sales using machine learning techniques.
Random Forest outperformed Linear Regression because sales data contains nonlinear patterns.

---

## 🚀 Future Improvements

* Use larger historical datasets
* Add seasonal & promotional features
* Apply advanced models (XGBoost, Gradient Boosting)
* Hyperparameter tuning
* Deploy model as a dashboard or web application

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📁 Project Structure

```
Sales-Forecasting/
│
├── sales.xlsx
├── sales_forecasting.ipynb
├── sales_distribution.png
├── correlation_heatmap.png
└── README.md
```

---

## 👩‍💻 Author

**Richa Bhardwaj**
B.Tech Computer Science Engineering
Interested in Data Science & Machine Learning

---

⭐ If you like this project, feel free to give it a star!
