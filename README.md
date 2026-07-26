# 🔄 Customer Retention & Pricing Strategy Analysis ("The Premium Paradox")

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-00599C?style=for-the-badge&logo=powerbi&logoColor=white)
![Data Modeling](https://img.shields.io/badge/Data_Modeling-Relational-blue?style=for-the-badge)
![Analytics](https://img.shields.io/badge/Analytics-Cohort_%26_Churn-orange?style=for-the-badge)

## 📌 Project Overview
This project was developed in response to a data analysis challenge organized by **KajoData** and **Data Acolyte**. The primary objective was to evaluate a transactional subscription dataset (~4,000 records) to determine how promotional pricing, standard rates, and price increases impact customer retention, long-term LTV, and churn rates.

### ❓ Key Business Questions Addressed
* How do pricing changes directly affect the influx and quality of new customer cohorts?
* Are high-value customers churning faster depending on their price tier?
* What is the optimal strategic balance: aggressive promotional acquisition vs. retention of price-increased tiers?

---

## 🛠️ Tools & Technical Workflow
* **Power BI:** Interactive UI/UX design, visual hierarchy, and executive layout optimization.
* **DAX:** Custom measures for cohort KPIs (ARPU, Active Subscribers, Retention %, Cumulative Revenue).
* **Data Modeling:** Transformed raw transactional log into a relational cohort model optimized for time-series retention analysis.

---

## 💡 Key Business Findings & Strategic Impact

Through cohort breakdown and time-series retention tracking, three core customer behaviors were identified:

| Pricing Segment | Key Metric (ARPU) | Retention Profile | Operational Impact & Finding |
| :--- | :--- | :--- | :--- |
| 💎 **Premium / Price Increase** | **1,363 PLN** (Highest) | 📉 **Critical Churn (Month 1)** | **"The Premium Segment Paradox":** Generates the highest immediate revenue, but customers treat it as a "one-off" service and churn immediately after Month 0/1. |
| 🏷️ **Promotional Pricing** | Lower ARPU | 📊 High Acquisition / Low Loyalty | Attracts high transaction volume, but users show low long-term retention without follow-up incentives. |
| 📦 **Standard Rates** | Baseline ARPU | 📈 Steady / Predictable | Provides steady, recurring baseline revenue with moderate retention curves. |

---

## 🎯 Actionable Strategic Recommendation

The data explicitly reveals that the company suffers substantial revenue leakage due to the rapid churn of VIP customers in their first month.

> **💡 Executive Recommendation:**  
> Shift marketing focus from aggressive discount-led acquisition to an automated **Month 1 VIP Loyalty & Onboarding Program** specifically targeting the Premium tier. Retaining even **5–10%** of this specific cohort will significantly increase global net profits without increasing Customer Acquisition Costs (CAC).

---

## 📷 Dashboard Preview

<p>
  <img src="DashboardKajodata.png" alt="Customer Retention & Pricing Strategy Dashboard" width="100%">
  <br>
  <em>Interactive Power BI report displaying overall portfolio performance, cohort retention curves, and pricing tier ARPU breakdown.</em>
</p>

---

## 📂 Dataset Specification
* **Timeframe:** November 2023 – March 2026
* **Volume:** ~4,000 transactional records
* **Core Granularity:** `Transaction Date`, `Customer ID`, `Amount`, `Pricing Tier`

---

## 👤 Author & Challenge Info
* **Project Context:** Created for the **#dataacolyte** & **#kajodataspace** data challenge.
* **Author:** Krzysztof Mielewczyk
* **Profile:** Junior Data Analyst / BI Developer
* 🔗 [LinkedIn Profile](https://www.linkedin.com/in/krzysztof-mielewczyk-45b4b023b/)
