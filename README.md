# 🛒 Retail Dataset — Exploratory Data Analysis (Project 3)

## 📌 Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) 
on a large-scale retail dataset containing 100,000 transactions across 
18 features. The analysis uncovers actionable business insights around 
customer behaviour, pricing strategy, product performance, and 
operational efficiency.

---

## 📂 Dataset Summary
| Property         | Details                        |
|-----------------|-------------------------------|
| Rows             | 1,00,000 transactions          |
| Features         | 18 columns                     |
| Numerical        | age, product_price, quantity, discount_percentage, delivery_days, final_price |
| Categorical      | product_category, customer_segment, payment_method, shipping_type, return_status |
| Target Variable  | final_price                    |
| Missing Values   | None (clean dataset)           |

---

## 🔍 Analysis Covered

### ✅ A. Univariate Analysis
- Descriptive statistics (mean, std, min, max)
- Skewness & Kurtosis for all numerical features
- Distribution plots with KDE curves

### ✅ B. Categorical Analysis
- Product category & customer segment distribution
- Payment method preferences
- Return status breakdown

### ✅ C. Outlier Detection
- IQR Method (Interquartile Range)
- Z-Score Method (±3σ threshold)
- Identified 503 high-value transactions in final_price

### ✅ D. Bivariate Analysis
- Correlation matrix (Pearson)
- Product Price vs Final Price (r = 0.77 — strong positive)
- Customer Segment vs Average Spending
- Return Rate by Product Category
- Shipping Type vs Delivery Days

### ✅ E. Multivariate Analysis
- Final Price by Category × Customer Segment
- Age Group × Segment × Spending Behaviour

---

## 💡 Key Insights
- 📈 **product_price** and **quantity** are the two strongest revenue drivers
- 🏆 **Home & Kitchen** generates the highest average revenue per transaction
- 👥 **Premium customers** spend ~20% more than New customers
- 🚚 **Economy shipping** correlates with higher return likelihood
- 💳 **Credit Card** is the most preferred payment method (28.5%)
- 🎯 **Premium customers aged 36–45** represent the highest-value segment

---

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-teal)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Plots-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red)

---

## 📁 Repository Structure
```
Retail-EDA-Project3-NHIS/
│
├── 📓 Vamsi_EDA_NHIS_Project_3.ipynb
├── 📊 retail_large_dataset.csv
├── 📑 Vamsi_EDA_NHIS_Project_3.pptx
├── 📄 NHIS_Project_3.pdf
├── 📄 Vamsi_EDA_NHIS_Project3_DiscussionGuide.pdf
└── 📄 README.md
```

---

## 👨‍💻 Author
**Vamsi Krishna**  
NHIS Project Internship Programme — 2026
