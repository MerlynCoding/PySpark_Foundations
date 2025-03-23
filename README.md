# PySpark_Foundations

# 📊 PySpark Employee & Salary Data Analysis Project

## 🚀 Project Overview

This project focuses on using **PySpark** to process, analyze, and visualize employee and salary datasets, simulating a real-world big data scenario. The project demonstrates how to handle large datasets by performing data cleaning, aggregation, joining multiple datasets, and creating insightful visualizations to support data-driven decisions.

---

## 📚 **Key Learning Outcomes**
- Setting up a PySpark environment.
- Loading and preprocessing large datasets.
- Data exploration and missing value analysis.
- Data aggregation and summarization using **PySpark functions**.
- Joining datasets using efficient Spark SQL techniques.
- Visualizing insights using **Matplotlib** and **Seaborn**.
- Performing an employee retention analysis based on tenure.

---

## 🗂 **Datasets Used**
- `employees.csv`: Employee records including `emp_no`, `first_name`, `birth_date`, `hire_date`, etc.
- `updated_salaries.csv`: Employee salary data including `salary`, `from_date`, `to_date`, and `dept_no`.

---

## 🛠 **Technologies Used**
- **Python 3.11**
- **PySpark** (Spark SQL & DataFrame API)
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## ⚙️ **Steps Performed**

1. **Environment Setup**
   - Initialized a SparkSession for data processing.

2. **Data Loading**
   - Loaded both employee and salary datasets into PySpark DataFrames.

3. **Data Cleaning**
   - Casted columns to appropriate types (e.g., `date`, `string`).
   - Checked and summarized missing values.

4. **Exploratory Data Analysis**
   - Counted unique employees, rows, and explored distributions.
   - Visualized salary distribution using Seaborn.

5. **Aggregation**
   - Aggregated data to calculate average salary, max salary, and employee counts per department.

6. **Joining DataFrames**
   - Merged employee and salary datasets using **left joins** to create a comprehensive dataset.

7. **Retention Analysis**
   - Identified employees who worked more than **10 years**.
   - Aggregated long-term employees by department.

8. **Visualization**
   - Created bar charts for department-wise employee retention and employee counts.

---

## 📊 **Sample Visualizations**

| ![Salary Distribution](./screenshots/salary_distribution.png) | ![Retention Bar Plot](./screenshots/retention_plot.png) |
|:--:|:--:|
| *Salary Distribution* | *Long-Term Employee Distribution* |

---

## 🔍 **Insights Gained**
- Departments with the highest retention of long-term employees.
- Salary patterns across departments.
- Identified high-earning employees with average salaries exceeding \$120,000.

---

## 🙌 **What I Learned**
- End-to-end PySpark workflow from setup to analysis.
- Handling big datasets using Spark DataFrames efficiently.
- Using Spark SQL aggregation functions for summarizing large datasets.
- Combining Spark and Pandas for efficient big data visualization.
- Deepened understanding of employee retention metrics in HR analytics.

---

## 💡 **Next Steps**
- Implement Spark MLlib for predictive analytics (e.g., predicting employee attrition).
- Automate the ETL pipeline using Apache Airflow.
- Deploy Spark jobs on a distributed cluster (e.g., AWS EMR).

---

## 🧑‍💻 **Author**

**James** - Junior Data Analyst

---
