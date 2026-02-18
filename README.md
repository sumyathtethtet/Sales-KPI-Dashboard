# Sales KPI Dashboard

## Project Overview
This project analyses sales data from a sample dataset to create a **Sales KPI Dashboard**. The goal is to provide actionable insights into sales trends, regional performance, product performance, and shipping efficiency.

## Features
- Data cleaning and preprocessing using Python (Pandas, NumPy)
- Exploratory Data Analysis (EDA) on sales data
- Visualisations using Matplotlib and Seaborn
- Key insights documented in `INSIGHTS.md`
- Data summarization and aggregation using Python `groupby` and `sum()` (equivalent to Excel Pivot Tables)

## Tools & Technologies
- **Programming:** Python (Pandas, NumPy), SQL
- **Data Visualisation:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook, VS Code
- **Data:** CSV files stored in the `data/` folder

## Project Structure
The `Sales-KPI-Dashboard` repository is organized as follows:
Sales-KPI-Dashboard/
│
├── data/ # CSV datasets
│ ├── train.csv # Original raw sales data
│ └── clean_sales_data.csv # Cleaned and preprocessed data
│
├── notebooks/ # Jupyter notebooks
│ ├── cleaning_analysis.ipynb # Data cleaning and preprocessing
│ ├── analysis.ipynb # Data aggregation and KPI calculation
│ └── visualisation.ipynb # Charts and visualisation
│
├── images/ # Exported charts and graphs (PNG)
│ ├── sales_by_category.png
│ ├── sales_by_region.png
│ ├── sales_by_month.png
│ ├── sales_by_year_bar.png
│ └── sales_by_year_line.png
│
├── INSIGHTS.md # Key insights from the analysis
└── README.md # Project overview and instructions

## Notes
- Visualisations include bar charts, line plots, and distribution plots for key KPIs such as total sales, sales by year, sales by region, top products, and shipping efficiency.