# college-roi-dashboard

🎓 Overview
This project analyzes the Return on Investment (ROI) for colleges across India based on tuition fees, placement packages, and cutoff ranks. It demonstrates my ability to work with relational databases (SQL), perform data transformations, create views, and develop an interactive Power BI dashboard for insightful decision-making.

📁 Project Structure
🔧 Database Setup
Created a database named college_roi_db

Tables:

college_table: college details (name, type, stream, state)

fees_table: tuition, hostel, and total fees

placements_table: average and highest packages, placement rate

cutoffs_table: exam cutoff ranks

📥 Data Import & Cleaning
Imported 4 CSV files into MySQL using schema-based approach

Handled data type conversions, ensured referential integrity, and filtered only general category records for consistency

🛠 Feature Engineering
Calculated custom ROI metric using:

sql
Copy
Edit
ROI (%) = (Average Package / Total Fee) * 100
Created a SQL view to join all key tables and export the clean dataset for Power BI

📊 Power BI Dashboard
Built an interactive one-page dashboard with slicers and KPI cards

Visualizations include:

Top 5 Colleges by ROI

State-wise Average ROI

Stream-wise ROI vs Average Package (combo chart)

ROI vs Cutoff Rank (scatter plot)

KPI cards: Highest ROI %, Average ROI %, Total Colleges

Insight summary and design enhancements with tooltips and grid background

📷 Dashboard Preview
(Add screenshot here in your GitHub README or repo)

🔑 Key Insights
🎯 IIM Ahmedabad had the highest ROI at 767%

⚙️ Engineering programs showed the best return compared to MBA and Medical

🎓 AIIMS had high ROI with low cutoff rank — indicating maximum value

📍 Top 5 colleges by ROI are all government institutions

🔍 Scatter plot showed correlation between low cutoff ranks and high ROI

💡 Actionable Recommendations
Prospective students should prioritize ROI alongside rankings

Engineering and government colleges generally offer higher returns

Streamlining tuition fees and boosting placements can increase ROI

📁 Files Included
File Name	Description
college_roi_db_schema.sql	SQL script to create and join tables
college_data_cleaned_view.sql	SQL view with final joined data
college_roi_dashboard.pbix	Power BI dashboard file
college_roi_data.csv	Exported CSV from SQL view
README.md	Project documentation

🧰 Tools Used
SQL (MySQL): joins, views, group-by aggregations, filtering

Power BI: data modeling, DAX measures, KPI cards, interactive visuals

Power Query: importing and transforming SQL-exported data

Excel/CSV: base data structure

💼 Author
Navya M
Data Analyst | SQL | Power BI | Excel
🔗 LinkedIn Profile | GitHub Projects

📢 Notice
This project uses synthetic data created for learning and demonstration purposes. It does not reflect real college data and is not affiliated with any educational institution.



