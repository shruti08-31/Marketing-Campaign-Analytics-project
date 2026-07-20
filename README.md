# 📊 Marketing Campaign Analytics using Python & Power BI

## Portfolio Demonstration Project

This project demonstrates an end-to-end data analytics workflow using **Python** and **Power BI** to analyze a real-world bank marketing campaign dataset. The objective is to transform raw marketing data into actionable business insights through data preprocessing, exploratory data analysis (EDA), KPI generation, and interactive dashboard development.

The project showcases practical skills in data cleaning, business intelligence, data visualization, and analytical storytelling.

---

# Project Objectives

The primary objectives of this project are to:

- Analyze customer responses to direct marketing campaigns.
- Identify factors influencing term deposit subscriptions.
- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis to uncover business patterns.
- Generate meaningful KPIs.
- Build an interactive Power BI dashboard.
- Provide data-driven business recommendations.

---

# Dataset

**Dataset:** Bank Marketing Dataset

The dataset contains customer information collected during direct marketing campaigns conducted by a banking institution.

### Dataset includes:

- Customer Demographics
- Financial Information
- Previous Campaign History
- Marketing Contact Details
- Campaign Outcome

Approximately **11,000+ customer records** with **17 features** are analyzed in this project.

---

# Technologies Used

| Tool | Purpose |
|-------|----------|
| Python | Data Analysis |
| Pandas | Data Cleaning & Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Analysis Environment |
| Power BI | Interactive Dashboard |
| Git & GitHub | Version Control |

---

# Project Structure

```text
Marketing-Campaign-Analytics/
│
├── 01Dataset/
│   └── bank.csv
│
├── 02Notebook/
│   └── Marketing_Funnel_Analysis.ipynb
│
├── 03Images/
│   ├── age_distribution.png
│   ├── deposit_distribution.png
│   ├── monthly_conversion.png
│   ├── top_10_jobs_conversion_rate.png
│   └── ...
│
├── Dashboard/
│   └── Marketing Campaign Dashboard.pbix
│
├── Report/
│   └── Marketing_Campaign_Analytics_Report.pdf
│
└── README.md
```

---

# Project Workflow

The project follows a complete analytics pipeline:

```
Business Problem
        │
        ▼
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Data Preprocessing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Business Insights
        │
        ▼
KPI Generation
        │
        ▼
Power BI Dashboard
        │
        ▼
Business Recommendations
```

---

# Data Preprocessing

The following preprocessing steps were performed:

- Loaded dataset using Pandas
- Inspected dataset structure
- Removed duplicate records
- Checked missing values
- Treated outliers using the IQR Method
- Converted categorical values where required
- Created a binary conversion variable
- Generated customer age groups
- Calculated business KPIs

---

# Exploratory Data Analysis

Several visualizations were created to understand customer behavior and campaign performance.

Analysis includes:

- Customer Age Distribution
- Deposit Subscription Distribution
- Job-wise Conversion Analysis
- Marital Status Analysis
- Education Analysis
- Housing Loan Analysis
- Personal Loan Analysis
- Contact Method Performance
- Monthly Campaign Performance
- Campaign Duration Analysis
- Previous Campaign Outcome
- Correlation Analysis

---

# Key Performance Indicators (KPIs)

The following KPIs were generated:

- Total Customers
- Total Conversions
- Overall Conversion Rate
- Average Customer Balance
- Average Call Duration

These KPIs were later integrated into the Power BI dashboard.

---

# Interactive Power BI Dashboard

An interactive dashboard was developed to allow business users to explore campaign performance dynamically.

### Dashboard Features

- Executive KPI Cards
- Customer Demographics
- Job-wise Conversion Analysis
- Education Analysis
- Monthly Conversion Trends
- Housing Loan vs Conversion
- Personal Loan vs Conversion
- Contact Method Analysis
- Previous Campaign Analysis
- Call Duration Analysis
- Interactive Filters (Slicers)

---

# Business Insights

The analysis revealed several meaningful business findings:

- Students and retirees achieved the highest conversion rates.
- Customers with tertiary education converted more frequently.
- Customers without housing or personal loans subscribed more often.
- Cellular communication significantly outperformed telephone campaigns.
- March, September, October, and December delivered better conversion efficiency than May.
- Longer customer conversations were strongly associated with successful subscriptions.
- Previous successful campaign responses were highly predictive of future conversions.

---

# Business Recommendations

Based on the analysis, the following recommendations were developed:

- Target students and retired customers more aggressively.
- Increase campaign efforts during high-conversion months.
- Prioritize customers who responded positively in previous campaigns.
- Focus marketing efforts on customers without existing loans.
- Encourage longer, consultative customer conversations.
- Increase the use of cellular communication.
- Continuously monitor campaign performance using interactive dashboards.

---

# Skills Demonstrated

This project demonstrates practical experience with:

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Business Intelligence
- KPI Development
- Dashboard Design
- Data Visualization
- Business Analytics
- Storytelling with Data
- Python Programming
- Power BI

---

# How to Run the Project

### Clone the repository

```bash
git clone https://github.com/<your-username>/marketing-campaign-analytics.git
```

### Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
02Notebook/Marketing_Funnel_Analysis.ipynb
```

Run all cells sequentially.

---

# Report

A detailed project report explaining the complete analytics workflow is included in the repository.

```
Report/
```

---

# Dashboard

The Power BI dashboard file (.pbix) is included in:

```
Dashboard/
```

Open it using Microsoft Power BI Desktop.

---

# Future Improvements

Potential future enhancements include:

- Predictive modeling for customer conversion
- Customer segmentation using clustering
- Campaign performance forecasting
- Interactive web dashboard using Streamlit
- Automated reporting pipeline

---

# Learning Outcome

This portfolio project demonstrates the complete lifecycle of a real-world analytics project—from raw data preparation to business insight generation and interactive dashboard development. It highlights the ability to apply Python and Power BI to solve business problems through data-driven decision-making.

---

# Author

**Shruti Prasad**

Aspiring Data Analyst | Python | Power BI | SQL | Data Visualization | Business Analytics

---

## License

This repository is intended for educational and portfolio purposes.
