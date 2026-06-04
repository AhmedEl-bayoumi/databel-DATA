# 📊 Databel Customer Churn Business Intelligence Report
# Dashboard
<img width="893" height="505" alt="DATABEL 3" src="https://github.com/user-attachments/assets/734d4933-ced3-4de3-b13f-bdac80c44c9d" />
<img width="888" height="494" alt="databel 2" src="https://github.com/user-attachments/assets/09f4d3ad-cc53-4302-861f-54f102be773d" />
<img width="887" height="499" alt="databel 1" src="https://github.com/user-attachments/assets/ab3411b4-019c-4610-8084-d715e0fd34b8" />

## 📋 Executive Summary
This repository contains a comprehensive data analytics project analyzing customer attrition for **Databel**, a telecommunications provider. Utilizing behavioral, demographic, and financial data points, this multi-page interactive dashboard uncovers the core drivers of customer churn. 

The primary objective is to transform raw customer data into actionable business strategies that mitigate revenue leakage, optimize plan structures, and improve long-term subscriber retention.

---

## 📈 Core Performance Indicators (KPIs)
The high-level health metrics of Databel's customer base reveal an urgent need for targeted retention strategies:

* **Total Customers:** 6,687 active accounts analyzed.
* **Number of Churned Customers:** 1,796 subscribers lost.
* **Overall Churn Rate:** **27%** — significantly higher than standard healthy industry baselines.
* **Average Monthly Charges:** $31 per user.
* **Customer Support Touchpoints:** 6,123 total service calls, averaging roughly 1 call per customer across the dataset.

---

## 🔍 Detailed Dashboard Breakdown & Visualization Insights

### 1. Executive Overview & Attrition Drivers
The primary layer of the analysis focuses on *why* and *where* customers are leaving.

* **Top Churn Reasons:** Competitor behavior is the leading threat to market share. **"Competitor made a better offer"** accounts for 303 churned accounts, closely followed by **"Competitor had better devices"** at 297 accounts.
* **Macro Categories:** A macroeconomic breakdown shows that **Competitors** are responsible for **45%** of the overarching churn classification, followed by Attitude/Service-related departures.
* **Geographic Vulnerabilities:** Geographic analysis shows that **California (CA)** is a massive anomaly with a staggering **63% churn rate**, nearly doubling the baseline of runner-up states like Ohio (OH) at 35% and Pennsylvania (PA) at 33%.

### 2. Demographic Profile Analysis
This view correlates customer lifecycle metrics with age segments and account relationship structures to pinpoint high-risk populations.

* **The Senior Citizen Risk:** While the sheer volume of churned accounts is distributed relatively evenly across working-age adults (ages 20 to 60, averaging 130–170 per bucket), the *proportional churn rate* scales drastically after age 65. It peaks sharply at **50%+ for customers aged 70–85**.
* **Demographic Distribution:** Senior citizens comprise **45%** of the entire demographic churn pie chart.
* **Account Group Dynamics:** Group size inversely scales with churn risk. Single-user accounts (Group Size = 0) exhibit a severe **33% churn rate** alongside the highest average monthly spending ($33). Conversely, accounts tied to larger groups (sizes 3 through 6+) scale down to stable churn rates of just **6% to 8%**.

### 3. Financial, Contractual, & Product-Usage Risk
An investigation into contract structures, payment channels, and data consumption habits reveals structural misalignment in Databel's product offerings.

* **Contractual Longevity:** Month-to-month contracts are highly volatile. **47% of females** and **45% of males** on monthly terms churn, whereas customers locked into yearly agreements scale down dramatically to **6% and 7% churn rates** respectively.
* **The Unlimited Data Plan Anomaly:** A critical product-market misfit exists for low-volume data users. Customers consuming **under 5GB of data** who are subscribed to an **Unlimited Data Plan** present an alarming **35% churn rate**. This signals that low-volume users feel they are paying an unnecessary premium for unused data.
* **Payment Method Behavior:** Customers paying via **Paper Check** represent **44%** of the distribution of churned users, followed closely by Direct Debit users at 40%. Credit card auto-pay systems are the most secure, accounting for only 17%.
* **Tenure Lifecycle Curve:** The account length trajectory shows that churn risk is at its absolute highest during the first 6 months of a customer's contract, gradually smoothing out as account length approaches 72 months.

---

## 🛠️ Data-Driven Strategic Recommendations

1. **Address the California (CA) Market Crisis:** A 63% churn rate demands immediate, localized attention. Conduct market research to determine if this spike is driven by poor regional network infrastructure or an aggressive regional campaign by a competitor.
2. **Implement Unlimited Plan Optimization Triggers:** Create automated system triggers to proactively flag accounts utilizing under 5GB on unlimited plans. Offer down-sell opportunities to data-tiered plans before they churn out due to perceived overpricing.
3. **De-incentivize Month-to-Month & Paper Check Options:** Adjust upfront pricing strategies to make month-to-month contracts financially restrictive, encouraging year-long commitments. Introduce small statement credits/incentives to transition users from Paper Checks to automatic Credit Card processing.
4. **Targeted Senior Loyalty Programs:** Design personalized service packages and specialized customer support pathways for users over the age of 65 to neutralize competitor hardware or device offers.
5. **Onboarding Safeguards:** Since tenure analysis shows the first 6 months are highly volatile, build strong customer service check-ins during months 1 through 3 to lower the early drop-off rate.
