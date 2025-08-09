# Telco Customer Churn Analysis

## 📌 Project Overview
This project analyzes customer churn patterns using the Telco dataset.  
The main goal is to identify factors that contribute to customer attrition and provide actionable insights for reducing churn.

---

## 📂 Contents
- **Data Preparation**
  - Convert data types (e.g., `TotalCharges` from object to float)
  - Replace empty strings with `NaN`
  - Remove rows with missing values
- **Exploratory Data Analysis (EDA)**
  - Customer churn distribution by:
    - Payment Method
    - Internet Service Type
    - Contract Type
    - Tenure
  - Key percentage comparisons for churned vs. retained customers
- **Key Insights**
  - Customers paying via **Electronic Check** have the highest churn rate (~40%).
  - Customers with **Fiber Optic** internet have a churn rate above 40%.
  - **Month-to-month contracts** are the most vulnerable to churn.
  - Most churn happens within the **first 5 months** (~50% of churned customers).

---

## 📊 Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
