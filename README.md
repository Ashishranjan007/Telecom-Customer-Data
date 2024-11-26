# Customer Churn Analysis and Prediction

## 📋 Overview
This project aims to analyze customer churn patterns and predict potential churners using a comprehensive **ETL Process**, **Power BI Dashboards**, and **Machine Learning Models**. It provides actionable insights to help organizations retain customers and design effective marketing campaigns.

---

## 🎯 Objectives
- Visualize and analyze customer data at **Demographic**, **Geographic**, **Payment & Account Info**, and **Service** levels.
- Study churner profiles and identify areas for implementing marketing campaigns.
- Develop a predictive model to identify potential future churners.

---

## 🚀 Features
1. **ETL Process in SQL Server:**
   - Created and managed a database in **SQL Server** to handle recurring data loads.
   - Imported CSV data into staging tables using the **Import Wizard**.
   - Transformed data using SQL queries to prepare for analysis.

2. **Interactive Power BI Dashboards:**
   - Visualized customer data, including churn metrics, demographic trends, and service usage.
   - Key Metrics:
     - **Total Customers**
     - **Total Churn & Churn Rate**
     - **New Joiners**
   - Segmentation:
     - **Churn Status**: Based on customer status.
     - **Monthly Charge Range**, **Age Groups**, and **Tenure Groups**.
   - Insights:
     - Top demographic and geographic churn patterns.
     - Service utilization impact on churn.

3. **Churn Prediction with Machine Learning:**
   - Implemented a **Random Forest Classifier** using **Python** to predict potential churners.
   - Utilized SQL Server data exports for model training.
   - Enhanced prediction accuracy with data preprocessing and feature engineering.

4. **Power BI Visualization of Predictions:**
   - Imported predicted churn data into Power BI for further analysis.
   - Created comprehensive visualizations for predicted churn metrics.

---

## 📂 Project Structure
```plaintext
|-- ETL Process (SQL Queries and Scripts)
|-- Power BI Dashboards
|   |-- Summary Dashboard
|   |-- Churn Insights
|   |-- Predicted Churn Analysis
|-- Machine Learning Model (Python)
|   |-- Data Preprocessing
|   |-- Feature Engineering
|   |-- Random Forest Classifier
|-- SQL Server Data Exports
|-- Prediction Data
|-- README.md


## How to Use
1. Clone this repository:
2. Open the Power BI report (`reports/Churn Analysis.pbix`) for visualization.
3. Run scripts in the `src/` folder to preprocess data and train predictive models.

## Tools and Technologies
- **Excel**: Dataset preparation.
- **SQL**: For data extraction and transformation.
- **Power BI**: For creating interactive visualizations and dashboards.
- **Python**: Libraries used include Pandas, NumPy, Matplotlib, and scikit-learn.

## Insights
Key findings from the analysis:
- [Add bullet points of key insights, e.g., major reasons for customer churn, patterns observed]

## Contact
For queries or suggestions, reach out at:
- **Email:** ashishranjan5323@gmail.com
- **LinkedIn:** [Ashish Ranjan](https://www.linkedin.com/in/ashish-ranjan-4a3799266/)
