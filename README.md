# 📊 Data Analytics Project

## Overview

This project demonstrates an end-to-end **data analytics workflow**, starting from data loading and exploratory analysis in Python to SQL-based analysis, Power BI dashboard development, and business reporting.

The objective is to transform raw data into meaningful insights that can support **data-driven business decisions**.

### Key Areas Covered

* Data loading and exploration using Python
* Exploratory Data Analysis (EDA)
* Data cleaning and preprocessing
* SQL analysis using MySQL
* Interactive dashboard development using Power BI
* Business insights and recommendations
* Final analytical report

---

## 📁 Dataset

The project uses a structured dataset containing relevant business/customer/transaction-level information.

The dataset was first loaded into Python for understanding its:

* Structure and dimensions
* Data types
* Missing values
* Duplicate records
* Outliers
* Numerical and categorical variables

---

## 🛠️ Tools & Technologies

| Tool                     | Purpose                                   |
| ------------------------ | ----------------------------------------- |
| **Python**               | Data loading, cleaning and EDA            |
| **Pandas**               | Data manipulation and preprocessing       |
| **NumPy**                | Numerical analysis                        |
| **Matplotlib / Seaborn** | Data visualization                        |
| **MySQL**                | SQL-based data analysis                   |
| **Power BI**             | Interactive dashboard                     |
| **Excel / CSV**          | Data storage and initial inspection       |
| **Jupyter Notebook**     | Python-based analysis                     |
| **GitHub**               | Project documentation and version control |

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Load Data in Python
     ↓
Data Exploration
     ↓
Data Cleaning & Preprocessing
     ↓
Exploratory Data Analysis
     ↓
Load Data into MySQL
     ↓
SQL Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights
     ↓
Final Report & Recommendations
```

---

## 🚀 Steps Performed

### 1. Data Loading

The dataset was imported into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")

print(df.head())
print(df.shape)
print(df.info())
```

The initial analysis focused on understanding the dataset structure and identifying potential data-quality issues.

---

### 2. Exploratory Data Analysis

EDA was performed to identify patterns, trends, distributions and relationships within the data.

Key activities included:

* Checking dataset dimensions
* Examining data types
* Descriptive statistics
* Analyzing categorical variables
* Analyzing numerical variables
* Identifying trends and patterns
* Creating visualizations
* Detecting potential outliers

---

### 3. Data Cleaning

The dataset was cleaned and prepared for further analysis.

Major preprocessing steps included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing column values
* Handling inconsistent data
* Creating required calculated columns
* Checking for outliers where appropriate

The cleaned dataset was then used for SQL analysis and dashboard development.

---

### 4. MySQL Analysis

The cleaned data was imported into **MySQL Server** for structured querying and analysis.

SQL queries were used to answer important business questions such as:

* What are the top-performing categories/products?
* Which customers or regions generate the most revenue?
* What are the monthly/annual sales trends?
* Which segments have the highest performance?
* What factors are associated with higher sales?
* Which areas require business attention?

Example:

```sql
SELECT
    category,
    SUM(sales_amount) AS total_sales
FROM sales
GROUP BY category
ORDER BY total_sales DESC;
```

SQL concepts used include:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* Aggregate functions
* `JOIN`
* Subqueries
* Window functions

---

## 📊 Power BI Dashboard

An interactive Power BI dashboard was developed to present the key findings in an easy-to-understand format.

### Dashboard Components

The dashboard includes relevant KPIs, charts and filters such as:

* Total Sales
* Total Customers
* Number of Orders
* Average Order Value
* Sales by Category
* Sales by Region
* Monthly/Yearly Trends
* Top-performing Products
* Customer/Business Segments

### Dashboard Features

* Interactive filters and slicers
* KPI cards
* Bar and column charts
* Line charts
* Category/segment analysis
* Trend analysis
* Drill-down where applicable

> 📌 **Add your Power BI dashboard screenshot here**

```markdown
![Power BI Dashboard](images/dashboard.png)
```

---

## 📈 Results & Key Insights

The analysis generated several actionable business insights from the dataset.

Examples of insights identified through the analysis include:

* High-performing categories/products contributed significantly to overall revenue.
* Certain customer or regional segments showed stronger performance than others.
* Sales trends revealed periods of higher and lower business activity.
* Underperforming segments were identified for further investigation.
* Customer and product-level analysis helped identify opportunities for improving business performance.

The insights were converted into **business recommendations** rather than focusing only on descriptive statistics.

---

## 💡 Business Recommendations

Based on the analysis, potential recommendations include:

1. Focus marketing efforts on high-performing products and customer segments.
2. Investigate underperforming categories and regions.
3. Use customer-level insights to improve retention and engagement.
4. Monitor sales trends to improve planning and forecasting.
5. Use dashboard KPIs for regular performance monitoring.
6. Make data-driven decisions using insights from Python, SQL and Power BI.

---

## 📄 Final Report

A detailed report was prepared to document the complete analytical process.

The report covers:

* Business problem
* Dataset description
* Data preparation
* Exploratory analysis
* SQL analysis
* Power BI dashboard
* Key findings
* Business insights
* Recommendations
* Conclusion

> 📌 **Add your final report here:** `reports/Project_Report.pdf`

---

## ▶️ How to Run

### Prerequisites

Install the following:

* Python 3.x
* Jupyter Notebook
* MySQL Server
* Power BI Desktop

### Python Setup

Clone the repository:

```bash
git clone https://github.com/yourusername/your-repository.git
cd your-repository
```

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook containing the data loading, cleaning and EDA steps.

### MySQL

1. Start MySQL Server.
2. Create the required database.
3. Import the cleaned dataset.
4. Run the SQL queries provided in the `sql/` folder.

Example:

```sql
CREATE DATABASE analytics_project;
USE analytics_project;
```

### Power BI

1. Open the `.pbix` file using Power BI Desktop.
2. Update the data source if required.
3. Refresh the dataset.
4. Explore the interactive dashboard.

---

## 📂 Project Structure

```text
data-analytics-project/
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── notebooks/
│   └── data_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── analytics_dashboard.pbix
│
├── reports/
│   └── Project_Report.pdf
│
├── images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

---

## 🎯 Skills Demonstrated

This project demonstrates practical experience in:

* **Python**
* **Pandas**
* **Data Cleaning**
* **Exploratory Data Analysis**
* **Data Visualization**
* **SQL**
* **MySQL**
* **Power BI**
* **Business Intelligence**
* **KPI Analysis**
* **Business Reporting**
* **Data-driven Decision Making**

---

## 👤 Author

**Somnath Mukherjee**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

This project demonstrates my ability to work with data across the complete analytics lifecycle — from **raw data to actionable business insights**.

