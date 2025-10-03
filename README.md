## 🍕 Pizza Sales Exploratory Data Analysis (EDA)

# Objective
The primary objective of this project was to perform an Exploratory Data Analysis (EDA) on a complete year of pizza sales data to establish a baseline understanding of business performance, identify key sales drivers, and uncover patterns that could inform inventory, marketing, and product strategy.

💾 Data & Tools
Category	Description
Dataset: Pizza 
Sales Transactional: Data (38,811 records, 12 columns)
Tools: Python (Google Colab, Jupyter Notebook), Pandas, Matplotlib, Seaborn)
# Key Steps Completed (Phase 1: Data Acquisition & Inspection)

In this foundational phase, I established a clean and reliable environment for the subsequent analysis. This stage demonstrates strong skills in data integrity and initial quality checks.

1. Data Ingestion and Environment Setup
Action: Imported core Python libraries (pandas, numpy, matplotlib, seaborn) and loaded the pizza_sales.csv file into a DataFrame.

Skill Demonstrated: Efficiently setting up a data science environment and demonstrating familiarity with key analytical tools.

2. Initial Data Structure Validation
Action: Used df.head() and df.shape to confirm the successful loading of 38,811 records and verify the presence of critical columns (e.g., total_price, quantity, pizza_category).

Skill Demonstrated: Performing immediate data quality assurance to ensure completeness and structural accuracy before proceeding.

3. Data Type and Summary Check
Action: Executed preliminary checks using methods like df.info() and df.describe() (or attempted to) to survey the data types and distribution of numerical columns.

Skill Demonstrated: Proactively identifying potential data cleaning requirements, such as converting order_date and order_time from object/string types to proper datetime objects for time-series analysis.

#  Portfolio Impact Statement
This initial phase successfully transformed raw transactional data into a usable, structured format. By validating the dataset's integrity and dimensions, I laid the necessary groundwork to move into advanced feature engineering and in-depth visualization to answer specific business questions about sales trends and product popularity.
