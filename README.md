# 🪔 Diwali Sales Analysis

## 📌 Overview

This project focuses on analyzing **Diwali sales data** to understand customer purchasing behavior, identify high-performing customer segments, and generate actionable business insights.

The analysis was performed using **Python, Pandas, NumPy, Matplotlib, and Seaborn**. The dataset was cleaned and explored through various demographic, geographic, occupational, and product-level analyses.

The primary objective is to identify **which customer segments and product categories contribute most to sales**, helping businesses improve marketing and sales strategies.

---

## 🎯 Business Objective

The main objective of this project is to answer questions such as:

* Who are the major buyers during the Diwali sales period?
* Which age group contributes the most to sales?
* Which states generate the highest sales?
* How does marital status relate to purchasing behavior?
* Which occupations have the highest number of buyers and sales?
* Which product categories are most popular?
* Which customer segment should businesses target for future campaigns?

---

## 📂 Dataset

The project uses the **Diwali Sales Data** dataset.

The dataset contains customer, order, demographic, geographic, occupational, and product information.

### Key attributes include:

* Gender
* Age Group
* State
* Marital Status
* Occupation
* Product Category
* Orders
* Amount

The dataset was loaded into a Pandas DataFrame and inspected before performing the analysis.

---

## 🛠️ Tools & Technologies

| Tool / Technology    | Purpose                        |
| -------------------- | ------------------------------ |
| **Python**           | Data analysis                  |
| **Pandas**           | Data manipulation and cleaning |
| **NumPy**            | Numerical operations           |
| **Matplotlib**       | Data visualization             |
| **Seaborn**          | Statistical visualization      |
| **Jupyter Notebook** | Analysis environment           |

---

## 🔄 Project Workflow

```text
Raw Diwali Sales Dataset
          ↓
     Data Loading
          ↓
   Data Exploration
          ↓
     Data Cleaning
          ↓
Exploratory Data Analysis
          ↓
 Customer Segmentation
          ↓
   Sales Analysis
          ↓
 Business Insights
          ↓
    Conclusion
```

---

## 🔍 Data Cleaning & Preprocessing

The dataset was inspected and cleaned before performing the analysis.

### Steps performed:

* Checked the dataset dimensions and columns
* Examined data types and statistical summaries
* Checked for duplicate records
* Removed duplicate records
* Checked for missing/null values
* Removed unnecessary columns such as `Status` and `unnamed1`
* Removed rows containing missing values
* Prepared the cleaned dataset for exploratory analysis

Example:

```python
df.drop_duplicates(inplace=True)

df.drop(["Status", "unnamed1"], axis=1, inplace=True)

df.dropna(inplace=True)
```

---

## 📊 Exploratory Data Analysis

The analysis focused on understanding customer demographics and purchasing patterns.

### 1. Gender Analysis

The analysis compares the number of male and female buyers and their total spending.

**Key finding:** Female customers represent the majority of buyers and contribute higher purchasing amounts compared with male customers.

---

### 2. Age Group Analysis

Customer purchasing behavior was analyzed across different age groups.

**Key finding:** Customers in the **26–35 age group** represent the largest buyer segment, with female customers particularly prominent in this group.

---

### 3. State-wise Analysis

The project analyzed both the number of orders and total sales generated across different states.

**Key finding:** **Uttar Pradesh, Maharashtra, and Karnataka** are among the leading states in terms of orders and total sales.

---

### 4. Marital Status Analysis

Customer count and total sales were analyzed based on marital status and gender.

**Key finding:** Married customers, particularly women, demonstrate strong purchasing power in the dataset.

---

### 5. Occupation Analysis

The project examines customer distribution and total spending across different occupations.

**Key finding:** Customers working in sectors such as **IT, Healthcare, and Aviation** represent important buyer segments.

---

### 6. Product Category Analysis

Product categories were analyzed based on the number of products sold and total sales generated.

**Key finding:** **Food, Clothing & Apparel, and Electronics & Gadgets** are among the leading product categories.

---

## 📈 Key Insights

The analysis identified the following major customer characteristics:

* Female customers form the largest buyer segment.
* The **26–35 age group** represents a major portion of buyers.
* **Uttar Pradesh, Maharashtra, and Karnataka** are key states in terms of orders and sales.
* Married women demonstrate strong purchasing power.
* Customers working in **IT, Healthcare, and Aviation** are important buyer segments.
* **Food, Clothing & Apparel, and Electronics & Gadgets** are high-performing product categories.

---

## 💡 Business Recommendations

Based on the analysis, businesses can consider the following strategies:

1. **Target women customers** with personalized Diwali campaigns and promotional offers.
2. Focus marketing campaigns on the **26–35 age group**.
3. Increase promotional activities in high-performing states such as **Uttar Pradesh, Maharashtra, and Karnataka**.
4. Develop targeted campaigns for customers working in **IT, Healthcare, and Aviation**.
5. Promote high-demand categories such as **Food, Clothing & Apparel, and Electronics & Gadgets**.
6. Use customer demographics to develop more personalized marketing campaigns.

---

## 📊 Visualizations

The project includes multiple visualizations created using **Matplotlib and Seaborn**, including:

* Gender-wise customer count
* Gender-wise total spending
* Age group and gender analysis
* Age group-wise sales
* Top 10 states by orders
* Top 10 states by sales
* Marital status and gender analysis
* Marital status-wise sales
* Occupation-wise customer count
* Occupation-wise sales
* Product category-wise sales
* Product category-wise product count

These visualizations help convert raw sales data into easily interpretable business insights.

---

## 🏁 Conclusion

The analysis indicates that **married women aged 26–35 years**, particularly those from **Uttar Pradesh, Maharashtra, and Karnataka** and working in sectors such as **IT, Healthcare, and Aviation**, represent an important customer segment.

The findings also show strong demand for **Food, Clothing & Apparel, and Electronics & Gadgets**.

These insights can help businesses improve their **customer targeting, promotional campaigns, product planning, and sales strategies** during future festive seasons.

---

## 📁 Project Structure

```text
Diwali-Sales-Analysis/
│
├── data/
│   └── Diwali_Sales_Data.csv
│
├── notebooks/
│   └── Diwali_Sales_Analysis.ipynb
│
├── images/
│   └── charts/
│
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Diwali-Sales-Analysis.git
cd Diwali-Sales-Analysis
```

### 2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the notebook

Open:

```text
Diwali_Sales_Analysis.ipynb
```

Run the cells sequentially to reproduce the analysis.

---

## 🎓 Skills Demonstrated

This project demonstrates practical skills in:

* **Python**
* **Pandas**
* **NumPy**
* **Data Cleaning**
* **Exploratory Data Analysis (EDA)**
* **Data Visualization**
* **Customer Segmentation**
* **Sales Analysis**
* **Business Insights**
* **Business Recommendations**

---

## 👤 Author

**Somnath Mukherjee**

Aspiring Data Analyst
**Python | SQL | Excel | Power BI | Data Analytics**

---

## ⭐ Project Highlights

> **Raw Data → Data Cleaning → EDA → Visualization → Business Insights → Recommendations**

This project demonstrates the ability to transform a raw sales dataset into **meaningful business insights using Python-based data analytics**.
