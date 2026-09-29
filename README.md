
# Superstore Python Data Analysis

## 📊 Project Overview

An end-to-end retail data analysis project built with Python to analyze sales performance, profitability, customer behavior, product performance, regional performance, shipping operations, and discount impact.

The project follows a complete Data Analyst workflow, starting from raw data inspection and advanced data cleaning and continuing through feature engineering, exploratory data analysis, statistical analysis, data visualization, automated KPI generation, reporting, and memory optimization.

---

## 🎯 Business Problem

A multinational retail company wants an automated analytical solution to monitor:

- Sales performance
- Profitability
- Customer behavior
- Product performance
- Regional performance
- Shipping efficiency
- Discount impact

The objective is to transform raw transactional data into meaningful business insights that can support data-driven decision-making.

---

## ⚠️ Dataset Disclaimer

The dataset used in this project is a sample retail dataset intended for educational and analytical purposes.

It does not represent confidential or proprietary data from a real company.

The business scenario, analytical workflow, KPIs, visualizations, and insights were developed as part of an independent Data Analyst portfolio project to demonstrate practical data analysis skills using Python.

---

## 🚀 Project Objectives

The project aims to:

- Import and inspect the dataset using Pandas
- Perform advanced data cleaning
- Validate missing values, duplicates, formats, numerical values, and dates
- Detect and investigate statistical outliers
- Develop reusable preprocessing functions
- Engineer business-oriented features
- Perform advanced exploratory data analysis
- Conduct statistical and correlation analysis
- Create professional data visualizations
- Generate automated KPI summaries
- Automatically export analytical outputs
- Generate an automated analytical report
- Optimize DataFrame memory usage
- Perform final validation

---

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- Pathlib

---

## 📁 Project Structure

```text
Superstore-Python-Data-Analysis/
│
├── data/
│   └── Sample - Superstore 2019.xls
│
├── documentation/
│   └── documentation/Documentation.docx
│
├── notebooks/
│   └── Superstore_Analysis.ipynb
│
├── outputs/
│   ├── cleaned_superstore.csv
│   ├── kpi_summary.csv
│   ├── region_performance.csv
│   ├── top_customers.csv
│   ├── top_products.csv
│   ├── yearly_sales.csv
│   ├── yearly_profit.csv
│   ├── monthly_sales.csv
│   ├── category_profitability.csv
│   ├── shipping_analysis.csv
│   ├── superstore_business_report.txt
│   │
│   └── visualizations/
│       ├── correlation_heatmap.png
│       ├── sales_by_category.png
│       ├── monthly_sales_trend.png
│       ├── sales_vs_profit.png
│       ├── regional_sales_vs_profit.png
│       ├── top_10_products.png
│       ├── discount_vs_profit.png
│       └── profit_margin_by_category.png
│
├── .gitignore
└── README.md
```

---

## 🔄 Data Analyst Workflow

The project follows a structured end-to-end Data Analyst workflow:

**Data Loading**  
→ **Initial Inspection**  
→ **Advanced Data Cleaning**  
→ **Data Quality Validation**  
→ **Outlier Detection & Investigation**  
→ **Feature Engineering**  
→ **Exploratory Data Analysis**  
→ **Statistical Analysis**  
→ **Data Visualization**  
→ **Automated KPI Generation**  
→ **Automatic Export**  
→ **Automated Analytical Reporting**  
→ **Memory Optimization**  
→ **Final Validation**

---

## 🧹 Advanced Data Cleaning

The dataset was subjected to a comprehensive data quality validation and cleaning process.

### Data Quality Checks

- Missing-value analysis
- Duplicate validation
- Data type correction
- Format validation
- Numerical validation
- Date validation
- Business-rule validation

The objective was to improve data quality while preserving valid business information.

Negative profit values were retained because they represent legitimate business losses rather than invalid records.

---

## 📌 Outlier Detection

Outliers were identified using the Interquartile Range (IQR) method.

The analysis focused on identifying unusual observations in important numerical variables such as:

- Sales
- Quantity
- Discount
- Profit

The detected outliers were **not automatically removed**.

This approach was chosen because an extreme observation may represent a legitimate business transaction and should therefore be investigated rather than removed automatically.

---

## ⚙️ Feature Engineering

Several business-oriented features were created to improve the analytical capabilities of the dataset:

- `Profit Margin`
- `Shipping Duration`
- `Sales Performance Category`
- `Year`
- `Month`
- `Month Name`
- `Quarter`

These engineered features support profitability analysis, operational analysis, customer and product evaluation, and time-based trend analysis.

---

## 📈 Key Performance Indicators

The project includes an automated KPI generation process designed to summarize the overall business performance.

Key KPIs include:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Overall Profit Margin
- Average Order Value
- Average Shipping Duration

The KPI summary is automatically exported as:

```text
outputs/kpi_summary.csv
```

---

## 📊 Exploratory & Statistical Analysis

The exploratory analysis investigates the major dimensions of the retail business, including:

- Sales performance
- Profitability
- Category performance
- Regional performance
- Customer performance
- Product performance
- Shipping performance
- Discount impact
- Time-based trends

The statistical analysis includes:

- Descriptive statistics
- Correlation analysis
- Distribution analysis
- Trend analysis
- Relationship analysis between key numerical variables

The analysis combines statistical findings with business interpretation to identify meaningful patterns and support data-driven decision-making.

---

## 💡 Key Business Insights

The analysis focuses on identifying business-relevant insights rather than simply presenting charts.

### Sales & Profitability

The analysis compares revenue generation against actual profitability to identify areas where strong sales do not necessarily translate into strong profit.

### Category Performance

Category-level analysis helps identify the strongest and weakest product categories based on sales and profitability.

### Regional Performance

Regional analysis evaluates differences in sales and profit across geographical markets.

### Customer Performance

Customer-level analysis identifies high-value customers and evaluates whether high revenue is accompanied by healthy profitability.

### Discount Impact

The relationship between discounts and profitability was investigated to understand their impact on profit margins.

### Time-Based Performance

Sales and profit trends were analyzed across time to identify growth patterns and changes in business performance.

---

## 📉 Statistical Findings

Correlation analysis was performed to investigate relationships between important numerical variables.

The analysis includes relationships between:

- Sales and Profit
- Discount and Profit
- Discount and Profit Margin
- Sales and Quantity

Correlation results were interpreted as statistical associations and were not treated as evidence of causation.

---

## 📦 Category Performance

Category-level analysis was performed to compare sales and profitability.

The analysis evaluates:

- Total Sales by Category
- Total Profit by Category
- Profit Margin by Category
- Relative category performance

This analysis helps identify categories that generate strong revenue as well as categories where profitability requires further attention.

---

## 🚚 Shipping Performance

Shipping performance was analyzed using the engineered `Shipping Duration` feature.

The analysis evaluates:

- Average shipping duration
- Shipping duration by shipping mode
- Operational differences between shipping modes

The results are automatically exported to:

```text
outputs/shipping_analysis.csv
```

---

## 📈 Visualizations

The project includes professional visualizations created using Matplotlib and Seaborn.

The visualization analysis includes:

- Correlation Heatmap
- Sales by Category
- Monthly Sales Trend
- Sales vs Profit
- Regional Sales & Profit
- Top 10 Products
- Discount vs Profit
- Profit Margin by Category

All generated visualizations are automatically saved to:

```text
outputs/visualizations/
```

The visualizations are designed to communicate statistical patterns, business trends, and performance differences clearly.

---

## 🤖 Modular & Automated Analysis

Reusable Python functions were developed to make the analytical workflow more structured, maintainable, and reusable.

The modular components support:

- Data cleaning
- Feature engineering
- Outlier detection
- KPI generation
- Automated analytical processing

This modular approach improves code organization and makes the workflow easier to maintain and adapt to similar analytical datasets.

---

## 📤 Automated Outputs

The project automatically generates and exports analytical outputs, including:

- Cleaned dataset
- KPI summary
- Regional performance analysis
- Top customers
- Top products
- Yearly sales
- Yearly profit
- Monthly sales
- Category profitability
- Shipping analysis
- Business analytical report
- Visualization files

All generated analytical outputs are organized inside the:

```text
outputs/
```

directory.

---

## ⚡ Memory Optimization

The project includes DataFrame memory optimization to improve computational efficiency.

Suitable categorical columns were converted to Pandas categorical data types where appropriate.

The optimization process compares memory usage before and after optimization while preserving the analytical functionality of the dataset.

---

## 📄 Documentation

Detailed project documentation is included in:

```text
documentation/Documentation.docx
```

The documentation provides additional details about:

- Data preparation
- Data cleaning
- Feature engineering
- Exploratory data analysis
- Statistical analysis
- Visualizations
- Automated processing
- Exported outputs
- Business insights
- Memory optimization

---

## 🎯 Project Outcome

This project demonstrates a complete Python-based Data Analyst workflow for transforming raw retail transaction data into structured analytical outputs and actionable business insights.

The project demonstrates practical experience in:

- Python
- Pandas
- NumPy
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization
- KPI Development
- Modular Programming
- Automated Reporting
- Automated Data Export
- Memory Optimization
- Business Insight Generation

The final solution provides a reusable analytical workflow that can support business performance monitoring and data-driven decision-making.

---
