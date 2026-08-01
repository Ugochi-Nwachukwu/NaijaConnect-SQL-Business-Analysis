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

📍 What is the average age per subscription plan?  

<img width="581" height="305" alt="image" src="https://github.com/user-attachments/assets/16002225-17d3-4dab-9185-ffa93e7dd792" />

Premium subscribers tend to be older, while Standard and Basic plans attract relatively younger customers.

Business Implication:  NaijaConnect can use this insight to tailor marketing campaigns by age group. Premium plans may be better promoted with value‑added services appealing to older professionals, while Standard and Basic plans can be positioned for younger, cost‑sensitive customers.


📍 Which regions generate the most revenue?

<img width="622" height="345" alt="image" src="https://github.com/user-attachments/assets/82d20394-489d-49cf-ac02-9f6a18bf37c8" />

North West (NW) region generates the highest revenue while North Central (NC) region contributes the least.

Business Implication: NaijaConnect can use this insight to prioritize investment and marketing efforts in high‑revenue regions like NW and SW, ensuring infrastructure and customer support are strengthened where demand is highest. At the same time, the lower‑performing regions (NC and SE) may require targeted promotions, localized campaigns, or improved service delivery to boost revenue contribution.


📍Which subscription plan contributes the most revenue? 

<img width="776" height="316" alt="image" src="https://github.com/user-attachments/assets/65dc23fb-73c2-4b43-a7fa-8c216081eaac" />

This result shows that premium customers are is driving financial performance. with this, Naijaconnect would avoid spreading resources too thin or misallocate them.

Business Implication: Since Premium generates the bulk of revenue, NaijaConnect should prioritize maintaining and enhancing Premium features to keep high‑value customers satisfied.
Then for Standard or Basic plans, management can investigate whether pricing, features, or marketing need adjustment. Understanding revenue distribution across plans prevents over‑reliance on one plan and encourages diversification.


📍 Who are the Top 10 highest‑paying customers  
<img width="784" height="375" alt="image" src="https://github.com/user-attachments/assets/9ba729c3-43a0-40fd-beaf-f3be2cfa0b90" />

This query identifies the top 10 customers who contribute most financially to NaijaConnect.

Business Implication:  Knowing who the highest‑paying customers are allows NaijaConnect to design loyalty programs, personalized offers, and premium support services tailored to these valuable clients. Retaining them is critical because losing even a few high‑value customers could significantly impact overall revenue. Additionally, analyzing their demographics and plan choices can guide marketing strategies to attract similar high‑value profiles in other regions.


📍What is the churn rate by subscription plan?

<img width="784" height="317" alt="image" src="https://github.com/user-attachments/assets/b1a4e4ab-c3a2-4647-8a48-8ac12ed34943" />

The results show that Basic and Premium plans have the highest churn rates, while Standard plans perform slightly better in retaining customers.

Business Implication:  High churn rates indicate dissatisfaction or weak value perception among customers. For NaijaConnect, this insight highlights the need to investigate why customers are leaving, it could be due to pricing, service quality, or competition. Management can use this information to redesign plan features, improve customer support, or introduce loyalty incentives. Reducing churn is critical because retaining existing customers is often more cost‑effective than acquiring new ones.

📍 What are the subscription join date trends for both customer count and revenue?

<img width="785" height="364" alt="image" src="https://github.com/user-attachments/assets/f04fefa1-589a-4384-8e0a-70847dc22691" />

This query shows both the number of customers who joined each month and the total revenue they generated. February stands out as the top month for both customer acquisition and revenue, confirming it as a peak period for NaijaConnect.

Business Implication: By combining customer count and revenue, NaijaConnect gains a complete picture of seasonal performance. February’s dominance suggests that campaigns, promotions, or external factors in that month drive both sign‑ups and spending. Management can use this insight to Forecast demand and revenue more accurately, Replicate February’s success in weaker months through targeted promotions and Align marketing and infrastructure planning with peak periods to maximize growth.


## Skills Demonstrated
• Data Transformation and Extraction: Transforming data in SQL

• Data Processing and Cleaning: Correcting errors and inconsistencies in data using SQL

• Data Analysis: Gaining comprehensive insights by handling exploratory analysis on the dataset.

• Critical Thinking and Problem-Solving: Solving business problems by using the right functions to query data.

## Recommendation
• Focus investment and customer support in high‑revenue regions (NW, SW). Launch localized promotions in weaker regions (NC, SE) to boost adoption.
 
• Protect Premium customers with loyalty programs and enhanced features since they drive most revenue. Investigate churn in Basic plans and adjust pricing or features to improve retention.
 
• Retain high‑value customers with premium support and exclusive benefits. Use their demographics and plan choices to attract similar profiles in other regions.

• Introduce incentives for churn‑prone plans. Monitor suspended accounts closely to prevent churn. Focus on retention since keeping existing customers is more cost‑effective than acquiring new ones.

• Replicate February’s success in weaker months through targeted promotions. Align marketing and infrastructure planning with peak periods to maximize growth.


## Conclusion
This project demonstrates how SQL can transform raw telecom data into actionable insights, guiding NaijaConnect’s strategy for customer growth and revenue optimization.lighting seasonal trends in customer activity.
