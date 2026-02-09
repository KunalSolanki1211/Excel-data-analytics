# Sales Data Cleaning and Analysis (Excel)

## Project Overview
This project focuses on cleaning, standardizing, and analyzing sales transaction data using Microsoft Excel.  
The dataset initially contained inconsistent formats, missing values, and data quality issues.  
The objective was to prepare clean, analysis-ready data and generate basic business insights.

---

## Dataset Description
The dataset contains sales transaction records with the following fields:
- Transaction ID  
- Date and Month  
- Department  
- Category  
- Product Name  
- Region  
- Sales Person  
- Units Sold  
- Unit Price  
- Cost  
- Revenue  
- Profit  

---

## Issues in Raw Data
- Multiple date formats (text dates, numeric dates, mixed formats)
- Inconsistent text casing (Sales, sales, SALES)
- Missing values in the Sales Person column
- Numbers stored as text (Units Sold, Unit Price)
- Inconsistent category and department naming

---

## Sheets Explanation

### 1. Raw_Data
- Original dataset with no modifications  
- Preserved to show the initial state of the data before cleaning

---

### 2. Cleaned_Data
This sheet contains the fully cleaned and standardized dataset.

**Cleaning steps performed:**
- Converted all date values into proper Excel date format  
- Standardized department, category, and region names  
- Converted numeric text values into numbers  
- Replaced missing Sales Person values with `"Unknown"`  
- Ensured consistency across all columns  
- Verified revenue and profit values for accuracy  

The cleaned data is structured and ready for analysis or dashboarding.

---

### 3. Cleaning_Steps
This sheet documents the complete data cleaning process step-by-step, including:
- Data structure setup  
- Duplicate removal  
- Format standardization  
- Data validation checks  

This sheet is included to clearly explain the logic and workflow used during cleaning.

---

### 4. Pivot_Analysis
Pivot tables were created to analyze business performance, including:
- Revenue by Department  
- Total Units Sold  
- Total Revenue  
- Total Profit  
- Average Order Value  

These summaries help in understanding department-wise contribution and overall sales performance.

---

### 5. Dashboard
A simple Excel dashboard summarizing key metrics:
- Total Revenue  
- Total Profit  
- Total Units Sold  
- Average Order Value  

Designed to provide a quick, high-level overview for decision-making.

---

## Excel Features Used
- Data cleaning and formatting  
- IF and IFERROR formulas  
- Text-to-number conversion  
- Pivot Tables  
- Basic KPI calculations  
- Dashboard creation  
- Data validation techniques  

---

## Outcome
- Raw, inconsistent data converted into a clean and structured dataset  
- Clear separation between raw data, cleaned data, analysis, and dashboard  
- Actionable insights generated using pivot tables and KPIs  
- Improved data reliability and readability  

