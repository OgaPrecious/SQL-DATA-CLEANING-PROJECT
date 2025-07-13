# SQL-DATA-CLEANING-PROJECT
🧹 SQL Data Cleaning: Layoffs Dataset This project focuses on cleaning and preparing a real-world dataset containing information about company layoffs. Using SQL, I performed a series of data wrangling steps to ensure accuracy, consistency, and usability for further analysis or visualization.


# 📦  Dataset Overview
The dataset includes the following variables:
* company: Name of the company
* location: Specific city or region
* industry: Industry sector of the company
* total_laid_off: Number of employees laid off
* percentage_laid_off: Proportion of workforce laid off
* date: Date of the layoff
* stage: Company funding stage (e.g., Series A, Series B)
* country: Country of operation
* funds_raised_per_millions: Total funds raised by the company in millions

# 🧽 Data Cleaning Tasks

* Removed duplicate records
* Cleanded text casing and removed extra white spaces
* Standardized inconsistent industry names (e.g., "crypto, cryptocurrency." to "crypto")
* standardized date formats
* Handled missing values and NULLs
* Created new columns for better time-based analysis

  
# 🔧 Tools Used
* MySQL for data querying and transformation
* Cleaned SQL scripts available for reproducibility
* Well-documented workflow with comments in each query

# 📂 Repository Structure
* [Click here to view the raw data SQL script](https://github.com/OgaPrecious/SQL-DATA-CLEANING-PROJECT/blob/main/01_raw_data.sql)— Original unprocessed data
* [Click here to view the data cleaning SQL script](https://github.com/OgaPrecious/SQL-DATA-CLEANING-PROJECT/blob/main/02_data_cleaning.sql) — SQL queries used for cleaning
* [click here to view the cleaned data SQL](https://github.com/OgaPrecious/SQL-DATA-CLEANING-PROJECT/blob/main/cleaned_data.sql)— Final cleaned version of the dataset
* README.md — Overview and explanation of the cleaning process

# ✅ Ideal for: 
Data analysts looking to practice real-world SQL data cleaning techniques on messy business data.

