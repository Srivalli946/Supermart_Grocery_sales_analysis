# Supermart_Grocery_sales_analysis
# 🛒 Supermart Grocery Sales - Retail Analytics

This project analyzes sales data from a fictional grocery delivery app in Tamil Nadu, India. It includes data preprocessing, exploratory data analysis (EDA), and building a machine learning model to predict sales using linear regression.

---

## 📁 Dataset

- **Source:** Provided for educational purposes
- **Format:** CSV
- **Size:** ~10,000 records
- **Features Include:**
  - Order ID, Customer Name, Category, Sub Category
  - City, Region, State
  - Order Date (with extracted day, month, year)
  - Sales, Discount, Profit

---

## 🧰 Tools & Technologies

- Python 🐍  
- Pandas, NumPy for data manipulation  
- Matplotlib, Seaborn for data visualization  
- Scikit-learn for machine learning  
- Jupyter Notebook for interactive development  

---

## 📊 Project Workflow

### 1. 📦 Data Loading & Cleaning
- Handled missing and duplicate values
- Converted date columns to proper datetime formats

### 2. 🔨 Feature Engineering
- Extracted month, year, day from Order Date
- Label encoded categorical variables

### 3. 📈 Exploratory Data Analysis (EDA)
- Visualized sales trends by category, month, and year
- Heatmap of feature correlations
- Identified high-performing product categories and regions

### 4. 🤖 Predictive Modeling
- Built a **Linear Regression** model to predict `Sales`
- Used features like Category, City, Discount, Profit, etc.

### 5. 📊 Model Evaluation
- Mean Squared Error (MSE)
- R-squared (R²)
- Scatter plot of Actual vs Predicted sales

---

## 🧪 Results

| Metric        | Value     |
|---------------|-----------|
| MSE           | ~1758     |
| R² Score      | ~0.82     |

The model demonstrates a good fit, capturing over 80% of the variance in sales.

---

## 📌 Key Insights

- **Egg, Meat & Fish** category contributes highest to sales.
- Sales increased progressively from 2016 to 2018.
- Top cities like Chennai and Coimbatore drive a large portion of revenue.

---

## 🚀 Future Enhancements

- Try advanced models: Random Forest, XGBoost
- Feature selection via correlation or SHAP
- Build a dashboard using Tableau, Power BI, or Streamlit
- Deploy model as a REST API or in a web app

---


