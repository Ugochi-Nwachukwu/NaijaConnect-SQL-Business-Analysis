# NaijaConnect-SQL-Business-Analysis    
SQL business analysis of NaijaConnect telecom data — uncovering customer demographics, subscription trends, payment methods, and revenue insights with actionable recommendations.

## Table of Contents
- [Problem Statement](#problem-statement)
- [Analysis Overview](#analysis-overview)
- [Data Source](#data-source)
- [Data Processing](#data-processing)
- [Skills Demonstrated](#skills-demonstrated)
- [Recommendation](#recommendation)
- [Conclusion](#conclusion)

## Problem Statement
In today’s competitive telecom environment, companies generate large volumes of transactional data daily, yet many struggle to extract meaningful insights that guide strategic decisions. NaijaConnect lacked visibility into customer demographics, revenue drivers, and subscription trends.

## Analysis Overview
📍Identifying top‑performing subscription plans.

📍Understanding customer demographics and payment preferences.

## Data Source
The dataset was imported into SQL. It contains customer details, subscription plans, payment methods, and revenue records.

## Data Processing
• Initial cleaning was performed in Excel(Power Query) to remove duplicates, fix missing values, and standardize column names.

• creating tables for the data set

-- customers table

<img width="502" height="206" alt="image" src="https://github.com/user-attachments/assets/ee8daee6-8bf1-49c9-842a-35d372283f6d" />

-- subscription table

<img width="646" height="194" alt="image" src="https://github.com/user-attachments/assets/d86f535f-7b1e-4d92-9235-2d4e1d0e6d9d" />


• The cleaned dataset was then imported into SQL for further transformation and analysis.


• Removing null values

<img width="656" height="191" alt="image" src="https://github.com/user-attachments/assets/be9ec500-1ef2-40f3-8288-1276fd0840cb" />

## Insights

What is the average age per subscription plan?  

<img width="581" height="305" alt="image" src="https://github.com/user-attachments/assets/16002225-17d3-4dab-9185-ffa93e7dd792" />

Premium subscribers tend to be older, while Standard and Basic plans attract relatively younger customers.

Business Implication:  NaijaConnect can use this insight to tailor marketing campaigns by age group. Premium plans may be better promoted with value‑added services appealing to older professionals, while Standard and Basic plans can be positioned for younger, cost‑sensitive customers.

Gender distribution across plans  
Why: Guides targeted campaigns (e.g., Premium skewing male/female).

💰 Revenue Drivers
Which subscription plan contributes the most revenue?  
Why: Identifies the most profitable plan for pricing and promotions.

Top 10 highest‑paying customers  
Why: Useful for loyalty programs and retention strategies.

Which regions generate the most revenue?  
Why: Helps management decide where to expand infrastructure or marketing.


Revenue by payment method  
Why: Shows customer preferences (Card vs USSD vs Transfer), guiding fintech partnerships.

📈 Subscription Trends
Do Premium customers use more data/voice than Standard/Basic?  
Why: Validates whether higher fees match higher usage.

Correlation between calls/SMS and revenue  
Why: Identifies which service (data, calls, SMS) drives income.

🔄 Customer Lifecycle
Churn rate by plan type


Churn rate by plan type  
Why: Shows which plans lose customers fastest, guiding retention.

Active vs suspended vs churned customers  
Why: Provides a health check of the customer base.

Join date trends  
Why: Reveals peak subscription months, useful for forecasting.




## Skills Demonstrated
• Data Transformation and Extraction: Transforming data in SQL

• Data Processing and Cleaning: Correcting errors and inconsistencies in data using SQL

• Data Analysis: Gaining comprehensive insights by handling exploratory analysis on the dataset.

• Critical Thinking and Problem-Solving: Solving business problems by using the right functions to query data.

## Recommendation
Focus marketing efforts on Premium subscribers, expand infrastructure in NW and SW regions, and design youth‑focused campaigns for Standard/Basic plans.

## Conclusion
This project demonstrates how SQL can transform raw telecom data into actionable insights, guiding NaijaConnect’s strategy for customer growth and revenue optimization.


Analyzing regional revenue distribution.

Highlighting seasonal trends in customer activity.
