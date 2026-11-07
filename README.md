# 📊 Predictive Classification with Logistic Regression (`Logistic_Final.ipynb`)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Scikit--Learn-Logistic%20Regression-orange.svg)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/Status-Complete-success.svg)]()

> A structured machine learning classification pipeline built using **Logistic Regression** to model binary outcomes, emphasizing feature interpretation, performance optimization, and robust evaluation metrics.

---

## 🎯 Executive Summary
* **Project Overview:** This project utilizes a logistic regression model to predict happy customers for an e-commerce company. The model suggests that products arriving on-time and satisfaction with the currier have a positive impact on customer happiness. The price of the item did not have a significant impact on the model
* **Core Technical Competency:** End-to-end classification pipeline implementation using Python, Pandas, Scikit-Learn, and Statsmodels.
* **Statistical Rigor & Interpretability:** Leveraged coefficient analysis and odds ratios to extract actionable business insights from feature weights.
* **Model Evaluation Strategy:** Went beyond basic accuracy by evaluating models using **Precision, Recall, and F1-Score** to handle classification trade-offs effectively.

---

## 🔄 Project Workflow & Step-by-Step Flow

Here is the structured data science workflow followed within `Logistic_Final.ipynb`:

### Step 1: Exploratory Data Analysis & Data Cleaning
* **Data Hygiene:** examined missing values and outliers, as well as the shape and structure of the data.
* **Distribution & Correlation:** Analyzed feature distributions and multi-collinearity (using Correlation Matrices / VIF) to ensure model stability.

### Step 2: Data Preprocessing & Feature Engineering
The data set was small, clean, and already encoded into numerical data.

### Step 3: Model Training & Optimization
* **Baseline Logistic Regression:** Trained an initial logistic regression model using Scikit-Learn.
* **Regularization Tuning:** Experimented with L1 (Lasso) and L2 (Ridge) regularization to prevent overfitting and perform feature selection.

### Step 4: Model Evaluation & Performance Metrics
* **Confusion Matrix:** Analyzed Type I and Type II errors.

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python
* **Machine Learning & Stats:** Scikit-Learn, Statsmodels
* **Data Processing & Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---

## 💡 Key Technical Insights & Interpretability

* **Feature Coefficients:** Logictic Regression was chosen in part due to the size of the dataset, but it also allows for direct interpretation of feature importance via coefficients and odds ratios—identifying exactly which factors drive the target prediction.
* **Model Simplicity vs. Performance:** Demonstrates how a well-tuned linear classifier can achieve strong predictive performance while maintaining full transparency for stakeholders.

---


## 🏁 Concluding Remarks & Future Scope

### What This Project Demonstrates
This project showcases an ability to implement a rigorous statistical machine learning pipeline, tune regularization parameters, interpret feature coefficients accurately, and evaluate classification models using industry-standard metrics.

---
*Feel free to reach out if you'd like to discuss the modeling choices, feature engineering, or statistical findings in greater detail!*
