Data Analytics Project
🧩 Overview

This project demonstrates a complete end-to-end data analytics workflow — from loading and exploring a dataset in Python, to running SQL queries on a PostgreSQL server, building an interactive Power BI dashboard, and presenting insights through a professional Gamma presentation.

The goal is to uncover meaningful insights, visualize trends, and communicate results effectively using modern data tools.

📊 Dataset

Source: Publicly available dataset (CSV format)

Size: ~300K rows

Description: Contains transactional and customer-related data used for trend analysis and performance insights

Key Attributes: Customer ID, Product Category, Purchase Amount, Date, Discount, Age, Region, etc.

🧰 Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn) – Data loading, cleaning, and exploratory data analysis (EDA)

PostgreSQL – Running SQL queries for deeper analysis

Power BI – Building an interactive dashboard for visualization

Gamma – Creating the final presentation deck

Jupyter Notebook – For scripting and documentation

⚙️ Steps Involved
1. Data Loading

Imported dataset into Python using pandas.read_csv()

Performed basic checks for missing values, duplicates, and datatypes

2. Exploratory Data Analysis (EDA)

Summary statistics and data distribution plots

Correlation analysis to identify relationships between variables

Outlier detection and feature understanding

3. Data Cleaning

Handled missing and inconsistent values

Removed duplicates

Converted data types (e.g., dates, numeric fields)

Standardized categorical variables

4. SQL Analysis

Uploaded the cleaned dataset to PostgreSQL

Executed SQL queries for business questions such as:

Top-performing products or customers

Revenue by region or category

Customer segmentation and behavior analysis

5. Dashboard Creation

Imported cleaned dataset into Power BI

Created visuals such as:

KPIs (Revenue, Profit, Discount Rate)

Trend charts and regional breakdowns

Dynamic filters and slicers for interactivity

6. Presentation

Compiled findings, visuals, and insights into a professional Gamma presentation

Highlighted business implications and recommendations

📈 Results & Insights

Identified key revenue-driving segments

Visualized purchase behavior trends across demographics

Provided actionable insights for marketing and sales teams

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/yourusername/data-analytics-project.git


Install dependencies:

pip install -r requirements.txt


Open Jupyter Notebook:

jupyter notebook


Run SQL scripts in PostgreSQL using pgAdmin or psql.

Open Power BI file (.pbix) to explore the dashboard.

View Gamma Presentation via the shared link (included in the repo).

📁 Project Structure
├── data/
│   └── dataset.csv
├── notebooks/
│   └── eda_and_cleaning.ipynb
├── sql/
│   └── analysis_queries.sql
├── dashboard/
│   └── powerbi_dashboard.pbix
├── presentation/
│   └── analytics_presentation.gamma
├── requirements.txt
└── README.md

💡 Future Enhancements

Automate ETL using Python scripts

Integrate dashboard with live database connection

Deploy as a web analytics app
