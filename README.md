Customer Behavior & Sales Analytics

An end-to-end data analytics project covering data ingestion and cleaning in Python, exploratory data analysis (EDA), relational querying in SQL, interactive visualization in Tableau, and executive storytelling via a written report and Gamma presentation.

Overview

This project analyzes customer purchasing patterns, subscription behavior, and review trends to uncover actionable insights for retention and revenue growth. The goal is to transform raw transactional data into a clean analytical dataset, answer core business questions with SQL, and present findings through an interactive Tableau dashboard and stakeholder deck.

Dataset

Source: Customer export dataset (customer export.csv — replace with your exact dataset source or filename).
Granularity: Customer / transaction-level records covering demographics, subscription status, purchase amounts, frequency, categories, and review ratings.
Key Fields: Customer ID, Age, Gender, Category, Purchase Amount, Subscription Status, Purchase Frequency, and Review Rating.

Tools & Technologies

Python: pandas, SQLAlchemy, Jupyter Notebook / VS Code
Databases & SQL: PostgreSQL, MySQL, SQL Server
Business Intelligence: Tableau (Tableau Public / Tableau Desktop)
Documentation & Presentation: Markdown / Word / PDF (Summary Report), Gamma (Presentation Deck)

Project Workflow & Steps

1. Data Loading & Initial Inspection (Python): Loaded the raw dataset into a Jupyter Notebook using pandas and audited schema types, row counts, summary statistics, and missing values.
2. Exploratory Data Analysis (EDA): Examined distributions, outliers, category breakdowns, and relationships between subscription status, spend, and customer ratings.
3. Data Cleaning & Transformation: Handled missing/null values, standardized column names and data types, removed duplicate entries, and derived clean analytical features before loading into SQL.
4. SQL Querying & Analysis: Loaded the cleaned table into PostgreSQL / MySQL / SQL Server (via SQLAlchemy or database import tools) and wrote SQL queries using aggregations, GROUP BY, CASE WHEN, CTEs, and window functions to calculate segment KPIs and conversion/retention splits.
5. Tableau Dashboard: Connected Tableau to the cleaned dataset/database, configured calculated fields, table calculations, custom number formatting, and labels, and built an interactive dashboard with filters and tooltips.
6. Report & Gamma Presentation: Summarized methodology, key findings, and business recommendations in a structured report, and built a concise slide deck in Gamma for non-technical stakeholders.

Dashboard

The Tableau workbook (dashboard/customer behavior dashboard.twbx or your Tableau Public link) highlights:
Executive KPIs: Customer count, average purchase amount, subscription split, and review rating metrics.
Segment Breakdowns: Performance across subscription status (Yes / No), product categories, customer demographics, and purchasing frequency.
Interactive Filtering & Labels: Direct data labels, formatted percentages, and interactive filters/tooltips for exploring segment trends.

(Add screenshots of your Tableau worksheets/dashboard under assets/ and link them here.)

Key Results & Insights

Subscription Impact: Quantified differences in spending and engagement between subscribed and non-subscribed customers.
Category & Rating Drivers: Identified top-performing categories and segments with higher or lower review ratings to guide targeted promotions.
Actionable Recommendations: Highlighted practical steps for improving repeat purchases and subscription conversion based on segment behavior.
