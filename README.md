# FUTURE_DS_02
Customer Retention &amp; Churn Analysis
# Customer Churn & Retention Analysis

## 1. Executive Summary

This analysis examines customer churn patterns, retention drivers, and customer lifetime trends using **7,043 customer records**.

### Key findings

* **Overall churn rate:** **26.5%** — 1,869 customers have churned.
* **Month-to-month customers are the highest-risk segment:** **42.7% churn rate**.
* **Customers in their first year are most vulnerable:** **47.4% churn rate** for customers with 0–1 year tenure.
* **Month-to-month Fiber Optic customers are the most critical risk segment:** **54.6% churn rate**.
* **Electronic check users have a high churn rate:** **45.3%**, increasing to **53.7% among month-to-month customers**.
* **Long-term contracts strongly improve retention:** churn falls to just **2.8% for two-year contracts**.
* **Customers with support and security services are more loyal**, suggesting that additional services can strengthen customer engagement and retention.
* Customer lifetime value increases significantly with tenure, with customers having **5+ years of tenure generating an average TotalCharges of approximately $5,180**.

---

## 2. Dataset Overview

| Metric             |      Value |
| ------------------ | ---------: |
| Total Customers    |      7,043 |
| Churned Customers  |      1,869 |
| Retained Customers |      5,174 |
| Overall Churn Rate |      26.5% |
| Average Tenure     | ~32 months |

The analysis focuses on identifying the customer groups most likely to churn and understanding the characteristics associated with long-term retention.

---

# 3. Churn Patterns

## 3.1 Contract Type Is the Strongest Churn Indicator

| Contract Type  | Customers | Churn Rate |
| -------------- | --------: | ---------: |
| Month-to-month |     3,875 |  **42.7%** |
| One year       |     1,473 |  **11.3%** |
| Two year       |     1,695 |   **2.8%** |

### Insight

Contract commitment is one of the strongest predictors of churn.

Month-to-month customers churn at a rate of **42.7%**, compared with only **2.8% among two-year contract customers**.

This indicates that customers without a long-term commitment are significantly more likely to leave.

### Business implication

The business should focus on converting high-risk month-to-month customers into annual or longer-term contracts using:

* Contract upgrade incentives
* Loyalty discounts
* Price-lock benefits
* Free service upgrades
* Limited-time annual-plan offers

---

## 3.2 Churn Is Highest During the First Year

| Tenure Group | Churn Rate |
| ------------ | ---------: |
| 0–1 Year     |  **47.4%** |
| 1–2 Years    |      28.7% |
| 2–3 Years    |      21.6% |
| 3–4 Years    |      19.0% |
| 4–5 Years    |      14.4% |
| 5+ Years     |   **6.6%** |

### Insight

Customer churn is heavily concentrated in the early stages of the customer lifecycle.

Customers with less than one year of tenure have a **47.4% churn rate**, while customers with more than five years of tenure have only a **6.6% churn rate**.

This suggests that the first year is the most important period for customer retention.

### Business implication

A structured **first-year customer retention program** should be introduced, including:

* 30-day onboarding follow-up
* 90-day satisfaction check
* Personalized service recommendations
* Early renewal incentives
* Proactive support for customers showing signs of dissatisfaction

---

## 3.3 Fiber Optic Customers Show Elevated Churn

| Internet Service    | Churn Rate |
| ------------------- | ---------: |
| Fiber optic         |  **41.9%** |
| DSL                 |      19.0% |
| No Internet Service |       7.4% |

### Insight

Fiber optic customers have a significantly higher churn rate than DSL customers.

This may indicate potential issues related to:

* Pricing
* Customer expectations
* Service quality
* Installation experience
* Technical support
* Competition in the high-speed internet market

### Important segment finding

The combination of **Fiber Optic + Month-to-Month contract** creates the highest-risk customer group:

> **54.6% churn rate**

This is one of the most important customer segments for targeted retention campaigns.

---

## 3.4 Electronic Check Customers Have High Churn

| Payment Method   | Churn Rate |
| ---------------- | ---------: |
| Electronic check |  **45.3%** |
| Mailed check     |      19.1% |
| Bank transfer    |      16.7% |
| Credit card      |      15.2% |

### Insight

Customers using electronic checks show significantly higher churn than customers using automatic payment methods.

The relationship becomes even stronger among month-to-month customers:

> **Month-to-month + Electronic Check = 53.7% churn rate**

### Business implication

The company should encourage customers to switch to automatic payment methods through:

* Small billing discounts
* Payment method incentives
* Simplified autopay enrollment
* Reminder campaigns before payment dates

Automatic payment can potentially reduce payment friction and improve customer continuity.

---

## 3.5 Senior Citizens Have Higher Churn Risk

| Customer Group      | Churn Rate |
| ------------------- | ---------: |
| Senior Citizens     |  **41.7%** |
| Non-Senior Citizens |      23.6% |

Senior citizens show a significantly higher churn rate.

The risk becomes especially high when combined with month-to-month contracts:

> **Senior Citizen + Month-to-Month Contract = 54.6% churn rate**

### Business implication

This segment may benefit from:

* Simplified support processes
* Dedicated customer service
* Clearer billing communication
* Personalized retention offers
* Assistance with service upgrades and payment setup

---

# 4. Retention Drivers

## 4.1 Long-Term Contracts Strongly Improve Retention

Long-term contracts are the strongest observed retention driver.

Customers with two-year contracts have a churn rate of only **2.8%**, compared with **42.7% for month-to-month customers**.

This suggests that commitment and contract stability are closely associated with customer retention.

---

## 4.2 Technical Support Is Associated With Lower Churn

| Technical Support    | Churn Rate |
| -------------------- | ---------: |
| No Technical Support |  **41.6%** |
| Technical Support    |      15.2% |
| No Internet Service  |       7.4% |

Among internet customers, those with technical support show significantly lower churn.

For Fiber Optic customers:

* Without Technical Support: **49.4% churn**
* With Technical Support: **22.6% churn**

### Insight

Technical support appears to be an important retention driver, particularly for customers using higher-value and more complex services.

### Recommendation

Technical support should be promoted as part of premium packages and offered proactively to high-risk customers.

---

## 4.3 Online Security Is Associated With Higher Retention

Customers without Online Security show a churn rate of approximately **41.8%**, while customers with Online Security show a churn rate of approximately **14.6%**.

This indicates that additional protection services may improve the perceived value of the overall customer relationship.

### Recommendation

The company should consider:

* Bundling security features
* Offering free trials
* Creating premium service packages
* Promoting security benefits during onboarding

---

## 4.4 Customers With Partners and Dependents Are More Stable

### Partner Status

| Partner     | Churn Rate |
| ----------- | ---------: |
| No Partner  |      33.0% |
| Has Partner |      19.7% |

### Dependents

| Dependents     | Churn Rate |
| -------------- | ---------: |
| No Dependents  |      31.3% |
| Has Dependents |      15.5% |

### Insight

Customers with partners or dependents show lower churn rates and longer average tenure.

This may indicate that customers with broader household service needs are more deeply connected to the provider.

### Business implication

Family-oriented bundles and multi-user service packages could improve customer retention.

---

# 5. Customer Lifetime Trends

## 5.1 Customer Value Increases With Tenure

| Tenure Group | Average Total Charges |
| ------------ | --------------------: |
| 0–1 Year     |                 ~$277 |
| 1–2 Years    |               ~$1,126 |
| 2–3 Years    |               ~$1,990 |
| 3–4 Years    |               ~$2,827 |
| 4–5 Years    |               ~$3,848 |
| 5+ Years     |           **~$5,180** |

### Insight

Customer lifetime value increases substantially as tenure increases.

Customers who remain for five or more years generate almost **19 times more average TotalCharges** than customers in their first year.

This means early churn has a major long-term financial impact.

### Business implication

Customer retention should be viewed as a long-term revenue strategy rather than simply a customer service activity.

Preventing early churn can protect significant future revenue.

---

## 5.2 Retained Customers Generate Greater Lifetime Value

Long-term customers typically have:

* Higher tenure
* Higher accumulated TotalCharges
* Greater service adoption
* Stronger contract commitment
* Lower probability of churn

The business should therefore prioritize moving customers from the high-risk early lifecycle stage toward long-term engagement.

---

# 6. Highest-Risk Customer Segments

The following customer segments require the highest retention priority:

### 1. Month-to-Month + Fiber Optic

**Churn Rate: 54.6%**

This is the highest-risk major customer segment identified in the analysis.

---

### 2. Month-to-Month + Electronic Check

**Churn Rate: 53.7%**

This combination suggests both weak contract commitment and potentially higher payment friction.

---

### 3. Senior Citizen + Month-to-Month Contract

**Churn Rate: 54.6%**

This group requires targeted service and communication strategies.

---

### 4. Month-to-Month Customers Without Technical Support

**Churn Rate: 50.4%**

Adding proactive technical support may help reduce service-related dissatisfaction.

---

### 5. New Customers With Less Than One Year Tenure

**Churn Rate: 47.4%**

This is the most important lifecycle stage for proactive retention.

---

# 7. Practical Recommendations to Reduce Churn

## Recommendation 1: Build a First-Year Retention Program

The first year has the highest churn risk.

### Actions

* Create onboarding journeys for new customers
* Conduct satisfaction checks at 30, 60, and 90 days
* Monitor early complaints and support interactions
* Offer renewal incentives before the first contract period ends
* Provide personalized service recommendations

### Expected impact

Reducing early-stage churn can protect future customer lifetime value.

---

## Recommendation 2: Convert High-Risk Customers to Longer Contracts

Focus on month-to-month customers, particularly:

* Fiber Optic customers
* Electronic check users
* Senior citizens
* Customers without technical support

### Actions

* Offer discounted annual plans
* Provide price protection
* Offer free service upgrades
* Create personalized contract upgrade campaigns

---

## Recommendation 3: Promote Automatic Payment Methods

Electronic check users have a significantly higher churn rate.

### Actions

* Encourage credit card or bank transfer autopay
* Provide small incentives for automatic payments
* Simplify payment enrollment
* Send payment reminders and renewal notifications

---

## Recommendation 4: Use Technical Support as a Retention Tool

Technical support is associated with lower churn, especially among Fiber Optic customers.

### Actions

* Offer free technical support trials
* Automatically recommend support to high-risk customers
* Create premium support bundles
* Contact customers after repeated service issues

---

## Recommendation 5: Investigate Fiber Optic Customer Experience

Fiber Optic customers have a **41.9% churn rate**, significantly higher than DSL customers.

The business should investigate:

* Pricing competitiveness
* Network reliability
* Installation issues
* Service quality
* Customer support performance
* Competitor offers

The particularly high churn rate among month-to-month Fiber Optic customers makes this a priority segment.

---

## Recommendation 6: Develop Customer Risk Scoring

A churn-risk scoring model can identify customers most likely to leave.

### High-risk indicators

* Month-to-month contract
* Low tenure
* Fiber Optic service
* Electronic check payment
* No technical support
* No online security
* Senior citizen status

Customers with multiple risk factors should receive proactive retention campaigns.

---

# 8. Suggested Retention Strategy

A practical retention strategy can be organized into three stages.

### Stage 1: Identify

Use customer data to identify high-risk customers based on:

* Contract type
* Tenure
* Service type
* Payment method
* Support usage
* Customer characteristics

### Stage 2: Engage

Provide personalized interventions such as:

* Contract upgrade offers
* Technical support
* Payment method incentives
* Security service trials
* Customer satisfaction follow-ups

### Stage 3: Retain

Measure the effectiveness of each intervention using:

* Churn rate
* Contract upgrades
* Customer tenure
* Customer lifetime value
* Retention campaign conversion rate

---

# 9. Key Business Takeaways

1. **Customer churn is concentrated among month-to-month customers.**
2. **The first year is the most critical period for retention.**
3. **Long-term contracts are strongly associated with lower churn.**
4. **Fiber Optic customers represent a major churn-risk segment.**
5. **Electronic check users show significantly higher churn.**
6. **Technical support and online security are associated with stronger retention.**
7. **Customers with longer tenure generate significantly greater lifetime value.**
8. **The most effective retention strategy should combine lifecycle management, contract conversion, proactive support, and personalized risk targeting.**

---

## Conclusion

The analysis shows that customer churn is not evenly distributed across the customer base. Churn is concentrated among customers with **short tenure, month-to-month contracts, Fiber Optic services, electronic check payments, and limited support services**.

The strongest retention opportunity is to intervene early in the customer lifecycle and convert high-risk customers into longer-term relationships.

A data-driven churn reduction strategy should focus on:

> **Early onboarding → Risk identification → Personalized intervention → Long-term contract conversion**

By targeting the highest-risk customer segments before they churn, the business can improve retention, increase customer lifetime value, and protect future revenue.
