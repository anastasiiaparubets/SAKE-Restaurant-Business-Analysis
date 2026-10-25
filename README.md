# SAKE-Restaurant-Business-Analysis
Business analysis case study exploring restaurant delivery performance, customer cancellations, operational bottlenecks, and potential business improvements using Google Sheets and PostgreSQL.
# SAKE Restaurant | Business Analysis Case Study


## Project Overview

This repository presents an independent business analysis portfolio project focused on **SAKE Restaurant**, a fictional restaurant and delivery business.

The project investigates declining delivery performance despite increasing order volumes, identifies potential operational bottlenecks, and proposes improvements to enhance service quality and customer experience.

The analysis covers **April–July** and combines data analysis, business process modeling, and solution development.

**Project type:** Independent Business Analysis Portfolio Project  
**Industry:** Food Delivery & Restaurant Operations  
**Tools:** Google Sheets, PostgreSQL, SQL, JetBrains DataGrip

---

## Business Problem

SAKE Restaurant experienced increasing order volumes alongside declining operational performance.

The analysis focuses on several key challenges:

- Increasing average delivery times
- Growing percentage of late deliveries
- Rising customer cancellation rates
- Increasing customer support contacts
- Declining courier ratings
- Potential inefficiencies in courier assignment

**Main business question:**

> How can SAKE Restaurant improve delivery efficiency and customer satisfaction while maintaining business growth?

---

## Data Analysis

The project uses a simulated order-level dataset covering four months.

### Data Preparation

Google Sheets was used to prepare and validate the dataset before analysis.

### SQL Analysis

PostgreSQL queries were developed and executed using JetBrains DataGrip.

The analysis includes:

1. **Monthly KPI Overview**  
   Tracking order volumes, completion rates, cancellations, delivery times, service ratings, and customer support contacts.

2. **Month-over-Month Changes**  
   Comparing monthly performance using SQL window functions, including `LAG()`.

3. **Delivery Bottleneck Analysis**  
   Examining preparation time, courier assignment time, and delivery time to identify operational inefficiencies.

4. **Delay & Customer Behaviour**  
   Comparing delayed and non-delayed orders to investigate differences in customer support interactions and service ratings.

5. **Business Impact Estimation**  
   Estimating potentially retained orders and additional gross merchandise value (GMV) under an improved cancellation-rate scenario.

---

## Key Findings

The analysis identified several concerning trends between April and July:

| KPI | April | July |
|---|---:|---:|
| Total Orders | 2,323 | 2,663 |
| Average Delivery Time | 38.33 min | 51.76 min |
| Late Delivery Rate (>15 min) | 8.63% | 28.91% |
| Customer Cancellation Rate | 3.79% | 7.89% |
| Average Courier Rating | 4.71 | 4.38 |

### Main Observation

**Order volume increased, but operational efficiency and customer experience deteriorated.**

The analysis suggested that courier assignment and delivery operations were important areas for further investigation.

---

## Business Analysis Approach

The project extends beyond SQL analysis to examine the operational processes behind the performance trends.

### Root Cause Analysis

Potential contributing factors were explored through structured hypotheses, including changes in courier assignment processes and courier compensation.

These factors were treated as hypotheses requiring validation rather than confirmed causes.

### Process Modeling

**As-Is Process:**  
Mapping the existing delivery workflow and identifying potential inefficiencies.

**To-Be Process:**  
Designing an improved workflow aimed at reducing delays and improving courier assignment efficiency.

### Proposed Improvements

Recommendations include:

- Reviewing courier assignment logic
- Improving delivery process efficiency
- Monitoring operational KPIs
- Testing changes through a controlled pilot
- Evaluating additional courier retention and motivation initiatives

---

## Business Impact

The project includes a scenario-based business impact assessment.

The SQL analysis estimates the potential number of orders retained if July's customer cancellation rate had remained at June's level.

It also calculates the corresponding potential additional GMV based on average order value.

These calculations illustrate possible business outcomes rather than guaranteed financial results.

---

## Repository Structure

```text
SAKE-Restaurant-Business-Analysis/
│
├── README.md
│
├── presentation/
│   └── SAKE_Business_Analysis.pdf
│
├── sql/
│   └── sake_analysis.sql
│
├── data/
│   └── sake_orders.csv
│
└── screenshots/
    └── SAKE_SQL_vertical.pdf
```

### Repository Contents

- **Presentation:** Complete business analysis case study, including findings, process models, and recommendations.
- **SQL:** PostgreSQL queries used to calculate KPIs, analyze operational performance, and estimate business impact.
- **Data:** Simulated order-level dataset used for the analysis.
- **Screenshots:** Visual documentation of SQL development in JetBrains DataGrip.

---

## Skills Demonstrated

**Business Analysis**
- Problem identification
- KPI definition and analysis
- Root cause hypothesis development
- Business process modeling (As-Is / To-Be)
- Solution evaluation
- Business impact estimation

**Technical Skills**
- SQL (PostgreSQL)
- Common Table Expressions (CTEs)
- Window functions
- Data cleaning and validation
- Data aggregation
- Performance comparison

**Analytical Skills**
- Trend analysis
- Operational bottleneck identification
- Data-driven decision-making
- Translating analytical findings into business recommendations

---

## Project Takeaway

This project demonstrates how business analysis can connect operational data with business processes and decision-making.

Rather than focusing exclusively on reporting performance metrics, the analysis explores **why performance may be declining, which processes require attention, and how potential improvements could be evaluated**.

---

## Disclaimer

SAKE Restaurant is a fictional business, and the dataset is simulated for portfolio and educational purposes.

All findings, hypotheses, financial estimates, and recommendations are part of an independent business analysis case study.

---

**Author:** Anastasiia Parubets  
**Project:** SAKE Restaurant — Business Analysis Portfolio Case Study
