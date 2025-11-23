# 📊 Basic Statistics – Analysis Notebooks

This repository contains two Jupyter notebooks demonstrating foundational concepts in **descriptive analytics**, **data preprocessing**, and **basic statistical methods** using real-world datasets.  
Each notebook focuses on practical analysis, visualizations, and data cleaning techniques useful for beginners and intermediate data analysts.

---

# 📘 BASIC STATISTICS – 1  
### *Descriptive Analytics and Data Preprocessing on Sales & Discounts Dataset*

## **Introduction**
- Perform descriptive analytics, visualize data distributions, and preprocess the dataset for further analysis.

## **Descriptive Analytics for Numerical Columns**
**Objective:** Compute and analyze basic statistical measures for numerical columns.  
**Steps:**
- Load the dataset into a programming environment (e.g., Python with `pandas`).
- Identify numerical columns.
- Calculate **mean**, **median**, **mode**, and **standard deviation**.
- Provide interpretations for each statistical measure.

## **Data Visualization**
**Objective:** Visualize the distribution and relationships of numerical and categorical variables.

### **Histograms**
- Plot histograms for numerical columns.
- Analyze distribution (skewness, outliers, shape) and draw insights.

### **Box Plots**
- Create boxplots to identify outliers and interquartile ranges.
- Highlight unusual or extreme values.

### **Bar Chart Analysis for Categorical Columns**
- Identify categorical columns.
- Create bar charts to visualize category frequencies.
- Analyze category distribution to derive insights.

## **Conclusion**
- Summarize findings from descriptive analytics and visual exploration.

---

# 📘 BASIC STATISTICS – 2  
### *Hospital Patient Data Analysis*

## **Problem Statement**
Analyze hospital patient records containing admission details, department, diagnosis, doctor, and billing information.  
Multiple datasets are provided, including patient info and billing details.

## **Context**
- Some patients may have blank bill amounts.
- Patients can appear multiple times due to follow-up visits.
- Goal: Clean, merge, and analyze data for billing accuracy and department-wise cost evaluation.

## **Tasks**
1. Load the patient dataset and display summary using `info()`.
2. Select relevant billing columns:  
   `['PatientID', 'Department', 'Doctor', 'BillAmount']`
3. Drop administrative columns:  
   `['ReceptionistID', 'CheckInTime']`
4. Use `groupby` to find **total bill amount per department**.
5. Remove duplicate patient records based on `PatientID`.
6. Fill missing `BillAmount` values using the **mean bill amount**.
7. Merge billing and patient datasets on `PatientID`.
8. Concatenate an additional DataFrame containing current-week patients (row-wise).
9. Concatenate new billing category columns such as:  
   `['InsuranceCovered', 'FinalAmount']` (column-wise).

## **Expected Outcome**
- Clean, accurate billing dataset.
- All missing values filled appropriately.
- Merged dataset aligned by `PatientID`.
- Ability to perform deeper analytics such as:
  - Department-wise revenue
  - Doctor performance comparison
  - Weekly patient trends

---
