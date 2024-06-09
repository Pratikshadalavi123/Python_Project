# Python_Project
## Overview 
The primary objective of the project is to analyze customer churn, which involves identifying patterns and factors that lead customers to leave a service or company. The project utilizes data analysis and visualization techniques to gain insights into customer demographics and behaviors that correlate with churn. 
### Data Source 
Dataset ChurnEda.csv" 
Number of Records. 10,000 
### Attributes: 
including Customerld, CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActive Member, EstimatedSalary, Exited, and Churned/Retained. 
 
## Methodology 
 
### 1. Data Loading and Initial Inspection 
Libraries Used: NumPy, Pandas, Matplotlib Seaborn  
Data Loading. The dataset is loaded into a Pandas DataFrame. 
### 2.Unique Values. Identification of unique values for categorical columns (Geography, Gender, NumOfProducts, etc.). 
### 3.	Data Cleaning 
Duplicates. Checked for and confirmed no duplicates in the dataset. 
Missing Values: Confirmed no missing values using 'df.isnull().sum(). 
 
##  4.	Data Visualization 
 
### Scatter Plot: Visualized relationship between Geography and EstimatedSalary, differentiated by Gender. 
### Bar Plot: Compared EstimatedSalary across different Geographies, segmented by Gender. 
### PieChart: Showed the distribution of customers across France, Spain, and Germany. 
### Heatmap: Used to check for missing values visually (none found). 
 
## Key Insights and Findings 
Customer Distribution: Majority of customers are from France (5014), followed by Spain (2477) and Germany (2509). 
 
### Customer Demographics and Financials: 
Age, CreditScore, Balance, and EstimatedSalary distributions provide insight into the 
 
## Churn Analysis:
The Exited and 'Churned/Retained' columns are crucial for understanding the churn status of each customer. 
 
## Conclusion :
 
This overview encapsulates the key elements of the project, providing a comprehensive understanding of the data analysis and visualization techniques employed to study customer churn. 






