

# Customer Behavior Analysis

An end-to-end data analytics project that explores retail customer shopping behavior using Python, SQL, and Power BI — covering everything from raw data cleaning to a final interactive dashboard and report.

This project was built by following a guided tutorial (credit: Amlan Mohanty) as a hands-on way to practice the full analytics workflow, from EDA to BI dashboarding.

---

## Overview

The goal of this project is to analyze customer shopping behavior to uncover patterns in spending, purchase frequency, product preferences, and customer segments. The workflow simulates a real-world data analyst task: take a raw dataset, clean and explore it, query it for business insights, and present findings through a dashboard and report that a non-technical stakeholder could understand.

## Dataset

- **File:** `customer_shopping_behavior.csv`
- **Size:** ~3,900 records
- **Description:** Retail transaction-level data including customer demographics (age, gender), purchase details (category, item, price, quantity), payment method, location, season, and customer loyalty indicators (subscription status, discount usage, previous purchases).

## Tools & Technologies

| Tool | Purpose |
|---|---|
| **Python** (Pandas, NumPy, Matplotlib/Seaborn) | Data loading, cleaning, and exploratory data analysis (EDA) |
| **SQL** (PostgreSQL / MySQL / SQL Server) | Querying the cleaned dataset for business insights |
| **Power BI** | Building an interactive dashboard to visualize key metrics |
| **Gamma** | Creating a presentation (PPT) to summarize findings |
| **PDF** | Final written report of the analysis |

## Steps

1. **Data Loading** – Imported the raw CSV into Python using Pandas.
2. **Exploratory Data Analysis (EDA)** – Examined data types, distributions, missing values, and summary statistics to understand the dataset.
3. **Data Cleaning** – Handled missing values, fixed inconsistent formatting, and prepared the dataset for analysis.
4. **SQL Analysis** – Loaded the cleaned data into a relational database and wrote SQL queries (`Customer_Behavior.sql`) to answer business questions such as top spending categories, purchase frequency by segment, and revenue trends.
5. **Dashboard Building** – Designed an interactive Power BI dashboard (`Customer_Behavior_Dashboard.pbix`) to visualize key metrics like total revenue, top categories, customer segments, and seasonal trends.
6. **Reporting** – Compiled the analysis and findings into a written report (`Customer Behavior Analysis.pdf`).
7. **Presentation** – Summarized the project and key insights into a slide deck using Gamma, for quick, recruiter-friendly consumption.

## Dashboard

The Power BI dashboard provides an interactive view of:
- Total revenue and average order value
- Purchase trends by category and season
- Customer segmentation (gender, age group, subscription status)
- Top-performing products and locations
- Discount and payment method usage patterns

> Open `Customer_Behavior_Dashboard.pbix` in Power BI Desktop to explore the dashboard interactively.

## Results

- Identified the top-performing product categories and seasonal demand shifts.
- Found clear differences in spending behavior between subscribed and non-subscribed customers.
- Highlighted the most-used payment methods and their relationship with purchase value.
- Surfaced actionable insights on customer segments most responsive to discounts.

*(Refer to `Customer Behavior Analysis.pdf` for the full write-up of insights and recommendations.)*

## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/sathwikkotyan/Customer_Behavior_Analysis.git
cd Customer_Behavior_Analysis
```

### 2. Python EDA & Cleaning
- Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn
```
- Load `customer_shopping_behavior.csv` in a Jupyter Notebook to run EDA and cleaning steps.

### 3. SQL Analysis
- Import `customer_shopping_behavior.csv` into PostgreSQL / MySQL / SQL Server.
- Run the queries in `Customer_Behavior.sql` to reproduce the analysis.

### 4. Power BI Dashboard
- Open `Customer_Behavior_Dashboard.pbix` in **Power BI Desktop**.
- Refresh the data source if prompted to point it to your local copy of the dataset.

### 5. Report & Presentation
- View `Customer Behavior Analysis.pdf` for the detailed report.

---

## Project Files

| File | Description |
|---|---|
| `customer_shopping_behavior.csv` | Raw dataset |
| `Customer_Behavior.sql` | SQL queries used for analysis |
| `Customer_Behavior_Dashboard.pbix` | Power BI dashboard file |
| `Customer Behavior Analysis.pdf` | Final analysis report |

---


## Dashboard


<img width="1398" height="817" alt="Screenshot 2026-06-17 164402" src="https://github.com/user-attachments/assets/6702449b-bcd1-49e4-8ec4-eca354776f77" />




## Acknowledgements

This project was completed as a guided learning exercise based on a tutorial by **Amlan Mohanty**, used to practice the end-to-end data analytics workflow.

## Author

**Sathwik Kotian**
Aspiring Data Analyst | Python · SQL · Power BI
