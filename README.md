# customer_behavior_analysis
Data analytics project showcasing customer behavior analysis using Python, SQL and Tableau
Customer Shopping Behavior Analysis 🛒
Overview 📊

This project analyzes 3,900 retail transactions to understand how customers shop across demographics, product categories, and channels. The goal is to uncover spending patterns, segments, and product preferences and turn them into clear business recommendations for sales, marketing, and loyalty strategy. 

Customer Shopping Behavior Anal…

Dataset 📁

Rows: 3,900

Columns: 18

Main features:

Customer demographics: age, gender, location, subscription status

Purchase details: item, category, amount, season, size, color

Behavior: discount applied, previous purchases, frequency, review rating, shipping type

Data quality: 37 missing values in review_rating, handled during cleaning. 

Customer Shopping Behavior Anal…

Tools 🧰

Python: pandas(EDA, cleaning, feature engineering)

Database: MySQL (SQL analysis and business queries)

Visualization: Tableau (interactive dashboard)

Deliverables: analytical notebook, SQL scripts, Tableau dashboard, business recommendations. 

Customer Shopping Behavior Anal…

Steps 🔍

Python EDA & Cleaning

Loaded data with pandas, checked structure with info() / describe().

Imputed missing review_rating values using median rating per product category.

Standardized column names (snake_case) and created features like age_group and purchase_frequency_days.

Removed redundant promo_code_used after consistency checks. 

Customer Shopping Behavior Anal…

SQL Analysis in PostgreSQL
Loaded the cleaned DataFrame into PostgreSQL and wrote SQL queries to answer key business questions, including:

Revenue by gender and age group

High-spending discount users

Top-rated products and top products per category

Shipping type comparison (Standard vs Express)

Subscribers vs non-subscribers, repeat buyers, and loyalty segments (New / Returning / Loyal)

Discount-dependent products and subscription likelihood for frequent buyers. 

Customer Shopping Behavior Anal…

Visualization & Storytelling

Built a Tableau dashboard to explore KPIs, trends, and segments.

Summarized insights and actions in a concise report / presentation for business stakeholders. 

Customer Shopping Behavior Anal…

Dashboard 📈

The Tableau dashboard provides:

Overall revenue and key KPIs

Breakdown by gender, age group, subscription status, shipping type, and product category

Views to explore top products, discount usage, and customer segments interactively. 

Customer Shopping Behavior Anal…

Result & Recommendations ✅

From the analysis, the project suggests how the retailer can: 

Customer Shopping Behavior Anal…

Boost subscriptions by promoting exclusive benefits.

Strengthen loyalty with rewards for repeat buyers to grow the “Loyal” segment.

Optimize discounts to drive sales while protecting margins.

Highlight top-rated and best-selling products in marketing campaigns.

Target high-value segments (e.g., profitable age groups and express-shipping users) with focused marketing.

How to Run ▶️

Clone the repository

git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis


Set up Python environment

python -m venv venv
# activate the venv (Windows / macOS / Linux)
pip install -r requirements.txt


Configure MySQL

Start MySQL Workbench and create a schema, e.g. customer_behavior_db.

Update the connection settings (host, db, user, password) in the notebook or config file.

Run the Python script / notebook to load the cleaned data into PostgreSQL.

Run the analysis

Open notebooks/customer_shopping_behavior_analysis.ipynb.

Run the cells in order: load → EDA → cleaning → feature engineering → load to PostgreSQL → SQL queries.

Open the Tableau dashboard

Open tableau/customer_shopping_behavior_dashboard.twbx in Tableau.

If needed, update the data source to point to your PostgreSQL instance.

And you’re set to explore customer shopping behavior and business insights 🚀
