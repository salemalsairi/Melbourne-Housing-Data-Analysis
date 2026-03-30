# 🏙️ Melbourne Real Estate Market Analysis

A comprehensive Data Analysis project exploring the housing market in Melbourne, Australia. This project demonstrates the integration of **SQL** for fast data extraction and **Pandas/Seaborn** for deep visualization and business insights.

## 🎯 Project Objectives (Questions Answered)
1. What are the top 5 most expensive regions in Melbourne?
2. How does the property type (House, Townhouse, Unit) affect the average price?
3. Is there a correlation between the distance from the city center and the price of houses?

## 🛠️ Tools & Technologies Used
- **Python 3.x**
- **SQLite3:** For creating a local database and executing complex queries (`GROUP BY`, `JOIN`, `WHERE`).
- **Pandas:** For data manipulation and integration with SQL via `read_sql_query`.
- **Seaborn & Matplotlib:** For creating professional, business-ready visualizations (Bar plots, Scatter plots with grids and legends).

## 📈 Key Insights Discovered
- **Southern Metropolitan** is the most expensive region on average.
- **Houses (h)** command significantly higher prices compared to Townhouses (t) and Units (u).
- There is a clear **negative correlation** between distance from the CBD and house prices; premium properties are heavily concentrated near the city center.

## 🚀 How to Run
1. Install requirements: `pip install pandas seaborn matplotlib`
2. Run the Jupyter Notebook. The script will automatically fetch the dataset, build the SQLite database, and generate the visualizations.
