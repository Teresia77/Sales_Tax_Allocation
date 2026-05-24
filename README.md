# Sales Tax Allocation Analysis (County, MTA, SPD)

## Overview
This project analyzes sales tax allocation patterns across different jurisdiction types, including Counties, Metropolitan Transit Authorities (MTA), and Special Purpose Districts (SPD). The objective is to examine how tax revenues are distributed over time, identify trends, detect anomalies, and generate actionable insights for policy and financial planning.

The analysis is conducted using Python with a focus on data cleaning, exploratory data analysis, time-series aggregation, and visualization.

---

## Objectives
- Analyze sales tax distribution across jurisdiction types
- Identify temporal trends in tax allocations
- Detect outliers and irregular payment patterns
- Compare performance across Counties, MTAs, and SPDs
- Generate business insights for budgeting and policy decisions

---

## Dataset
The dataset consists of administrative tax allocation records with the following key variables:

### Key Fields
- `Name` – Jurisdiction name
- `Type` – County, MTA, or SPD
- `Current Rate` – Sales tax rate
- `Payments To Date` – Total payments received
- `Comparable Payment Prior Year` – Year-over-year comparison
- `Percent Change From Prior Year` – Growth indicator
- `Percent Change To Date` – Cumulative growth
- `Report Month`, `Report Year` – Time indicators
- `Report Period Type` – Monthly or annual reporting classification

---

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter / Spyder
- Time Series Aggregation
- Data Cleaning & Preprocessing

---

## Data Processing Workflow

### 1. Data Cleaning
- Checked missing values using `.isnull().sum()`
- Handled missing data where necessary
- Verified data types and structure

### 2. Feature Engineering
- Created time-based variables (Year, Month, Quarter)
- Constructed pivot tables for aggregation
- Grouped data by jurisdiction type

### 3. Exploratory Analysis
- Descriptive statistics (mean, median, std, min, max)
- Distribution analysis of payments
- Identification of seasonal trends

---

## Key Analyses Performed

### 1. Jurisdiction Comparison
- Compared total and average payments across:
  - Counties
  - MTAs
  - SPDs

---

### 2. Time-Series Trends
- Quarterly aggregation of payments
- Yearly evolution of tax allocations
- Monthly seasonal patterns

---

### 3. Outlier Detection
- Scatter plots and boxplots used to detect:
  - Unusual payment spikes
  - Reporting anomalies
  - Economic or policy-driven irregularities

---

## Key Insights

- Counties consistently receive the largest share of total tax allocations
- MTAs and SPDs receive significantly smaller but stable distributions
- Clear seasonal patterns emerge in monthly and quarterly trends
- Q4 periods often show increased allocation activity
- Growth rates fluctuate, suggesting influence from policy and economic cycles
- Outliers indicate potential reporting anomalies or special fiscal events

---

## Visualizations

The project includes the following key visual analyses:

- Total Payments by Jurisdiction Type
- Ranking of Allocations (County vs MTA vs SPD)
- Average Payments Comparison
- Quarterly and Yearly Evolution Trends
- Monthly Seasonal Patterns
- Outlier Detection (Boxplots & Scatterplots)
- Distribution Analysis (Histograms)

---

## Business Recommendations

### 1. Seasonal Budget Planning
Allocate resources based on predictable seasonal peaks (especially Q4 trends).

### 2. Equity in Allocation Review
Evaluate funding disparities between Counties, MTAs, and SPDs.

### 3. Policy Impact Monitoring
Track percent-change indicators to assess effects of fiscal policy shifts.

### 4. Data Quality Improvements
Standardize reporting to reduce missing values and outliers.

### 5. Forecasting Opportunities
Use historical trends for predictive modeling of future tax allocations.

---

## Key Skills Demonstrated
- Data Cleaning & Wrangling
- Exploratory Data Analysis (EDA)
- Time-Series Aggregation
- Data Visualization
- Business Insight Generation
- Statistical Summary Analysis
- Outlier Detection

---

## Repository Structure
```text
sales-tax-allocation/
│
├── data/
├── visuals/
├── notebooks/
├── reports/
├── sales_tax_allocation.csv
├── README.md
```

---

## Author
Teresia Wainaina
