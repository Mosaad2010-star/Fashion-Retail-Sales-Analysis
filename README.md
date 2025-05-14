# 🛍️ Comprehensive Data Analysis and Customer Segmentation on Fashion Retail Sales Data

## 🎯 Objective

The primary objective of this project is to perform a **comprehensive analysis** on fashion retail sales data to gain actionable insights, **predict purchasing behavior**, and **identify customer segments** based on purchase characteristics.

---

## 🛠️ Tools & Technologies Used

- Python: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`
- Scikit-learn: Regression & Clustering models
- Jupyter Notebook / IDE
- Streamlit (for interactive app)

---

## 📁 Project Structure


---

## 📊 1. Data Overview & Preparation

- The dataset contains **2,487 records** with the following key fields:
  - `Customer ID`, `Item Purchased`, `Purchase Amount (USD)`, `Date of Purchase`, `Review Rating`, `Payment Method`
- Performed:
  - Column renaming and cleaning
  - Converted `Date_Purchase` to `datetime` format
  - Null values check: No significant issues found

---

## 🔍 2. Exploratory Data Analysis (EDA)

- Analyzed distribution of `Purchase Amount (USD)` to detect skewness & outliers
- Visualized relationship between:
  - Review Ratings vs. Purchase Amounts (Scatter plots)
  - Payment Methods vs. Sales (Boxplots)
- Used correlation heatmaps to explore numerical feature relationships

---

## 🤖 3. Predictive Modeling: Regression Analysis

**Goal:** Predict Purchase Amount using:
- `Item Purchased`
- `Review Rating`
- `Payment Method`

### Models Implemented:
- Linear Regression
- Ridge Regression
- Lasso Regression

### Evaluation Metrics:
- **R² Score:** Measures model explanatory power
- **RMSE:** Measures prediction error

**Result:**  
Linear and Ridge Regression provided the best balance of accuracy and interpretability.

---

## 👥 4. Customer Segmentation: Clustering Analysis

- Applied **K-Means Clustering** using behavioral features
- Determined optimal number of clusters using **Elbow Method**
- Segmented customers into **3 distinct clusters** based on purchase behavior

### Cluster Insights:
- Different clusters represented distinct groups in terms of:
  - Spending power
  - Rating tendencies

---

## 🔑 Key Findings

- **Review Rating** had a weak but notable influence on purchase amount
- **Payment Method** correlated with differences in spending behavior
- **Customer Segments** can be used for **targeted marketing strategies**

---


