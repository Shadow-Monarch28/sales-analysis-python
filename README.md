# Sales Analytics & Exploratory Data Analysis (EDA)

## 🧠 Business Objective
Analyze sales data to identify revenue drivers, profitability patterns, and potential risk areas to support business decision-making.


## 📌 Project Overview
This project is an **end-to-end Sales Analytics and Exploratory Data Analysis (EDA)** exercise designed to reflect **real Data Analyst work**.  
It covers data preparation, feature engineering, statistical analysis, visualization, and business insight generation.

The project demonstrates how raw sales data can be transformed into **actionable business insights**.

# Section Headers:
1. Data Loading
2. Data Cleaning
3. Feature Engineering
4. EDA
5. Insights


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

Cleaned data is saved as: **sales_eda_project.py**

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

## 📌 Insights & Recommendations

- The West region leads in revenue generation and should be prioritized for growth.
- Furniture shows strong profit margins, suggesting pricing or cost advantages.
- Certain low-revenue outliers may indicate underperforming products or data issues.

---

## 📁 Repository Contents
- `sales_eda_project.py` → Complete analysis code  
- `analysis_ready_sales.csv` → Cleaned dataset  
- `README.md` → Project documentation  

---

## 📈 Visualizations

### Total Revenue by Region
![Revenue by Region](Images/revenue_by_region.png)

### Profit Margin by Category
![Profit Margin by Category](Images/Profit_margin_by_category.png)

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
