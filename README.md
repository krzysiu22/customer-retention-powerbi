# KajoDataSpace: Customer Retention & Pricing Strategy Analysis

## Project Overview
I developed this project in response to a data analysis challenge organized by KajoData and Data Acolyte. My primary objective was to analyze a dataset of subscription transactions to determine the impact of promotional pricing, standard rates, and price increases on customer retention and new user acquisition. 

Through this analysis, I focused on answering the following key business questions:
* How do pricing changes affect the influx of new customers?
* Are customers churning faster depending on their pricing segment?
* What is the optimal business strategy: more frequent promotions or price increases for new users?

## Tools & Technologies
* **Power BI:** Data visualization, interactive dashboard design, and UI/UX optimization.
* **DAX:** Creating custom measures for KPI tracking (ARPU, Total Revenue, Customer Count).
* **Data Modeling:** Transforming the raw transactional log into a relational model suitable for cohort and retention analysis.

## Dataset
* **Timeframe:** November 2023 - March 2026
* **Size:** ~4,000 transactional records
* **Features:** Date, Customer ID, Transaction Amount

## Key Business Findings

### 1. The Premium Segment Paradox
My analysis revealed that customers categorized within the Premium / Price Increase segment generate the highest Average Revenue Per User (ARPU: 1,363 PLN) and form the core of the company's total revenue over the analyzed period.

### 2. High Churn Rate in High-Value Tiers
Despite being the most profitable group, the retention curve I built highlights a critical issue: the Premium segment acts largely as a "one-off" group. The vast majority of these high-paying customers churn immediately after their first month (Month 0). 

### 3. Promotional vs. Standard Pricing
While deep promotions attract a high volume of users, they do not guarantee long-term loyalty. The standard tier maintains a steady but significantly lower ARPU.

## Strategic Recommendation
Based on the data story, I identified that the company is losing significant capital through the rapid churn of VIP customers. 

**Actionable Insight:** 
Instead of focusing solely on aggressive price hikes or deep promotions for acquisition, I recommend immediately implementing a loyalty program or dedicated retention marketing (follow-up campaigns) targeting the Premium Segment around their first month of purchase. Retaining even 5-10% of this specific cohort will drastically increase global profits without the additional Customer Acquisition Cost (CAC) required to generate new leads.

## Dashboard Preview
![Dashboard Screenshot](DashboardKajodata.png)

---
*Project created for the #dataacolyte & #kajodataspace challenge.*
