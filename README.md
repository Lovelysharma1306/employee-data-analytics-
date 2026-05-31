# 📊 Employee Data Analytics

This project is a **business analytics case study** using Python in Google Colab.
It demonstrates how to clean and analyze a messy employee dataset to extract actionable HR and management insights.

---

## 🛠 Tools & Libraries
- Python (Google Colab)
- Pandas — data cleaning & manipulation
- Matplotlib & Seaborn — data visualization
- NumPy — numerical operations

---

## 📂 Repository Structure
- Messy_Employee_dataset.csv — Raw input data
- Cleaned_Employee_dataset.csv — Cleaned output data
- Employee_Data_Analysis.ipynb — Google Colab notebook
- README.md — Project documentation

---

## 🗂 Datasets

### 1. Messy Dataset
Raw HR data with missing values, inconsistent entries, and formatting issues.
- Missing ages for several employees
- Salary column containing N/A values
- Combined Department_Region column needing splitting
- Duplicate records and invalid phone numbers

### 2. Cleaned Dataset
- Missing ages filled with median values
- Salary converted to numeric and imputed
- Department and Region extracted as separate columns
- Duplicate records removed
- Dates standardized to datetime format

---

## 🔎 Business Questions Answered
1. Which department has the highest average salary?
2. Is remote work associated with higher performance scores?
3. What is the salary distribution across different regions?
4. Which year had the most employee joinings?
5. Which performance score category earns the highest average salary?

---

## 📈 Business Insights
- Salary trends vary significantly across departments and regions
- Remote work shows patterns linked to performance scores
- Hiring surges can be tracked by join year
- Performance scores correlate with compensation differences

---

## 💡 Business Analytics Value
This project demonstrates how raw HR data can be transformed into **decision-support insights** for management:
- Identifying compensation trends
- Understanding workforce performance
- Tracking hiring patterns over time
