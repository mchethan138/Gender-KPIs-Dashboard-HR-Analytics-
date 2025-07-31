
# 📊 Customer Churn Analysis Dashboard

This project presents an end-to-end **Customer Churn Analysis** and **Risk Profiling** using Power BI. It is designed to help telecom or subscription-based service providers identify at-risk customers, analyze behavioral and demographic patterns, and take data-driven decisions to reduce churn and improve customer retention.

## 🔍 Project Overview

The dashboard is divided into two key views:

### 1️⃣ Churn Dashboard
Provides a high-level summary of churn-prone customers and insights into their profiles.

### 2️⃣ Risk Analysis Dashboard
Drills down into specific churn risk factors with interactive filters for churn probability, internet service, contract type, and subscription duration.

---

## 📌 Key Observations from the Churn Analysis Project

### 📊 Churn Dashboard

**Demographics:**
- Gender distribution among churners is almost equal (Female: 49.76%, Male: 50.24%).
- 25% of churners are Senior Citizens, indicating higher risk in older age groups.
- 36% have partners, and 17% have dependents, which could impact service cancellation decisions.

**Subscription Duration:**
- 53% of churned customers were subscribed for less than 1 year, suggesting that new users are more likely to churn.
- Churn rate significantly drops with longer subscription duration.

**Payment Behavior:**
- A high percentage (57%) of churners used Electronic checks.
- Month-to-month contracts dominate churners (89%).

**Billing Preference:**
- 74.91% of churners had Paperless Billing.

**Service Usage:**
- 91% of churners had Phone Service.
- 44% used Streaming TV/Movies and 29% had Device Protection.
- 50% of churners had multiple lines.

**Support Issues:**
- High number of Tech (2,173) and Admin (885) support tickets.

---

### 🔍 Risk Analysis Dashboard

**Overall Churn Rate:**
- Churn rate stands at 42.71%.

**Churn by Internet Service:**
- Fiber Optic users: 54.61% churn rate.
- DSL users: 32.22%.
- No internet: 18.89%.

**Churn by Contract Type:**
- Month-to-Month contracts show the highest churn.

**Churn by Payment Method:**
- Highest churn with Electronic Check.
- Lower churn with Bank Transfer, Credit Card, and Mailed Check.

**Churn by Subscription Time:**
- Customers with less than 1 year of service have the highest churn rate.
- Loyalty improves over time.

**Revenue Impact:**
- Total churned customer charges exceed 5.31M.

---

## ✅ Suggestions to Reduce Customer Churn

1. **Target New Customers with Engagement Strategies**
   - *Observation:* 53% churned within the first year.
   - *Suggestion:* Strong onboarding, early check-ins, and loyalty incentives.

2. **Incentivize Long-Term Contracts**
   - *Observation:* 89% are on month-to-month contracts.
   - *Suggestion:* Offer discounts or bundles for longer contracts.

3. **Review Issues with Electronic Check Payments**
   - *Observation:* Highest churn via Electronic Checks.
   - *Suggestion:* Promote alternatives like credit card/bank transfer.

4. **Improve Service Quality for Fiber Optic Users**
   - *Observation:* Fiber Optic users have highest churn rate.
   - *Suggestion:* Improve reliability and collect feedback.

5. **Monitor Customers Logging Support Tickets**
   - *Observation:* High tech/admin ticket volume.
   - *Suggestion:* Flag and support frequent complainants proactively.

6. **Focus Retention on High-Value Customers**
   - *Observation:* High total charges (5.31M) from churned users.
   - *Suggestion:* Use customer lifetime value models for prioritization.

7. **Reevaluate Paperless Billing Communication**
   - *Observation:* 74.91% use paperless billing.
   - *Suggestion:* Improve clarity and engagement in digital messages.

8. **Segment Customers by Service Use**
   - *Observation:* High churn among Phone, Streaming, and Protection users.
   - *Suggestion:* Assess value perception and improve service offerings.

9. **Promote Referral or Loyalty Programs**
   - *Observation:* <1 year tenure customers churn more.
   - *Suggestion:* Implement referral, milestone, or loyalty rewards.

---

## 💡 Tools Used

- **Power BI**: Interactive dashboard creation and data visualization
- **DAX**: Custom measures and KPIs
- **Data Cleaning**: Done prior to visualization to prepare meaningful groupings and aggregations

---

## 📷 Dashboard Snapshots

| Churn Dashboard | Risk Analysis Dashboard |
|-----------------|--------------------------|
| ![Churn Dashboard](./churn%20dashboard.png) | ![Risk Analysis Dashboard](./Risk%20Analysis.png) |

