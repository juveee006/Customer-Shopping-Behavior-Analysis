# Customer Shopping Behavior Analysis

## Project Overview

This project focuses on analyzing customer shopping behavior data using Python, MySQL, and Data Visualization tools. The objective of the project is to clean raw shopping data, perform exploratory data analysis (EDA), store processed data in a MySQL database, and create interactive dashboards to generate meaningful business insights.

This is an end-to-end Data Analytics project covering:

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Database Integration
- Exploratory Data Analysis (EDA)
- Dashboard Creation
- Business Insight Generation

---

# Technologies Used

- Python
- Pandas
- PyMySQL
- SQLAlchemy
- MySQL
- CSV Dataset
- Power BI / Tableau / Excel (Dashboard)

---

# Project Workflow

## 1. Database Creation

A MySQL database named `shopping_db` was created using PyMySQL.

## 2. Data Loading

The dataset `customer_shopping_behavior.csv` was loaded into a Pandas DataFrame.

## 3. Data Cleaning

The following preprocessing steps were performed:

- Handled missing values in `Review Rating`
- Standardized column names
- Renamed inconsistent columns
- Removed redundant columns
- Checked null values and duplicates

## 4. Feature Engineering

Additional features were created:

- `age_group`
- `purchase_frequency_days`

These features improved the analytical capability of the dataset.

## 5. MySQL Integration

The cleaned data was inserted into a MySQL database table for SQL-based analysis and storage.

## 6. Exploratory Data Analysis (EDA)

Analysis was performed on:

- Customer age groups
- Purchase behavior
- Product categories
- Discounts and promo usage
- Review ratings
- Payment methods
- Purchase frequency

## 7. Dashboard Creation

An interactive dashboard was created to visualize:

- Total Sales
- Category-wise Purchases
- Customer Segmentation
- Review Ratings
- Purchase Frequency
- Gender Distribution
- Discount Usage

---

# Dataset Information

Dataset Name:

`customer_shopping_behavior.csv`

The dataset contains customer shopping details such as:

- Age
- Gender
- Category
- Purchase Amount
- Review Ratings
- Discounts
- Payment Methods
- Subscription Status
- Purchase Frequency

---

# Key Features

- End-to-End Data Analysis Project
- Data Cleaning & Transformation
- SQL Database Integration
- Feature Engineering
- Dashboard Visualization
- Business Insights Generation

---

# Project Structure

```bash
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.csv
├── customer_shopping_cleaned.csv
├── shopping_analysis.py
├── dashboard/
├── screenshots/
├── README.md
└── project_report.docx
