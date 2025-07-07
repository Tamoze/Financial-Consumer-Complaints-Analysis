# Financial-Consumer-Complaints-Analysis

## Introduction

The Financial Consumer Complaints project explores over 62,000 consumer complaints submitted to the Consumer Financial Protection Bureau (CFPB) concerning Bank of America from 2017 to 2023. Using Power BI, the project delivers interactive and insightful visualizations that help uncover trends in complaint types, products, resolution methods, and company response times.

This project is particularly relevant for stakeholders interested in customer service analytics, financial compliance, and operational performance in the banking sector.

## Table of Contents
- [Project Overview](#project-overview)  
- [Project Scope](#project-scope)  
- [Business Objectives](#business-objectives)  
- [Document Purpose](#document-purpose)  
- [Use Case](#use-case)  
- [Data Source](#data-source)  
- [Dataset Overview](#dataset-overview)  
- [Data Cleaning and Processing](#data-cleaning-and-processing)  
- [Data Analysis and Insights](#data-analysis-and-insights)  
- [Recommendation](#recommendation)  
- [Conclusion](#conclusion)

---

## Project Overview
This Power BI dashboard project explores consumer complaints submitted to the Consumer Financial Protection Bureau (CFPB) regarding **Bank of America** between **2017 and 2023**. The analysis focuses on complaint trends across financial products and services, examining how issues are reported and resolved, and evaluating company response patterns.

---

## Project Scope
The scope of this project includes:
- Analyzing complaint trends over a 7-year period (2017–2023).
- Identifying product categories and issues with the highest complaint volumes.
- Understanding the timeliness and nature of company responses.
- Detecting seasonal patterns in complaint submissions.

---

## Business Objectives
- Discover which financial products and issues trigger the most consumer complaints.
- Evaluate how effectively Bank of America addresses complaints.
- Understand trends in response time, dispute frequency, and submission channels.
- Identify operational inefficiencies and areas for service improvement.

---

## Document Purpose
This README serves as documentation for the Power BI dashboard and provides:
- Context on the dataset used
- Description of the analytical workflow
- Key findings and visual highlights
- Actionable insights and recommendations

---

## Use Case
This dashboard can support:
- **Banking Operations Teams** – to pinpoint service issues and improve response workflows.
- **Regulatory Affairs Departments** – to identify compliance risks and response delays.
- **Data Analysts** – seeking patterns in customer sentiment and seasonal trends.
- **Consumer Advocacy Groups** – to track complaint resolution fairness.

---

## Data Source
- **Provider**: [Maven Analytics](https://www.mavenanalytics.io/)
- **Dataset**: Consumer complaints filed with the CFPB
- **Entity Covered**: Bank of America
- **Time Period**: 2017–2023

---

## Dataset Overview
- **Total Records**: 62,516
- **Number of Fields**: 12

Key fields include:
- `Date received`
- `Date sent to company`
- `Product`, `Issue`
- `Submitted via`
- `Company response to consumer`
- `Timely response?`
- `Consumer disputed?`
- `State`, `ZIP code`

Each record represents an individual complaint submitted by a consumer.

---

## Data Cleaning and Processing
Data preparation steps included:
- Removing null values and duplicates
- Standardizing date formats and calculating submission-response time
- Normalizing product and issue categories for consistency
- Filtering to retain only complaints related to Bank of America (2017–2023)

---

## Data Analysis and Insights

### 🔍 Seasonal Trends
![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Seasonal%20complaints.png)
- Q3 recorded the highest number of complaints (16,952), closely followed by Q2 with 16,641.
- Q1 had 14,662 complaints, while Q4 had the lowest with 14,261.
  
This shows a clear spike in consumer complaints during mid-year (Q2 and Q3), likely driven by seasonal or operational factors.

### 📅 Trends of Consumer Complaints by Month
![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Complaints%20by%20month.png)

This shows that:
- Complaint volume rises steadily from February (3,130) to July (4,458), peaking in mid-summer.
- After July, complaints begin to decline, with the lowest reported in December (3,190).
- Key monthly figures:

Highest months: July (4,458), May (4,000), June (3,852)

Lowest months: February (3,130), November (3,212), December (3,190)

This trend suggests increased customer friction or service interaction during warmer months or fiscal midpoints.

### 📆 Trends of Consumer Complaints by Year (2017–2023)
![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Complaints%20by%20year.png)

This shows that complaint volumes increased consistently from 2017 (2,879) to a peak in 2022 (8,746).

A decline occurred in 2023 (6,263), possibly due to improved complaint resolution strategies or reduced service disruptions.

Year-over-year summary:

- 2017: 2,879
- 2018: 4,698
- 2019: 4,465
- 2020: 5,297
- 2021: 7,116
- 2022: 8,746
- 2023: 6,263

*🔍 Key Insight Summary*

- Complaints peak in Q3 and mid-year months, especially July and May, signaling a seasonal trend.

- December and February see the fewest complaints, suggesting calmer service periods.

- Over the years, complaint volumes rose sharply before tapering off in 2023, indicating progress in handling or preventing issues.

### 📊 Top Products with Complaints
- **Credit reporting** and **checking/savings accounts** had the highest number of complaints.
- Common issues include **incorrect information on reports** and **unauthorized transactions**.

### 🛠️ Resolution Types
- The majority of complaints are resolved with an **"Explanation"** or **"Closed with monetary relief"**.
- A significant number were closed without relief, leading to a higher dispute rate.

### ⏱️ Timeliness of Response
- While most responses were timely, **untimely responses** were often linked to disputes or complex product categories.
- Delay patterns often appeared in **credit-related** complaints.

---

## Recommendation
- **Enhance Response Workflow**: Focus on reducing delays for credit-related complaints.
- **Targeted Training**: Equip support agents with better tools to handle disputed issues.
- **Product Review**: Investigate why credit reporting triggers high complaint volumes.
- **Proactive Monitoring**: Use predictive modeling to anticipate seasonal spikes and prepare resources.

---

## Conclusion
This Power BI dashboard offers a deep dive into consumer complaints targeting Bank of America’s financial products from 2017 to 2023. It reveals critical service gaps and highlights improvement opportunities in timeliness, dispute resolution, and product support. By leveraging these insights, stakeholders can make informed, customer-focused decisions.

---


## 📸 Dashboard Preview

![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Consumer%20Complaints%20Analysis%20Page3.png)![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Consumer%20Complaint%20Analysis%20Page1.png)![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Consumer%20Compaint%20Analysis%20Page%202.png)

> *Sample Power BI dashboard showing complaint trends, top product issues, and resolution breakdown.*

---


## 🏷️ Project Badges

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?logo=powerbi)
![Dataset](https://img.shields.io/badge/Dataset-Maven%20Analytics-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
