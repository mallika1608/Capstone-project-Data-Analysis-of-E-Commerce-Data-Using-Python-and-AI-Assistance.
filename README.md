Data Analysis of E-Commerce Sales Data Using Python and AI Assistance
Technologies Used
The project was developed using Python in a Jupyter Notebook environment. The following technologies and libraries were used:
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Pathlib
HTML/CSS (for dashboard generation)
AI assistance was used throughout the project to generate reusable, clean, and beginner-friendly Python code.

2. Data Description
Datasets Used
The project used three CSV datasets:
List of Orders.csv
Contains order-level information such as:
Order ID
Order Date
Customer Name
State
City
Order Details.csv
Contains transactional line-item information such as:
Order ID
Category
Sub-Category
Amount
Profit
Quantity
Sales target.csv
Contains monthly category-level sales targets:
Month
Category
Target

Data Format
File format: CSV
Structured tabular data
Loaded into Pandas DataFrames for analysis

Data Quality Checks Performed
The following checks were performed:
Missing value detection
Duplicate record checks
Data type validation
Standardization of date formats
Removal of fully empty rows
Removal of unnecessary spaces in key columns
Validation of merge keys before joins

Data Quality Issues Identified
Some of the issues identified in the datasets were:
Missing values in customer-related fields
Fully blank rows
Trailing spaces in join columns
Inconsistent date formats
Duplicate transactional rows
Negative profit values
Missing join key values

Handling of Data Issues
Missing IDs were replaced using stable UNKNOWN identifiers
Dates were standardized into a common format
Duplicate rows were analyzed and cleaned carefully
Merge keys were standardized before joining datasets
Audit reports were created to validate merge quality and data consistency

3. Techniques Used
The following data analysis techniques were used:
AI-assisted Prompt Engineering — used AI to help craft better prompts.
Data Cleaning
Data Auditing
Missing Value Handling
Duplicate Detection
Data Standardization
Outer Joins and Merge Validation
Exploratory Data Analysis (EDA)
Trend Analysis
Profitability Analysis
Target vs Actual Performance Analysis
Dashboard Creation using HTML

4. Step-by-Step Process
Installed and imported required Python libraries.
Created reusable project folder structure using Pathlib.
Loaded all CSV files into Pandas DataFrames.
Performed initial dataset inspection.
Created reusable audit functions for data quality checks.
Identified missing values, duplicates, and formatting issues.
Cleaned datasets and standardized formats.
Validated unique keys and join conditions.
Removed invalid duplicates.
Merged datasets using outer joins with audit tracking.
Created exploratory data analysis visualizations using Seaborn and Matplotlib.
Generated management-level business insights for each visualization.
Created an HTML dashboard to display charts and insights together.
