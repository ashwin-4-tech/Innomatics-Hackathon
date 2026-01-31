Food Delivery Data Analysis Hackathon Project
---------------------------------------------

Project Objective
-----------------

The primary objective of this hackathon project was to demonstrate proficiency in data manipulation, integration, and analysis using Python's Pandas library and related tools. The goal was to consolidate diverse datasets related to a food delivery service, perform various analyses to extract meaningful insights, and prepare the data for further use.


Provided Files:
---------------

orders.csv: Order details from a CSV file.
users.json: User information from a JSON file.
restaurants.sql: Restaurant details from an SQL script, involving connecting to an in-memory SQLite database.


Tech Stack:
----------

Google Colab: The cloud-based Jupyter notebook environment used for developing, running, and sharing the Python code for data processing and analysis.
Python: The primary programming language utilized for scripting, data manipulation, and orchestrating the entire data analysis workflow.
Pandas: A powerful Python library specifically used for data loading (from CSV, JSON), manipulation, merging (DataFrames), and conducting various data analyses.
SQL: Employed for defining and populating a relational database schema for restaurant data, which was then queried and loaded into a Pandas DataFrame.


Data Analysis Key Findings:
--------------------------

Loading data from diverse sources: orders.csv (CSV), users.json (JSON), and restaurants.sql (SQL).
Merging and integrating these datasets using pd.merge() to create a unified dataset.
Exporting the final consolidated data to final_food_delivery_dataset.csv.
Performing Exploratory Data Analysis (EDA) and feature engineering, such as calculating revenue per user, analyzing revenue by city and cuisine, and categorizing restaurants by rating.
