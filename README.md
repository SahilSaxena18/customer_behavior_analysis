# customer_behavior_analysis
# Data Analytics Project

## Overview

This project demonstrates an end-to-end data analytics workflow, starting from data extraction and exploration to business insights visualization and reporting. The project involves data cleaning, exploratory data analysis (EDA), SQL-based analysis using PostgreSQL, dashboard development in Power BI, and presentation of findings through a report and presentation deck.

---

## Dataset

The dataset used in this project contains business-related information that was analyzed to identify trends, patterns, and actionable insights.

**Dataset Features:**

* Multiple records and attributes
* Structured tabular format
* Suitable for data cleaning, analysis, and visualization

---

## Tools & Technologies

| Tool                 | Purpose                             |
| -------------------- | ----------------------------------- |
| Python               | Data loading, cleaning, and EDA     |
| Pandas               | Data manipulation and preprocessing |
| NumPy                | Numerical operations                |
| Matplotlib / Seaborn | Data visualization                  |
| PostgreSQL           | Data storage and SQL analysis       |
| SQL                  | Querying and extracting insights    |
| Power BI             | Interactive dashboard creation      |
| Gamma                | Presentation (PPT) creation         |
| MS Word / PDF        | Report documentation                |

---

## Project Workflow

### 1. Data Loading

* Imported dataset using Python.
* Verified data structure and data types.
* Checked dataset dimensions and summary statistics.

### 2. Exploratory Data Analysis (EDA)

* Analyzed distributions and trends.
* Identified missing values and inconsistencies.
* Generated visualizations to understand key patterns.

### 3. Data Cleaning

* Handled missing values.
* Removed duplicate records.
* Corrected data formats and standardized fields.
* Prepared data for further analysis.

### 4. SQL Analysis (PostgreSQL)

* Imported cleaned data into PostgreSQL.
* Created and executed SQL queries.
* Performed aggregations, filtering, and business analysis.
* Extracted key metrics and insights.

### 5. Power BI Dashboard

* Connected PostgreSQL data to Power BI.
* Created interactive visualizations.
* Designed KPI cards, charts, and filters.
* Built a user-friendly dashboard for decision-making.

### 6. Reporting & Presentation

* Documented methodology and findings.
* Prepared a business report summarizing insights.
* Created a professional presentation using Gamma.

---

## Dashboard Highlights

The Power BI dashboard includes:

* Key Performance Indicators (KPIs)
* Trend Analysis
* Category-wise Performance
* Interactive Filters and Slicers
* Summary Insights for Business Decision-Making

---

## Key Results

Some of the major outcomes from the analysis include:

* Identification of important business trends.
* Discovery of high-performing and low-performing segments.
* Data-driven recommendations for improvement.
* Interactive dashboard enabling easy monitoring of performance metrics.

---

## Project Structure

```text
Data-Analytics-Project/
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   ├── customer_behavior_shopping_analysis.ipynb
│   └── customer_behavior_shopping_analysis.ipynb
│
├── SQL/
│   └── customer_behavior_sql_queries.sql
│
├── PowerBI/
│   └── customer_behavior_dashboard.pbix
│
├── Report/
│   └── customer behavior shopping analysis.pdf
│
├── Presentation/
│   └── customer-behavior-shopping-analysis.pdf
│
└── README.md
```

## How to Run

### Python Analysis

1. Install required libraries:

```bash
pip install psycopg2-binary sqlalchemy
```

2. Open Jupyter Notebook:

```bash
customer_behavior_shopping_analysis.ipynb jupyter notebook
```

3. Run the notebooks for EDA and data cleaning.

### PostgreSQL Analysis

1. Create a PostgreSQL database.
2. Import the cleaned dataset.
3. Execute the SQL queries from the `SQL` folder.

### Power BI Dashboard

1. Open the `customer_behavior_dashboard.pbix` file in Power BI Desktop.
2. Refresh data connections.
3. Explore the interactive dashboard.

---

## Conclusion

This project showcases practical skills in data analytics, including data preprocessing, exploratory analysis, SQL querying, dashboard development, and business reporting. It demonstrates the complete analytics lifecycle and the ability to convert raw data into meaningful business insights.
