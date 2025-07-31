
# 📊 Customer Churn Analysis Dashboard

This project presents an end-to-end **Customer Churn Analysis** and **Risk Profiling** using Power BI. It is designed to help telecom or subscription-based service providers identify at-risk customers, analyze behavioral and demographic patterns, and take data-driven decisions to reduce churn and improve customer retention.

## 🔍 Project Overview

The dashboard is divided into two key views:

### 1️⃣ Churn Dashboard

This page provides a high-level summary of churn-prone customers and insights into their profiles.

**Key Highlights:**
- **Customers at Risk**: 1,869 identified at-risk customers.
- **Demographics**: Balanced gender ratio, with 25% being senior citizens and 36% having partners.
- **Subscription Time**: Most churners have been subscribed for **less than 1 year (53%)**.
- **Payment Methods**: 57% use Electronic checks—this method is highly associated with churn.
- **Billing Method**: 75% of churners opted for paperless billing.
- **Contract Types**: 89% are on **Month-to-Month** contracts.
- **Service Usage**: High churn rate among users of phone service (91%), streaming services (44%), and device protection (29%).
- **Support Metrics**: 885 admin tickets and 2,173 tech tickets logged.

### 2️⃣ Risk Analysis Dashboard

This interactive dashboard drills down into the **churn risk** factors with filters for:
- **Risk of Churn**
- **Internet Service Type**
- **Contract Type**
- **Subscription Duration**

**Key Insights:**
- **Total Customers**: 3,875
- **Overall Churn Rate**: **42.71%**
- **Churn by Internet Service**:
  - Fiber Optic: 54.61% churn rate
  - DSL: 32.22%
  - No Internet: 18.89%
- **Churn by Contract**:
  - Month-to-Month customers show the highest churn
- **Churn by Payment Method**:
  - Electronic checks again show the highest churn rate compared to other payment types
- **Churn by Subscription Time**:
  - Customers with < 1 year of service have the highest churn rate
- **Revenue Impact**:
  - Total churned customer charges exceed **5.31M**, showing a significant revenue loss due to churn

## 📌 Key Observations & Recommendations

### 1. New Customer Engagement
- **Observation**: 53% of churners left within the first year.
- **Suggestion**: Implement onboarding programs, early check-ins, and loyalty incentives within the first year.

### 2. Long-Term Contract Promotion
- **Observation**: 89% of churners are on month-to-month contracts.
- **Suggestion**: Offer discounts for switching to long-term contracts (1-2 years).

### 3. Payment Method Analysis
- **Observation**: Electronic check users have the highest churn rate.
- **Suggestion**: Promote alternative secure payment methods and investigate usability issues.

### 4. Service Quality for Fiber Optic Users
- **Observation**: Fiber Optic users have the highest churn rate (54.61%).
- **Suggestion**: Improve reliability and performance for this premium service.

### 5. Support Ticket Monitoring
- **Observation**: High number of tech/admin tickets.
- **Suggestion**: Proactively support customers with frequent complaints.

### 6. Focus on High-Value Customers
- **Observation**: Churned customers represent 5.31M in total charges.
- **Suggestion**: Prioritize retention efforts for high-paying users.

### 7. Digital Communication Evaluation
- **Observation**: 75% of churners use paperless billing.
- **Suggestion**: Ensure digital messages are clear and engaging; promote offers through billing channels.

### 8. Segment by Service Usage
- **Observation**: High churn in phone (91%) and streaming services (44%).
- **Suggestion**: Evaluate service value and bundle offerings to increase stickiness.

### 9. Loyalty & Referral Programs
- **Observation**: New customers churn more frequently.
- **Suggestion**: Launch referral bonuses, rewards, and milestone-based loyalty schemes.

## 💡 Tools Used

- **Power BI**: For interactive dashboard creation and data visualization
- **DAX (Data Analysis Expressions)**: For calculated columns and measures
- **Data Cleaning & Preprocessing**: Performed prior to visualization (e.g., subscription time grouping, churn categorization)

## 📷 Dashboard Snapshots

| Churn Dashboard | Risk Analysis Dashboard |
|-----------------|--------------------------|
| ![Churn Dashboard](./churn%20dashboard.png) | ![Risk Analysis Dashboard](./Risk%20Analysis.png) |

