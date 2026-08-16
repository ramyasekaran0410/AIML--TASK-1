# AIML Task 1 - Data Analysis and Sales Prediction

## 📌 Project Overview
This repository contains the complete workflow for **AIML Task 1**. The goal of this project is to perform end-to-end data analysis on a Sales dataset and build a simple Machine Learning model to predict future sales. 

## 🛠️ Technologies Used
- **Language:** Python
- **Libraries:** 
  - `Pandas` (Data manipulation & cleaning)
  - `NumPy` (Numerical operations & conditional logic)
  - `Matplotlib` (Data visualization)
  - `Scikit-Learn` (Linear Regression model)

## 📊 Dataset Features
The dataset contains information about various orders, including:
- `Order_ID`, `Product_Category`
- `Customer_Age`, `Quantity`, `Unit_Price`, `Discount`, `Delivery_Days`
- **Target Variable:** `Sales`

## 🚀 Project Workflow
This notebook is divided into 6 main parts:

1. **Data Understanding:** Exploring the dataset structure, data types, and separating numerical/categorical columns.
2. **Data Cleaning:** Identifying and removing missing values (`NaN`) and duplicate records to ensure data quality.
3. **Statistical Analysis:** Calculating mean, median, min, max, standard deviation, and range for key metrics.
4. **Data Visualization (EDA):** 
   - Histograms & Boxplots for Sales distribution.
   - Bar charts for Sales by Product Category.
   - Scatter plots to understand the relationship between Quantity, Unit Price, Delivery Days, and Sales.
5. **Correlation Analysis:** Finding the strongest positive/negative relationships with Sales (Identified `Delivery_Days` as the strongest positive factor).
6. **Machine Learning (Linear Regression):** Trained a Linear Regression model to predict the expected `Sales` for a new order based on user inputs.

## 💡 How to Use
1. Open the `AIML_task_1.ipynb` file in **Google Colab** or Jupyter Notebook.
2. Run all the cells sequentially.
3. In the final cell, you can modify the `new_order` inputs to predict sales for different scenarios.

---
*Created as part of the AIML training/task.*
