# 📊 Bank Term Deposit Marketing Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![SQL](https://img.shields.io/badge/SQL-Analysis-blue)
![Excel](https://img.shields.io/badge/Excel-Data%20Cleaning-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# Project Overview

This project analyzes customer and campaign data from a Portuguese banking institution to understand the factors influencing term deposit subscriptions.

Banks spend significant resources on telemarketing campaigns. Identifying customers most likely to subscribe can improve marketing efficiency, reduce campaign costs, and increase conversion rates.

Using Excel, SQL, and Power BI, this project explores customer demographics, financial behavior, campaign performance, and previous marketing outcomes to generate actionable business insights.

---

# Business Problem

The bank wants to improve the effectiveness of its telemarketing campaigns by answering the following questions:

- Which customers are most likely to subscribe to a term deposit?
- Which customer segments should be prioritized?
- How effective are different communication channels?
- Does previous campaign success influence future subscriptions?
- What factors drive conversion?

---

# Dataset Information

| Attribute | Value |
|------------|---------|
| Dataset | Bank Marketing Dataset |
| Source | UCI Machine Learning Repository |
| Records | 45,211 |
| Features | 17 |
| Target Variable | Term Deposit Subscription |

### Target Variable

| Value | Meaning |
|---------|---------|
| Yes | Customer subscribed |
| No | Customer did not subscribe |

---

# Tools Used

| Tool | Purpose |
|--------|---------|
| Excel | Data Cleaning & Exploratory Data Analysis |
| SQL | Business Analysis |
| Power BI | Dashboard Development |
| GitHub | Project Documentation |

---

# Project Workflow

```text
Business Understanding
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
SQL Analysis
        ↓
Power BI Dashboard
        ↓
Business Recommendations
```

---

# Key Performance Indicators

| KPI | Value |
|------|------|
| Total Customers | 45,211 |
| Subscribers | 5,289 |
| Non-Subscribers | 39,922 |
| Conversion Rate | 11.70% |

### Key Observation

Only about 1 out of every 9 customers subscribed to a term deposit, highlighting the importance of targeted marketing.

---

# Data Cleaning

The dataset underwent quality checks before analysis.

### Data Quality Results

| Check | Result |
|---------|---------|
| Missing Values | None |
| Duplicate Records | None Detected |
| Invalid Data Types | Corrected |
| Data Consistency | Verified |

---

# Exploratory Data Analysis

## Customer Occupation Analysis

### Top Converting Occupations

| Occupation | Conversion Rate |
|------------|----------------|
| Student | 28.68% |
| Retired | 22.79% |
| Unemployed | 15.50% |
| Management | 13.76% |
| Admin | 12.20% |

### Insight

Students converted at more than double the overall conversion rate.

### Business Interpretation

Students and retirees appear more receptive to savings and investment products.

---

## Education Analysis

| Education Level | Conversion Rate |
|----------------|----------------|
| Tertiary | 15.01% |
| Unknown | 13.57% |
| Secondary | 10.56% |
| Primary | 8.63% |

### Insight

Customers with tertiary education demonstrated the strongest conversion performance.

### Business Interpretation

Financial literacy may contribute to increased adoption of investment products.

---

## Housing Loan Analysis

| Housing Loan | Conversion Rate |
|--------------|----------------|
| No | 16.70% |
| Yes | 7.70% |

### Insight

Customers without housing loans converted at more than twice the rate of customers with housing loans.

### Business Interpretation

Customers with fewer financial obligations may have greater disposable income available for investments.

---

## Personal Loan Analysis

| Personal Loan | Conversion Rate |
|---------------|----------------|
| No | 12.66% |
| Yes | 6.68% |

### Insight

Customers with personal loans were significantly less likely to subscribe.

### Business Interpretation

Existing debt appears to reduce willingness to commit funds to long-term savings products.

---

# Campaign Performance Analysis

## Contact Method Analysis

| Contact Type | Conversion Rate |
|--------------|----------------|
| Cellular | 14.92% |
| Telephone | 13.42% |
| Unknown | 4.07% |

### Insight

Cellular communication generated the highest conversion rates.

### Business Interpretation

Mobile communication channels should be prioritized for future campaigns.

---

## Call Duration Analysis

| Outcome | Average Duration |
|----------|----------------|
| Subscribed | 537 Seconds |
| Not Subscribed | 221 Seconds |

### Insight

Successful conversions were associated with significantly longer conversations.

### Business Interpretation

Customer engagement plays a major role in conversion success.

---

# Monthly Campaign Performance

## Top Performing Months

| Month | Conversion Rate |
|--------|----------------|
| March | 51.99% |
| December | 46.73% |
| September | 46.46% |
| October | 43.77% |

### Insight

Subscription behavior varies considerably across the year.

### Business Interpretation

Campaign timing can significantly impact performance.

---

# Previous Campaign Analysis

## Previous Campaign Outcome

| Outcome | Conversion Rate |
|----------|----------------|
| Success | 64.73% |
| Other | 16.68% |
| Failure | 12.61% |
| Unknown | 9.16% |

### Insight

Customers who previously responded positively were over five times more likely to subscribe again.

### Business Interpretation

Previous campaign success is the strongest predictor of future conversion.

---

# SQL Analysis

The SQL phase focused on answering business questions related to customer segmentation, campaign effectiveness, and conversion drivers.

### Key SQL Questions

- Which occupation has the highest conversion rate?
- Which months produce the highest conversions?
- Does loan status affect customer behavior?
- Which communication channels perform best?
- How does previous campaign success influence future outcomes?

Example queries can be found in:

```text
/sql/business_queries.sql
```

---

# Power BI Dashboard

The dashboard was designed for business stakeholders and marketing managers.

## Dashboard Pages

### Executive Summary

KPIs:
- Total Customers
- Subscribers
- Conversion Rate
- Average Balance
- Average Call Duration

### Customer Insights

Visualizations:
- Occupation Analysis
- Education Analysis
- Marital Status Analysis
- Loan Analysis

### Campaign Performance

Visualizations:
- Contact Method Performance
- Monthly Conversion Trends
- Campaign Success Analysis
- Previous Outcome Analysis

---

# Dashboard Screenshots

## Executive Dashboard

![Executive Dashboard](images/executive-dashboard.png)

---

## Customer Analysis Dashboard

![Customer Dashboard](images/customer-analysis.png)

---

## Campaign Performance Dashboard

![Campaign Dashboard](images/campaign-performance.png)

---

# Key Findings

### Finding 1

Students and retirees are the most responsive customer groups.

### Finding 2

Customers without loans convert significantly better than customers with active debt.

### Finding 3

Cellular communication outperforms traditional telephone contact.

### Finding 4

Longer customer conversations are strongly associated with successful conversions.

### Finding 5

Campaign timing significantly impacts conversion rates.

### Finding 6

Previous campaign success is the strongest predictor of future subscription behavior.

---

# 📋 Recommendations

## Recommendation 1

Prioritize students and retirees in future telemarketing campaigns.

### Expected Impact

Higher conversion rates with lower marketing costs.

---

## Recommendation 2

Implement retargeting strategies for customers who previously subscribed.

### Expected Impact

Improved campaign ROI.

---

## Recommendation 3

Increase investment in mobile communication channels.

### Expected Impact

Higher engagement and improved conversion rates.

---

## Recommendation 4

Create specialized offers for customers with existing loans.

### Expected Impact

Improved relevance and customer response.

---

## Recommendation 5

Increase campaign activity during historically high-performing months.

### Expected Impact

Better resource utilization and campaign effectiveness.

---

# Skills Demonstrated

### Data Analytics

- Data Cleaning
- Exploratory Data Analysis
- Customer Segmentation
- KPI Analysis

### SQL

- Aggregations
- CASE Statements
- Grouping & Filtering
- Business Reporting Queries

### Power BI

- Dashboard Development
- Data Modeling
- DAX Measures
- Interactive Reporting

### Business Intelligence

- Data Storytelling
- Insight Generation
- Strategic Recommendations

---

# Project Outcome

This project demonstrates how customer and campaign data can be transformed into actionable business insights that improve marketing efficiency, increase subscription rates, and support data-driven decision-making.

---

# Author

## Ayomide Idowu

**Data Analyst | Excel | SQL | Power BI**

### Connect With Me

- LinkedIn: [linkedin.com/in/analystay]
- GitHub: [Your GitHub URL]
- Portfolio: [Your Portfolio URL]

---

⭐ If you found this project useful, consider giving the repository a star.
