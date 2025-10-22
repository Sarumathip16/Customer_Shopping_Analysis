Customer Shopping Behavior Analysis
Author: Sarumathi Palanisamy

Overview
This project presents an end-to-end data analytics workflow designed to analyze customer shopping data, uncover spending patterns, and generate actionable insights for business decision-making.
The process includes data loading, cleaning, exploratory data analysis (EDA), SQL querying, dashboard creation in Power BI, and a final presentation using Gamma App.
It demonstrates how structured analysis and visualization can transform raw data into meaningful insights that support customer and sales strategies.

Dataset
The dataset contains 3,900+ customer transactions across 18 attributes representing demographic, purchase, and behavioral information.
Key Features:

Customer demographics: age, gender, location
Purchase details: category, purchase amount, season
Shopping behavior: discount applied, previous purchases, subscription status

Tools & Technologies
Programming & Analysis: Python, Pandas, NumPy
Database Management: PostgreSQL / MySQL / SQL Server
Visualization: Power BI
Documentation & Reporting: Microsoft Word, Gamma App
Presentation: PowerPoint (created using Gamma)

Steps Followed
1. Data Loading & Inspection
Loaded dataset using pandas in Python.
Verified structure, data types, and missing values.

2. Data Cleaning & Preprocessing
Handled missing data and duplicates.
Renamed columns for better readability.
Created derived features (e.g., age groups, purchase frequency).

3. Exploratory Data Analysis (EDA)
Conducted univariate and bivariate analysis.
Used matplotlib and seaborn for visual insights into customer behavior and trends.

4. Database Integration
Imported cleaned dataset into PostgreSQL / MySQL / SQL Server.
Used SQLAlchemy or pyodbc for Python–SQL connectivity.

5. SQL Analysis
Performed business-focused SQL queries to explore:
Revenue by gender and age group
Discount impact on spending
Customer segmentation (new, returning, loyal)
Top products by rating and sales

6. Dashboard Creation (Power BI)
Designed an interactive Power BI dashboard with dynamic filters and KPIs.
Visualized sales performance, revenue trends, and customer insights.

7. Reporting & Presentation
Compiled findings into a professional report.
Designed a Gamma presentation deck summarizing key insights and recommendations.

Dashboard Highlights
Dynamic slicers for filtering by customer type, category, or region.
Key KPIs showing total sales, top-performing products, and subscription trends.
Interactive visuals linking customer demographics to purchase behavior.

Results & Insights
Identified top-performing customer segments driving major revenue.
Observed correlation between subscription and higher spending.
Recommended targeted marketing and loyalty programs.
Improved business understanding through visual storytelling and SQL-driven metrics.

How to Run the Project
Clone this repository:
git clone https://github.com/Sarumathip16/Customer-Shopping-Behavior-Analysis.git
Install dependencies:
pip install -r requirements.txt
Run the Jupyter Notebook to perform data cleaning and EDA.

Set up a local or cloud SQL database and execute the provided SQL scripts.

Open the Power BI file to explore the dashboard.

Review the report and presentation inside /reports and /presentation folders.
