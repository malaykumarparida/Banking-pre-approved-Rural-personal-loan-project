# Bank Personal Loan Lead Analysis – Banking (Rural Customers)

This project demonstrates a complete **end-to-end data analyst workflow** using **MySQL** and **Python (Pandas)** to identify rural customers who are eligible for **pre-approved personal loans**. The goal was to generate high-quality leads and reduce unnecessary calling efforts by bank employees.  

## Project Overview
- **Domain:** Banking / Personal Loans  
- **Data Size:** 500+ rows per table  
- **Tools Used:**  
  - **MySQL** – data integration, cleaning, and analysis  
  - **Python (Pandas)** – missing value imputation, EDA, and preprocessing  

## Problem Statement
Banking faced the issue of making many calls to customers but generating fewer leads for personal loans. The objective was to filter and prioritize customers who are more likely to take a loan.

## Datasets
1. Customer Demographics (age, gender, occupation, location)  
2. Financial Information (income, expenses)  
3. Debt-to-Income Ratio  
4. CIBIL Score  
5. Previous Loan History (with Axis and other banks)  
6. Credit & Risk Scores  
7. Delinquency & Default History  
8. Current Active Loans  
9. Last 6 Months’ Bank Statements  
10. Fixed Deposit Data  
11. Call Logs (response history)

Each table contains **more than 500 records**.  

## Process

### 1. Database and Tables
- Created database and tables using MySQL  
- Inserted data for all entities (customer info, financials, cibil, etc.)  

### 2. Data Cleaning
- Used **box plots** to detect outliers  
- Filled missing numerical data using **median** (Python Pandas)  
- Filled missing categorical data using **mode**  

### 3. Data Merging
- Used **SQL JOINs** to integrate data from multiple tables  
- Prepared a unified dataset for analysis  

### 4. Exploratory Data Analysis (EDA)
- Identified patterns in **CIBIL scores, loan history, and call logs**  
- Filtered customers who missed more than 7 calls  
- Segmented customers with **high probability** of taking loans  

### 5. Lead Generation
- Created a **filtered lead list** directly in SQL  
- Exported results for business teams  

## Outcome
- **Reduced wasted calls** by targeting only high-potential leads  
- Built a **reusable SQL + Python pipeline** for banking analytics  
- Provided a **scalable framework** for future loan campaigns  

## Future Enhancements
- Add **machine learning lead scoring models**  
- Build **Tableau or Power BI dashboards**  
- Automate the entire pipeline using **Airflow or cron jobs**  

---

### How to Run
1. Clone this repository  
2. Import SQL files into MySQL to create database & tables  
3. Run Python scripts for cleaning and EDA  
4. Execute queries to generate the final lead list  

---

**Author:** Malay Kumar Parida
--https://www.linkedin.com/in/malay-kumar-parida/
--malayparida96@gmail.com
