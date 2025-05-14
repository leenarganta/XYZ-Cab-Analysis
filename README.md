# VC
XYZ Cab Investment Analysis

Project Objective:
XYZ, a private US firm, is exploring investment opportunities in the Cab industry. This project analyzes historical data to provide insights into market trends, customer behavior, and company performance, ultimately guiding XYZ's investment decision.

Goals of the Project: 
- Analyze cab usage trends across cities.
- Compare performance of two cab companies.
- Understand customer demographics and segments.
- Identify profitable investment opportunities.

Dataset Information:
- Cab_Data.csv: Transaction records from 2016-2018 for two cab companies.
- Customer_ID.csv: Demographic details of customers.
- Transaction_ID.csv: Links transactions to customers and payment modes.
- City.csv: City-wise population and cab user statistics.

Data Cleaning & Preparation: 
- Merged all datasets into a master file.
- Handled missing values, duplicates, and standardized formats.
- Conducted data type conversions.
- Generated calculated fields like Profit Margin, Total Rides, etc.

Exploratory Data Analysis (EDA):
- Seasonal trends in cab usage.
- Company-wise profit margin comparison.
- Customer segmentation by demographics.
- City-wise cab usage density.
- Payment modes and transaction analysis.

Files in this Repository
EDA_XYZ_Cab_Investment.ipynb: Complete Jupyter Notebook for data cleaning, analysis, visualizations, and insights.
Cab_Data.csv: Original cab transaction data.
Customer_ID.csv: Customer demographic dataset.
Transaction_ID.csv: Mapping table for transaction & payment info.
City.csv: City-wise population and cab user data.
DataSets/: Folder containing raw data files.
project.py: Python script for initial file handling and data checks.
Data_Intake_Report.pdf: Summary of dataset properties and structure.

Key Findings & Recommendations: 
- Company A has higher customer retention and consistent profit margins.
- Usage spikes during summer months indicating seasonality.
- Suburban areas with growing population show untapped potential.
- Based on the analysis, Company A is recommended for investment due to its stronger performance and growth prospects.

Tools & Technologies Used:
Python: pandas, numpy, matplotlib, seaborn

Jupyter Notebook for EDA
GitHub for version control and collaboration

Repository Link
https://github.com/leenarganta/XYZ-Cab-Analysis

Author
Leena Ganta
Data Glacier Intern | May 2025

Deliverables for Week 2:
- EDA Notebook (EDA_XYZ_Cab_Investment.ipynb)
- Data Intake Report (Data_Intake_Report.pdf)
- README.md (this file)
