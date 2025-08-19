# 📊 Sales Performance Analysis

This project analyzes **Sales Data** to uncover insights about performance across regions, product categories, discounts, and profits. It also includes a **Linear Regression model** to predict sales based on key features.

---

## 📂 Dataset
- **File:** `sales_data.csv`  
- **Columns:**
  - `Product` → Product name  
  - `Region` → Geographical region  
  - `Sales` → Sales amount  
  - `Profit` → Profit earned  
  - `Discount` → Discount percentage  
  - `Category` → Product category  
  - `Date` → Date of transaction  

---

## ⚙️ Tech Stack
- Python 3.x  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  

---

## 🚀 Steps Performed
1. **Data Loading & Cleaning**  
   - Removed duplicates  
   - Handled missing values  
   - Converted `Date` to datetime  

2. **Exploratory Data Analysis (EDA)**  
   - Time series analysis of sales trends  
   - Profit vs. Discount relationship  
   - Sales distribution by Region & Category  

3. **Predictive Modeling**  
   - Linear Regression model trained to predict Sales using Profit & Discount  

---

## 📊 Visualizations
- 📈 Sales trends over time  
- 🔵 Scatter plot: Profit vs. Discount  
- 🗂️ Bar & Pie charts: Sales by Region and Category  
- 🔥 Heatmap: Correlation between features  

---

## 🤖 Model Evaluation
- **Model:** Linear Regression  
- **Features:** Profit, Discount  
- **Target:** Sales  
- **Metric:** R² Score  

---

## 📈 Example Output
- **R² Score:** 0.87
- **Insights:**
             Higher discounts reduce profits significantly.
             Some regions outperform consistently in sales.
             Technology category shows highest growth trend.
