Food Delivery Data Analysis Hackathon Project
---------------------------------------------

Project Objective
-----------------

The primary objective of this hackathon project was to demonstrate proficiency in data manipulation, integration, and analysis using Python's Pandas library and related tools. The goal was to consolidate diverse datasets related to a food delivery service, perform various analyses to extract meaningful insights, and prepare the data for further use.




## 1. Provided Files
- **orders.csv**: Order details from a CSV file  
- **users.json**: User information from a JSON file  
- **restaurants.sql**: Restaurant details from an SQL script, involving connecting to an in-memory SQLite database  

## 2. Tech Stack
- **Google Colab**: Cloud-based Jupyter notebook environment for developing, running, and sharing Python code  
- **Python**: Primary programming language for scripting and data manipulation  
- **Pandas**: Library for loading, merging, and analyzing data  
- **SQL**: Used for defining and querying restaurant data  

## 3. Data Analysis Key Findings
- Loaded data from diverse sources (CSV, JSON, SQL)  
- Merged datasets using `pd.merge()` to create a unified dataset  
- Exported consolidated data to `final_food_delivery_dataset.csv`  
- Performed EDA and feature engineering:
  - Calculated revenue per user  
  - Analyzed revenue by city and cuisine  
  - Categorized restaurants by rating  
