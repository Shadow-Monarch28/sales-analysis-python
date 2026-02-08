# Sales Analytics & Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project is an **end-to-end Sales Analytics and Exploratory Data Analysis (EDA)** exercise designed to reflect **real Data Analyst work**.  
It covers data preparation, feature engineering, statistical analysis, visualization, and business insight generation.

The project demonstrates how raw sales data can be transformed into **actionable business insights**.

---

## 🛠 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📂 Dataset
A realistic sales dataset was generated with the following fields:
- `date`
- `region`
- `category`
- `product`
- `sales`
- `quantity`
- `profit`

Derived fields:
- `revenue`
- `profit_margin`

Cleaned data is saved as:

---

## 🔄 Project Workflow

### 1️⃣ Data Understanding
- Checked data shape, schema, and summary statistics
- Identified data quality issues

### 2️⃣ Data Cleaning & Feature Engineering
- Removed invalid or missing records
- Created revenue and profit margin features
- Converted and sorted date fields
- Removed duplicates
- Standardized column formats

### 3️⃣ Exploratory Data Analysis (EDA)
- Revenue analysis by region
- Profit margin analysis by category
- Monthly revenue trends
- Correlation analysis between revenue and profit
- Outlier detection using IQR method

### 4️⃣ Visualization
- Bar chart: Total revenue by region
- Boxplot: Profit margin distribution by category

---

## 📊 Key Business Insight
> **The West region generates the highest total revenue, while the Furniture category shows a strong average profit margin.**

---

## 📁 Repository Contents
- `sales_eda_project.py` → Complete analysis code  
- `analysis_ready_sales.csv` → Cleaned dataset  
- `README.md` → Project documentation  

---

## 🎯 Skills Demonstrated
- Data cleaning & validation
- Feature engineering
- Aggregation & pivot analysis
- Statistical reasoning
- Business-focused EDA
- Data visualization
- Insight communication

---

## 🚀 How to Run
```bash
pip install pandas numpy matplotlib seaborn
python sales_eda_project.py
