# SQL Data Cleaning – Layoffs Dataset
## The Business Problem

Raw datasets are often messy, inconsistent, and unreliable, making it difficult for analysts to generate accurate insights.

In the context of layoffs data, poor data quality can lead to:

* Incorrect trend analysis
* Misleading business decisions
* Inconsistent reporting across companies and industries

## Project Objective

This project focuses on cleaning and standardizing a real-world layoffs dataset using SQL to ensure it is accurate, consistent, and ready for analysis or visualization.
Layoffs Dataset: This project focuses on cleaning and preparing a real-world dataset containing information about company layoffs. Using SQL, I performed a series of data wrangling steps to ensure accuracy, consistency, and usability for further analysis or visualization.

## What I Did
* Removed duplicate records to ensure data integrity
* Standardized text fields (e.g., company names, industries) for consistency
* Cleaned and formatted date fields for time-based analysis
* Handled missing values and NULLs appropriately
* Transformed and structured columns to improve usability for analysis
* Prepared the dataset for downstream analysis and visualization


#  Dataset 
The dataset contains company layoff data with features such as:

* Company name
* Location and country
* Industry
* Total employees laid off
* Percentage laid off
* Date of layoff
* Company funding stage
* Funds raised (in millions)

# Data Cleaning Process

Key transformations performed:
* Standardized inconsistent industry labels (e.g., variations of “crypto”)
* Trimmed whitespace and corrected text casing
* Converted date formats into a consistent structure
* Identified and removed duplicate entries
* Ensured numerical fields were properly formatted for analysis
* Created new columns for better time-based analysis

## Business Impact

This cleaned dataset enables:

* More accurate analysis of layoff trends across industries and regions
* Reliable reporting for business and economic insights
* Better decision-making based on consistent and trustworthy data

  
#  Tools Used
* MySQL (Data Cleaning & Transformation)
* SQL (Querying & Data Wrangling)


#  Repository Structure
Raw dataset (original, unprocessed data)
Cleaned dataset (final structured data)
SQL scripts (data cleaning queries)
Documentation (project overview and methodology)
* [Raw Dataset- Original, Unprocessed data](https://github.com/OgaPrecious/SQL-DATA-CLEANING-PROJECT/blob/main/01_raw_data.sql)
* [Raw data in .csv](https://github.com/OgaPrecious/SQL-DATA-CLEANING-PROJECT/blob/main/02_raw_data.csv)
* [Cleaned Dataset-Final Structured Data](https://github.com/OgaPrecious/SQL-DATA-CLEANING-PROJECT/blob/main/03_cleaned_data.sql)
* [Cleaned Data in .csv](https://github.com/OgaPrecious/SQL-DATA-CLEANING-PROJECT/blob/main/04_cleaned_data.csv)
* [Data Dleaning Queries](https://github.com/OgaPrecious/SQL-DATA-CLEANING-PROJECT/blob/main/05_data_cleaning_script.sql)
* [Documentation](https://github.com/OgaPrecious/SQL-DATA-CLEANING-PROJECT/blob/main/README.md)

