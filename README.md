# 📈 Multiple Linear Regression - Marketing Sales Predictor

This project was developed as part of the **3MTT AI/ML Track (Mini Project 1)** by **Abdulrahman Adisa Amuda**. It explores how various marketing channels — such as TV, social media, radio, and influencers — affect **product sales**, using a **Multiple Linear Regression model**.

> 🚀 Goal: Use regression to help businesses **optimize their marketing budget** by identifying the most impactful promotional strategies.

---

## 🧠 Project Overview

- 📊 **Model Type**: Multiple Linear Regression (using `statsmodels`)
- 💼 **Use Case**: Predicting product sales based on promotional spend
- 📁 **Dataset**: `marketing_sales_data.csv` (TV, Social Media, Radio, Influencer, Sales)
- ⚙️ **Tools Used**: Python, pandas, seaborn, matplotlib, statsmodels

---

## 🔧 Project Steps

### ✅ Step 1: Problem Definition
Understand the real-world value of predicting sales to optimize marketing spend and ROI.

### 📥 Step 2: Data Collection
Loaded and inspected `marketing_sales_data.csv` to understand structure and variables.

### 📊 Step 3: Exploratory Data Analysis (EDA)
Used:
- `pairplot()` to examine relationships between features
- Detected trends and potential correlations visually

### 🧹 Step 4: Data Preparation
- Dropped missing values (`dropna()`)
- One-hot encoded categorical features like `Influencer`
- Ensured the dataset was clean for regression

### 🔢 Step 5: Model Building
- Built OLS (Ordinary Least Squares) model using `statsmodels`
- Regression formula: `Sales ~ TV + Social_Media + Radio + Influencer_*`

### 📏 Step 6: Model Evaluation
- Scatterplot of **Predicted vs Actual** sales
- Q-Q plot of residuals to check **normality**
- Verified linearity and assumptions for valid regression

### 📈 Step 7: Results & Insights
- ✅ Interpreted coefficients and p-values
- ✅ Explained impact of each variable
- ✅ Highlighted most significant channels
- ✅ Shared insights on optimizing marketing strategy

---

## 📌 Key Takeaways

- Regression assumptions must be checked before trusting predictions
- Coefficients reveal **how much each channel contributes to sales**
- R-squared shows how well your model explains sales variability
- Stakeholders can use insights to **reallocate marketing budgets wisely**

---

## 💡 Recommendations to Stakeholders

- 📺 Increase TV spend if it's shown to have the highest coefficient
- 📻 Reduce spend on non-impactful channels
- 📉 Consider alternative strategies for influencer campaigns if impact is low
- 📊 Use this model as a **forecasting tool** for campaign planning

---

## 📁 Files Included

- `Abdulrahman_Adisa_Amuda_Module_1_Mini_Project.ipynb` — Main Jupyter Notebook with full pipeline
- All steps: EDA, data cleaning, modeling, evaluation, interpretation

---

## 📎 Submission Info

- 👨‍🎓 **3MTT Mini Project 1**
- 🧠 **Track**: AI/ML
- 🗂️ **Format**: Jupyter Notebook (`.ipynb`)
- ✅ Submitted via GitHub & Google Drive

---

## 🧑‍💻 Author

**Abdulrahman Adisa Amuda**  
IBM AI & ML Certified | 3MTT Fellow  
[GitHub Profile](https://github.com/adisar6402)
