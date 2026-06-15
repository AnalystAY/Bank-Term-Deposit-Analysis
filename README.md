📊 Bank Term Deposit Marketing Analysis

"Power BI" (https://img.shields.io/badge/Tool-Power%20BI-yellow)
"SQL" (https://img.shields.io/badge/Tool-SQL-blue)
"Excel" (https://img.shields.io/badge/Tool-Excel-green)
"Status" (https://img.shields.io/badge/Status-Completed-success)

📌 Project Overview

Banks invest heavily in telemarketing campaigns to promote term deposit subscriptions. Since outbound calling is expensive and resource-intensive, identifying customers with a higher likelihood of subscribing can significantly improve campaign effectiveness and reduce marketing costs.

This project analyzes over 45,000 customer records from a Portuguese banking institution to uncover customer characteristics, campaign factors, and behavioral patterns associated with successful term deposit subscriptions.

The analysis was conducted using Excel, SQL, and Power BI to simulate a real-world business analytics workflow from data exploration to executive reporting.

---

🎯 Business Problem

The bank needs to answer the following questions:

- Which customer segments are most likely to subscribe to a term deposit?
- What campaign factors influence conversion?
- Which communication channels perform best?
- How can marketing resources be allocated more effectively?
- What actionable insights can increase subscription rates?

---

🛠️ Tools Used

Tool| Purpose
Microsoft Excel| Data Cleaning & Exploratory Analysis
SQL| Business Querying & Data Investigation
Power BI| Dashboard Development & Visualization
GitHub| Project Documentation & Portfolio Hosting

---

📂 Dataset Information

Dataset: Bank Marketing Dataset

Source: UCI Machine Learning Repository

Records: 45,211

Features: 17

Target Variable: "y"

- Yes = Customer subscribed to a term deposit
- No = Customer did not subscribe

Dataset Citation

Moro, S., Cortez, P., & Rita, P. (2014).

A Data-Driven Approach to Predict the Success of Bank Telemarketing.

Decision Support Systems, Elsevier, 62:22–31.

---

🔍 Project Workflow

Phase 1 — Business Understanding

Understanding the bank's marketing objectives and identifying key performance indicators.

Phase 2 — Data Cleaning (Excel)

- Checked for missing values
- Reviewed data types
- Identified outliers
- Verified categorical variables
- Performed preliminary segmentation analysis

Phase 3 — SQL Analysis

Developed business-focused queries to answer strategic questions:

- Which jobs convert best?
- Which months perform best?
- Does loan status affect subscriptions?
- How important is previous campaign success?
- Which contact methods are most effective?

Phase 4 — Power BI Dashboard

Built an executive dashboard showing:

- Customer Segmentation
- Conversion Analysis
- Campaign Performance
- Marketing Insights
- Subscription Trends

Phase 5 — Business Recommendations

Translated analytical findings into actionable recommendations for decision-makers.

---

📈 Key Performance Indicators (KPIs)

KPI| Value
Total Customers| 45,211
Total Subscribers| 5,289
Conversion Rate| 11.7%
Non-Subscribers| 39,922
Features Analyzed| 17

---

💡 Key Insights

1️⃣ Customer Occupation Matters

Students and retired customers demonstrated significantly higher subscription rates than other occupational groups.

Business Impact

Marketing campaigns should prioritize these customer segments to maximize conversion efficiency.

---

2️⃣ Previous Campaign Success Is a Strong Predictor

Customers who previously responded positively to a marketing campaign were far more likely to subscribe again.

Business Impact

These customers should be prioritized in future outreach campaigns.

---

3️⃣ Contact Method Influences Conversion

Cellular communication channels achieved higher conversion rates than traditional telephone contact.

Business Impact

Future campaigns should emphasize mobile communication strategies.

---

4️⃣ Existing Debt Reduces Subscription Likelihood

Customers with housing loans and personal loans were less likely to invest in term deposits.

Business Impact

Marketing resources may be more effective when focused on customers with lower debt obligations.

---

5️⃣ Longer Conversations Lead to Better Outcomes

Customers who subscribed generally participated in longer conversations with bank representatives.

Business Impact

Investing in quality customer engagement may improve conversion rates.

---

6️⃣ Campaign Timing Matters

Certain months consistently outperformed others in terms of conversion rates.

Business Impact

Campaign budgets should be optimized around historically high-performing periods.

---

📊 Dashboard Preview

Executive Dashboard

Key Metrics

- Total Customers
- Subscribers
- Conversion Rate
- Average Balance
- Average Call Duration

Visualizations

- Subscription Distribution
- Customer Segmentation
- Monthly Conversion Trend
- Job Category Performance
- Loan Status Analysis
- Campaign Performance Analysis

---

📸 Dashboard Screenshots

Executive Overview

"Executive Dashboard" (images/dashboard-overview.png)

Customer Segmentation

"Customer Segmentation" (images/customer-segmentation.png)

Campaign Performance

"Campaign Performance" (images/campaign-performance.png)

---

🧮 Sample SQL Analysis

Conversion Rate by Job

SELECT
    job,
    ROUND(
        SUM(CASE WHEN y='yes' THEN 1 ELSE 0 END) * 100.0
        / COUNT(*),2
    ) AS conversion_rate
FROM bank
GROUP BY job
ORDER BY conversion_rate DESC;

---

Conversion Rate by Previous Campaign Outcome
```sql
SELECT
    poutcome,
    ROUND(
        SUM(CASE WHEN y='yes' THEN 1 ELSE 0 END) * 100.0
        / COUNT(*),2
    ) AS conversion_rate
FROM bank
GROUP BY poutcome
ORDER BY conversion_rate DESC;
```
---

📋 Business Recommendations

Recommendation 1

Prioritize customer segments with historically high conversion rates such as students and retirees.

Recommendation 2

Implement customer retargeting strategies for individuals who previously responded positively to campaigns.

Recommendation 3

Increase investment in mobile communication channels.

Recommendation 4

Develop specialized messaging for customers with active loans.

Recommendation 5

Schedule campaigns during historically high-performing months.

---

📚 Skills Demonstrated

✅ Data Cleaning

✅ Exploratory Data Analysis (EDA)

✅ Customer Segmentation

✅ SQL Query Development

✅ Data Visualization

✅ Dashboard Design

✅ KPI Development

✅ Business Intelligence

✅ Data Storytelling

✅ Business Recommendation Framework

---

🚀 Project Outcomes

This project demonstrates how data analytics can help financial institutions:

- Improve campaign effectiveness
- Reduce telemarketing costs
- Increase conversion rates
- Better understand customer behavior
- Make data-driven marketing decisions

---

👤 Author

Ayomide Idowu

Certified Data Analyst

Connect With Me

- LinkedIn: [Add LinkedIn URL]
- GitHub: [Add GitHub URL]
- Portfolio: [Add Portfolio URL]

---

⭐ If You Found This Project Useful

Please consider giving this repository a star.

It helps support my data analytics learning journey and showcases the project to other learners and recruiters.Before publishing:
