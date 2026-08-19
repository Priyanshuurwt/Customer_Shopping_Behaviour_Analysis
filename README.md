# Customer Shopping Behavior Analysis

## Overview

This project demonstrates an end-to-end **Data Analytics workflow**, starting from raw data and progressing through data cleaning, exploratory analysis, SQL analysis, visualization, and reporting.

The project includes:

- Loading and analyzing a dataset using Python
- Performing Exploratory Data Analysis (EDA)
- Cleaning and preprocessing the data
- Performing analytical queries using MySQL
- Building an interactive Power BI dashboard
- Creating a detailed project report
- Creating a presentation using Gamma AI

The main objective is to transform raw data into meaningful insights that can support data-driven decision-making.

---

## Dataset

The project uses a structured dataset containing **[briefly describe your dataset]**.

The dataset was initially loaded into Python to understand its structure, quality, and key characteristics.

The analysis included:

- Number of rows and columns
- Data types
- Missing values
- Duplicate records
- Unique values
- Statistical summary
- Outlier identification
- Relationships between variables

**Dataset:** `dataset.csv`

---

## Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Python | Data loading, EDA, and data cleaning |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| MySQL | SQL-based data analysis |
| Power BI | Interactive dashboard and visualization |
| Gamma AI | Presentation creation |
| Jupyter Notebook | Python-based analysis |

---

## Project Workflow

### 1. Data Loading

The dataset was loaded into Python using **Pandas**.

The initial analysis was performed to understand:

- Dataset dimensions
- Column names
- Data types
- Missing values
- Duplicate records
- Basic statistics

---

### 2. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to identify patterns, trends, relationships, and anomalies within the dataset.

Key activities included:

- Descriptive statistics
- Frequency analysis
- Distribution analysis
- Correlation analysis
- Identifying trends
- Identifying outliers
- Creating visualizations

---

### 3. Data Cleaning

The raw dataset was cleaned and prepared for further analysis.

The cleaning process included:

- Handling missing values
- Removing duplicate records
- Correcting inconsistent values
- Converting data types
- Standardizing categorical values
- Handling outliers where required
- Preparing the final dataset for SQL analysis

The cleaned dataset was then used for further analysis.

---

### 4. SQL Analysis using MySQL

The cleaned dataset was imported into **MySQL Server** for structured data analysis.

SQL queries were used to perform tasks such as:

- Filtering and sorting data
- Aggregation using `GROUP BY`
- Filtering aggregated results using `HAVING`
- Using different types of `JOIN`
- Calculating KPIs
- Finding top-performing categories/products
- Ranking records
- Analyzing trends
- Comparing different segments

The SQL analysis helped extract additional business insights from the dataset.

---

### 5. Power BI Dashboard

The analyzed data was used to create an interactive **Power BI dashboard**.

The dashboard includes:

- Key Performance Indicators (KPIs)
- Charts and graphs
- Category-wise analysis
- Trend analysis
- Tables
- Filters and slicers
- Interactive visualizations

The dashboard provides a quick and user-friendly overview of the major insights obtained from the analysis.

---

## Dashboard

### Power BI Dashboard Preview

> Add your Power BI dashboard screenshot here.

**Power BI File:** `dashboard.pbix`

The dashboard allows users to interact with the data using filters and slicers and explore different aspects of the analysis.

---

## Results & Key Insights

The analysis helped identify several important patterns and insights from the dataset.

Some of the key findings include:

- Identified major performance trends
- Identified top-performing categories/products
- Analyzed customer or transaction patterns
- Identified important KPIs
- Compared performance across different segments
- Identified areas of strong and weak performance
- Extracted actionable insights from the data

> **Note:** Replace the points above with the actual findings from your project.

---

## Project Structure

```text
Data-Analytics-Project/
│
├── dataset/
│   └── customer_shopping_behavior_Dataset.csv
│
├── python/
│   └── customer_shop_behav.ipynb
│
├── sql/
│   └── Costomer_beha_sqlqueries.sql
│
├── powerbi/
│   └── Customer_behav_Dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
└── README.md
