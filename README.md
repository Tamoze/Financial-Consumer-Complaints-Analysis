## Financial-Consumer-Complaints-Analysis

## Introduction

The Financial Consumer Complaints project explores over 62,000 consumer complaints submitted to the Consumer Financial Protection Bureau (CFPB) concerning Bank of America from 2017 to 2023. Using Power BI, the project delivers interactive and insightful visualizations that help uncover trends in complaint types, products, resolution methods, and company response times.

This project is particularly relevant for stakeholders interested in customer service analytics, financial compliance, and operational performance in the banking sector.

## Table of Contents
- [Project Overview](#project-overview)
- [Project Scope](#project-scope)
- [Business Objectives]  
- [Document Purpose] 
- [Use Case] 
- [Data Source]  
- [Dataset Overview] 
- [Data Cleaning and Processing]  
- [Data Analysis and Insights] 
- [Recommendation]
- [Conclusion](#conclusion)

---

### Project Overview
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

The key metrics for this analysis include:
- Total Complaints Submitted: 62,516
- Total Submission Channels: 7
- Number of Products: 9
- Number of Sub-Products: 47
- Number of Issues Identified: 76
- Number of Sub-Issues Identified: 47
- Number of States Reporting Complaints: 51
- Number of Response Strategies/Approaches: 5

This analysis provides insights into various dimensions of consumer complaints, including:
- Total Complaints Received per Quarter
- Seasonal Trends of Consumer Complaints
- Monthly and Yearly Complaint Trends
- Issues Identified per Product and Sub-Product
- Top 10 Most Frequent Issues
- States with the Highest Complaint Volumes
- Prompt Response Rates and Response Approaches
- Products with Responses in Progress
- Top 10 Issues with Response in Progress
- Top 10 Issues with Delayed Responses
- Complaint Channel Distribution

These insights aim to guide data-driven decision-making for improving customer experience and response effectiveness in the financial services sector.

# 📊 Consumer Complaint Trends
  **🔍 Seasonal Trends**
![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Seasonal%20complaints.png)
- Q3 recorded the highest number of complaints (16,952), closely followed by Q2 with 16,641.
- Q1 had 14,662 complaints, while Q4 had the lowest with 14,261.
  
This shows a clear spike in consumer complaints during mid-year (Q2 and Q3), likely driven by seasonal or operational factors.

  **📅 Trends of Consumer Complaints by Month**
  
![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Complaints%20by%20month.png)

This shows that:
- Complaint volume rises steadily from February (3,130) to July (4,458), peaking in mid-summer.
- After July, complaints begin to decline, with the lowest reported in December (3,190).

Key monthly figures:
- Highest months: July (4,458), May (4,000), June (3,852)
- Lowest months: February (3,130), November (3,212), December (3,190)

This trend suggests increased customer friction or service interaction during warmer months or fiscal midpoints.

  **📆 Trends of Consumer Complaints by Year (2017–2023)**
  
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

  # 📌 Insights on Issues by Product, Sub-Product, and Issue Type

**🏦 Number of Issues Identified Per Product**

![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Number%20of%20issues%20identified%20per%20product.png)

Complaint volume by product category shows clear trends in which services cause the most friction:
- Checking or savings accounts dominate with 24,814 issues, showing that routine banking services are the most problematic area for consumers.
- Credit cards or prepaid cards follow with 16,197 issues.

Other notable products:
- Credit reporting/credit repair – 7,710
- Mortgage – 6,661
- Money transfer, virtual currency – 3,453
- Debt collection - 2,736
- Vehicle loan or lease - 633
- Payday loan, title loan or personal loan - 333
- Student loan - 39

This distribution shows that while traditional banking leads in volume, financial products involving third parties (like credit reports and transfers) also account for a large portion of issues.

**10 Most Frequent Issues Across Products**

![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/10%20Most%20Frequent%20Issues%20Across%20Products.png)

The analysis of complaint issues reveals a strong concentration in a few problem areas:
- Managing an account leads by a wide margin with 15,109 complaints, indicating customer difficulty in day-to-day account operations.

  Other high-frequency issues include:
- Incorrect information on report – 4,931
- Problems with a purchase shown on statement – 4,415
- Closing an account – 2,953
- Trouble during payment process – 2,827
- Opening an account - 2,725
- Problem with a lender or other company charging your account - 2,493
- Fraud or scam - 1697

These reflect concerns around basic account operations, transactional disputes, and information accuracy — all critical aspects of financial trust and user experience.

**🧾Top 10 Issues Identified Per Sub-Product**

![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Top%2010%20issues%20idenntied%20per%20sub%20product.png)

The sub-product breakdown gives deeper granularity into where issues cluster:
- Checking accounts again top the list with 20,768 issues, reaffirming the need for better experience and support in this basic financial service.
- General-purpose credit cards – 13,404
- Credit reporting – 7,340

Other sub-products of concern include:
- Conventional home mortgage – 3,767
- Other banking products or services – 2,568
- Government benefit cards – 2,429
- Domestic (US) money transfer -  1,773
- Credit card debt - 1697
  
These results indicate that daily-use and high-volume products (e.g., checking accounts, credit cards, and credit reports) are most susceptible to dissatisfaction and confusion.

*🔍 Summary of Product & Issue Insights*
- Consumers struggle most with basic financial operations, particularly managing and closing accounts.
- Checking accounts and general-purpose credit cards are the most complaint-prone sub-products.
- There’s a strong need for clearer communication, proactive dispute resolution, and process simplification for frequently used products.

  # 🌎 Geographic Insights: Top 10 States by Complaint Volume

**📍 State-Level Complaint Distribution**

![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/10%20Top%20State%20with%20Highest%20Complaints.png)
- California (CA) ranks #1 by a large margin with 13,709 complaints—over double that of the next state. This reflects its large population and high concentration of financial product users.
- Florida (FL) follows with 6,458 complaints, also showing high engagement or dissatisfaction levels with financial services.

Other top states include:
- Texas (TX): 4,656
- New York (NY): 4,442
- Georgia (GA): 2,921
- New Jersey (NJ): 2,654
- Illinois (IL): 2,270
- Massachusetts (MA): 2,141
- Maryland (MD): 1,959
- Virginia (VA): 1,731

*🧠 What This Means:*
- These states likely have large urban populations, diverse financial product users, and greater awareness of consumer protection rights—leading to higher reporting.
- It may also reflect regional differences in service quality, financial regulation, or banking infrastructure.
- California's dominance highlights the need for localized customer support strategies in high-volume states.

  # 🛠️ Resolution Types

**🧾 Response Distribution Overview**

![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Responses%20Approaches%20for%20submitted%20complaints.png)

There are 5 different types of response approaches adopted from the chart:
- Closed with explanation is by far the most common response type, accounting for 41,044 complaints.
- Closed with monetary relief follows, representing 14,697 responses — showing that in many cases, consumers were compensated.
- Closed with non-monetary relief was issued in 5,273 cases, indicating that adjustments or corrections were made without financial reimbursement.
- In progress responses stand at 1,494, showing a small number of complaints still under review.
- Only 8 complaints were marked as simply “Closed”, indicating that almost all cases were followed up with at least a basic resolution status.

*💡 What This Means:*
- The high number of “Closed with explanation” responses suggests that many complaints stem from misunderstandings or miscommunication — an opportunity for better consumer education and clearer policies.
- Monetary and non-monetary relief combined (≈20,000 cases) highlights the importance of resolution integrity and fairness in customer service.
- The very low number of pending or unresolved complaints (<2.5%) reflects well on response efficiency but should still be monitored to ensure timely closure.

  # ⏱️ Timeliness of Response
  
  **📊 Prompt Response Rate**

  ![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Prompt%20Response%20Rate.png)

  The chart shows that:
 - 93.77% of complaints received a prompt response, which shows a strong level of responsiveness by the organization.
- 3.84% were not responded to promptly, which may signal potential gaps in handling specific complaint types or workflow inefficiencies.
- A very small portion (indicated in yellow) is missing data, suggesting some issues in data recording or reporting consistency.

*💡 Insight:*
- Overall, the organization demonstrates excellent responsiveness. However, attention should be given to the few cases not promptly addressed, especially to understand any systemic causes or patterns.
- While most responses were timely, **untimely responses** were often linked to disputes or complex product categories.
- Delay patterns often appeared in **credit-related** complaints.

  ** 🔄 Top 10 Issues with Response in Progress**
  
  ![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Product%20with%20Response%20in%20Progress.png)
  
The bar chart reveals that the issues still being worked on include:
- Managing an account (380 cases) – again appearing prominently, reinforcing it as a high-friction area.
- Opening an account (100 cases) and Problem with a credit reporting company's investigation (93 cases) also dominate.

  Other areas of issues with response in progress are:
- Closing an account	83
- Incorrect information on your report	80
- Other features, terms or problem	67
- Problem with a purchase shown on your statement	63
- Improper use of your report	62
- Problem caused by your fund being low	52
- Getting a credit card	50

*💡 Insight:*
- The majority of unresolved complaints revolve around account lifecycle issues — from opening, managing, to closing — and credit report accuracy. 
- This indicates ongoing friction in core banking operations, compliance reporting, and transactional clarity.

  **⏳ Top 10 Issues with Delayed Response**
  
![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Top%2010%20Issues%20with%20delayed%20response.png)
  
From the bar chart, the most delayed issues are:
- Managing an account (497 cases) – the most affected, indicating a process or support bottleneck in account-related services.
- Incorrect information on credit reports (322 cases) – this likely involves third-party verification delays.
- Problems with a purchase shown on your statement (197 cases) and Attempting to collect debt not owed (118 cases) are also notable.

   Other areas of issues with response in progress are:
- Closing an account	116
- Opening an account	107
- Problem with a credit reporting company’s investigation	99
- Problem with a lender or other company charging your account	99
- Fraud or scam	80
- Improper use of your report	80
  
*💡 Insight:*

The top delayed issues mirror the “in progress” ones, with "Managing an account" again leading. Delay-prone complaints tend to involve third-party interactions, data disputes, or fraud investigations, which are more complex and time-consuming.

  # Complaint Channel Distribution

![](https://github.com/Tamoze/Financial-Consumer-Complaints-Analysis/blob/main/Complaint%20channel%20distribution.png)

The chart shows how customers are submitting complaints across different platforms.

| Channel         | Percentage |
|-----------------|------------|
| Web             | 72.66%     |
| Referral        | 17.22%     |
| Phone           | 7.49%      |
| Email           | 2.11%      |
| Web Referral    | 0.14%      |
| Others          | 0.38%      |

*📌 Insight:*
- Digital-first trend: The web dominates as the main complaint channel.
- Referral usage indicates the value of external bodies like regulators or advocacy groups.
- Phone and email still serve those preferring traditional channels.

---

## ✅ General Recommendations

**1. Proactively Manage High-Risk Complaint Categories**
- Prioritize resolution for frequently reported issues such as managing an account, incorrect credit report information, and fraud or scams.
- Introduce dedicated resolution workflows and specialized response teams to reduce delays and repeat complaints.

**2. Target Top States with High Complaint Volumes**
- Focus attention on complaint-heavy states like California, Texas, Florida, and Georgia.
- Allocate regional support resources, targeted consumer education, and policy adjustments to address regional drivers of dissatisfaction.

**3. Enhance Mid-Year Support Capacity (Q2–Q3)**

Since Q2 and Q3 (April to September) register the highest complaint volumes, institutions like Bank of America should:
- Scale up customer service staffing during these months.
- Launch proactive outreach to address common seasonal complaint types.
- Ensure system reliability and uptime, especially for online and mobile banking platforms during this peak period.

**4. Boost Response Timeliness and Efficiency**

Although prompt response is generally strong, a significant portion of complaints remain "In Progress" or are resolved with delay.

Recommendations:
- Implement automated routing and triage systems to prioritize and speed up case handling.
- Conduct regular audits of delayed responses to identify root causes and resolve procedural inefficiencies.

**5. Monitor and Improve Product-Specific Complaint Channels**
- Allocate more attention to products with high complaint volumes.
- Encourage product and compliance teams to analyze recurring complaint trends.
- Update call center scripts and agent training to reflect the latest pain points and resolutions.

**6. Leverage Predictive Analytics**
- Use historical complaint patterns to forecast complaint surges by:

 Month, season, or product/service.
- Deploy AI-driven early warning systems to detect and respond to emerging issues in real-time.

**7. Strengthen Complaint Resolution Approaches**

A large proportion of cases are closed with explanations, which may not fully satisfy customers.
- Shift from reactive justification to proactive resolution strategies.
- Consider post-resolution feedback loops to improve quality and consistency.

**8. Improve Web-Based and Multichannel Experiences**

Since 72.66% of complaints come through web, ensure:
- User-friendly online forms, responsive mobile interfaces, and interactive complaint guides.
- Explore live chat and AI-powered assistants for real-time issue triage.

- Also enhance:
  
 Phone (7.49%) and email (2.11%) support capacity for customers less likely to use online tools.
 
 Streamline referral (17.22%) and web referral (0.14%) submissions through better partner integration.

**9. Improve Self-Service Resources**
- Develop robust and updated FAQs, tutorials, and chatbot support for frequent issues.
- Promote self-resolution tools during peak complaint months to relieve customer service teams.

**10. Customer Education Campaigns**
- Launch campaigns around March and April to:
- Educate users on fees, account features, and dispute resolution.
- Minimize misunderstandings that typically spike during Q2–Q3.

**11. Evaluate and Scale Operational Changes from 2023**

The noticeable drop in complaints in 2023 indicates that implemented changes were effective.
- Conduct a retrospective review to assess which measures worked.
- Scale or replicate these best practices across departments, regions, or product lines.

**12. Establish a Continuous Improvement System**
- Integrate complaint analytics into a continuous improvement framework by:
  
  Monitoring trends and satisfaction over time.
  
  Using insights for training, policy reform, and customer service redesign.

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
