Overview
This project analyzes customer shopping behavior using transactional data to uncover spending patterns, product preferences, subscription trends, and key business insights. It demonstrates the full analytics workflow from data loading and cleaning to SQL analysis and interactive dashboarding — ideal for showcasing end-to-end data analytics skills.

Dataset
Source: Internal transactional dataset
Rows: 3,900
Columns: 18
Key Features:
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Item, Category, Amount, Season, Size, Color)
Behavior metrics (Discount Applied, Previous Purchases, Frequency, Review Rating, Shipping Type)
Missing Data: 37 values in review_rating handled via imputation

Tools & Technologies
Stage	Tool
Data Loading & Cleaning	Python (Pandas, NumPy)
Exploratory Data Analysis	Python
Database Analysis	PostgreSQL / MySQL / SQL Server
Visualization & Dashboard	Power BI
Report	Markdown / Document
Presentation	Gamma PPT

Project Steps
Load Dataset in Python
Imported with pandas
Explored with .info() and .describe()
Data Cleaning & Preparation
Checked for missing values
Handled null ratings with median imputation
Standardized column names (snake case)
Engineered features (age groups, purchase frequency)
Database Integration
Loaded cleaned data into PostgreSQL/MySQL/SQL Server
Performed SQL queries for business insights
Exploratory & Business Analysis
Revenue by demographic groups
High-value discount users
Product rating analysis
Subscription behavior
Dashboard Development
Built Power BI dashboard with interactive filters and visual insights
Reporting
Prepared project report summarizing findings
Presentation
Created Gamma-based PPT highlighting key results

Key Results
Identified high-revenue age and gender segments
Compared subscribers vs non-subscribers spending patterns
Found top products by rating and purchase frequency
Evaluated discount strategy and shipping preferences
Developed an interactive Power BI dashboard for business users

How to Run
Python Setup
Clone the repo
git clone https://github.com/subhimaheshwari/customer-behaviour-analysis
cd customer-behaviour-analysis
Install dependencies
pip install -r requirements.txt
Run notebook/script
python analysis.py

Database Setup
Create database (PostgreSQL/MySQL/SQL Server)
Load cleaned CSV into database
Run SQL scripts from /sql_queries/

Power BI
Open dashboard.pbix
Connect to the database or cleaned dataset
Refresh visuals
