Foodie Insights – Restaurant Analytics Dashboard

📌 Overview

Foodie Insights is an end-to-end data analytics project inspired by restaurant platform data.
This project analyzes restaurant performance, customer behavior, pricing, online ordering trends, and ratings.
The goal of this dashboard is to extract actionable insights for business decision-making and visual storytelling.

🚀 End-to-End Tech Stack

Component Tools Used
Database	SQL Server
EDA & Cleaning - 	Python, Pandas, Seaborn
Connection -   ODBC Driver
Visualization -  Power BI , Matplotlib
Dashboard Type -	Interactive BI Dashboard

📥 Dataset Description

The raw dataset contains details of restaurants such as:

Cuisine Type
Cost for Two
Online Order Availability
Ratings
Votes
Type (Cafe, Bar, Dine-in, etc.)

🧱 Project Architecture (Pipeline)

1. Import and Store Data in SQL Server

Created a database and tables in SQL Server.
Loaded raw CSV into SQL Server.

2. EDA and Data Cleaning in Python (Jupyter Notebook)

Performed exploratory data analysis using:

Pandas
NumPy
Matplotlib
Seaborn

Operations performed:

Missing value handling
Data type conversion
Duplicates removal
Outlier treatment
Feature derivation
Summary statistics & trends

Visualizations done using Seaborn:

Cost vs Rating
Distribution plots

3. SQL–Python Connection using ODBC Driver

Connected SQL Server to Python via:

pyodbc + ODBC Driver 17


Pulled data directly from SQL queries into Python.

4. Export Cleaned Data to CSV

After transformation, cleaned data exported to CSV.

5. Import Cleaned Data into Power BI

Used the cleaned dataset for report creation and data modeling.

📊 Dashboard Highlights (Power BI)

Key business KPIs:

Average Cost
Average Rating
Online vs Offline Ordering
Total Votes
Restaurant Type & Cuisine Distribution

Major visuals:

Top 10 restaurants by votes

Top restaurant chains by number of branches

Online vs Offline orders (donut chart)

Cost vs Rating comparison

Slicers for drill-down & filtering

Dashboard is fully interactive with:

Cuisine filters

Price filters (bucket + range)

🎯 Key Insights

✔ Online ordering contributes majority of demand
✔ High cost does not guarantee higher rating
✔ Popular restaurant chains attract highest votes
✔ Certain cuisines dominate customer preference

🧠 Skills Demonstrated

Data engineering in SQL Server

EDA using Python + Seaborn

Data cleaning and transformation

Business analytics & visualization

Power BI data modeling

Interactive dashboarding

📌 Project Files Included

✔ Database scripts (SQL)
✔ Jupyter Notebook EDA
✔ Cleaned dataset
✔ PBIX Power BI Dashboard
✔ README + Screenshots

💡 Future Enhancements

Geospatial location analysis

Cuisine-wise price benchmarking

Automated refresh pipeline

Time-series trends

🏆 Conclusion

Foodie Insights is a complete data analytics project covering:

Data ingestion → EDA → Cleaning → Transformation → Visualization

It answers real business questions and provides measurable insights into the restaurant domain.
