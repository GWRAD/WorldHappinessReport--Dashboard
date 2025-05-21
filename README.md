🌍 World Happiness Index 2024 - Power BI Dashboard

This project visualizes and analyzes the 2024 World Happiness Report data using SQL Server and Power BI. It uncovers global patterns in happiness by country, exploring how factors like GDP, freedom, social support, and corruption contribute to national well-being.

📊 Dashboard Highlights

✅ Key Visuals

Top 10 Happiest Countries (Bar Chart)

World Map of Happiness Scores (Filled Map)

Factor Contribution Breakdown (Pie Chart)

Freedom vs. Happiness (Scatter Plot)

Corruption vs. Happiness (Scatter Plot)

🔁 Fully Interactive

Click any country to update the map, pie chart, and scatter plots

Tooltips display ladder score, rank, and underlying factors

🗃️ Dataset Source

World Happiness Report 2024worldhappiness.report

Data includes:

Ladder score (happiness)

GDP per capita (log)

Social support

Life expectancy

Freedom to make life choices

Generosity

Perception of corruption

🛠️ Tech Stack

🔸 SQL Server 2022 Express

Created a normalized Happiness_2024 table

Stored procedures for:

Getting top N happiest countries

Country-specific factor breakdown

Year-wide factor averages

Views created:

vw_HappinessFull2024

vw_HappinessBreakdown2024 (for pie chart)

vw_HappinessMap2024

🔸 Power BI

Imported views and stored procedure outputs

Built a star schema with Query2 as the central table

Used RANKX DAX to assign dynamic happiness ranks

Customized formatting: tooltips, filters, cross-interactions


📌 Key Learnings

Data modeling using star schema for clean relationships

SQL + Power BI integration via stored procedures and views

Advanced visual interactions using slicers and filters

Applying RANKX and tooltip design for storytelling

