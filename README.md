# OTT-Merger-Analysis

As part of the Codebasics Resume Challenge #14, I created this Data Analytics Project

Link to the [Challenge](https://codebasics.io/challenge/codebasics-resume-project-challenge)

Link to [Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiM2JjZTcwZTUtMTIzMC00ZTZhLWE4YzQtNDkyMWRhYmVjMDA2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

Link to [Dashboard Video Presentation](https://youtu.be/UpXF6MSe2Ok)

## Problem Statement
Lio, a leading telecommunications provider in India, is planning a strategic merger with
Jotstar is one of the country’s most prominent streaming platforms. This potential partnership
aims to combine LioCinema’s expansive subscriber base and Jotstar’s diverse content library
to revolutionize digital streaming in India.

As part of the merger preparation, the management team at Lio wants to analyze the
performance and user behavior of both platforms—LioCinema and Jotstar—over the past
year (January to November 2024). The goal is to gain insights into individual platform
performance, content consumption patterns, subscriber growth, Inactive behavior, and upgrade
and downgrade trends. The insights derived from this study will help the management make
informed decisions and optimize content strategies post-merger, with the ultimate goal of
establishing Lio-Jotstar as the leading OTT platform in India.

### Task List

The management expects detailed insights into the following:

1. Content Library Analysis: A detailed comparison of content types across both platforms.
2. Subscriber Insights: Analyse trends in subscriber acquisition and demographic variations.
3. Inactivity Analysis: Inactivity patterns across age groups, city tiers, and subscription
plans.
4. Upgrade Patterns: Insights into subscription upgrades and their influencing factors.
5. Downgrade Patterns: Analysis of subscription downgrades and associated trends.
6. Content Consumption Behavior: Patterns in total watch time, device preferences, and
variations by user demographics. 

## Data Sources
The dashboard gathers data from:
𝐌𝐲𝐒𝐐𝐋 𝐃𝐚𝐭𝐚𝐛𝐚𝐬𝐞: Essential data is pulled from the MySQL database, consisting of two SQL files '𝐉𝐨𝐭𝐬𝐭𝐚𝐫_𝐝𝐛.𝐬𝐪𝐥' and '𝐋𝐢𝐨𝐜𝐢𝐧𝐞𝐦𝐚_𝐝𝐛.𝐬𝐪𝐥'.
Both SQL files consist of the Subscribers table, the Content table, and the Content Consumption table.

## Data Model for User Data and User Content Consumption Tables

<p align="center">
    <img src='https://github.com/Dinesh281197/OTT-Merger-Analysis/blob/main/Report%20Screenshots/User_Data_%26_Content_Consumpstion.png' height="400">
</p>

## Data Model for Content Tables

<p align="center">
    <img src='https://github.com/Dinesh281197/OTT-Merger-Analysis/blob/main/Report%20Screenshots/Content.png' height="400">
</p>

## Homepage

<p align="center">
    <img src='https://github.com/Dinesh281197/OTT-Merger-Analysis/blob/main/Report%20Screenshots/Homepage.png' height="400">
</p>

## Key Notes

<p align="center">
    <img src='https://github.com/Dinesh281197/OTT-Merger-Analysis/blob/main/Report%20Screenshots/KeyNotes%20View.png' height="400">
</p>

## Performance Overview

<p align="center">
    <img src='https://github.com/Dinesh281197/OTT-Merger-Analysis/blob/main/Report%20Screenshots/Performance_Overview.png' height="400">
</p>

## User Insights and Engagements

<p align="center">
    <img src='https://github.com/Dinesh281197/OTT-Merger-Analysis/blob/main/Report%20Screenshots/User_Insights_%26_Engagement.png' height="400">
</p>

## Subscription Trends and Revenue

<p align="center">
    <img src='https://github.com/Dinesh281197/OTT-Merger-Analysis/blob/main/Report%20Screenshots/Subsciption%20trends%20%26%20Revenue%20View.png' height="400">
</p>

## Content Library and Language Analysis

<p align="center">
    <img src='https://github.com/Dinesh281197/OTT-Merger-Analysis/blob/main/Report%20Screenshots/Content_Library_%26_Language_Analysis.png' height="400">
</p>

## What I Learned from My OTT Merger Analysis Project

### Domain Knowledge:
- **OTT Industry Insights:** Understanding how **user engagement, subscription trends, and content distribution** impact platform growth.  
- **Subscriber Behavior:** Identifying factors like **upgrade/downgrade trends, watch time, and churn rates** affecting platform performance.  
- **Content Strategy:** How **genre availability, language preferences, and content variety** shape audience retention and revenue.  

### **Data Analysis & Technical Skills:**  
**SQL Expertise:** Extracting & analyzing data from **Jotstar.sql & LioCinema.sql** for insights on user behavior & revenue.  
- **Power BI Visualization:** Creating **dynamic dashboards** with slicers for a month, age group, city tier, and device type.  
- **KPI Analysis:** Interpreting **growth rates, revenue trends, and performance metrics** to drive strategic recommendations.  
- **Correlation Analysis:** Exploring relationships between **inactive users and watch time trends** for better retention strategies.  

### **Other Key Learnings:**  
- Data-driven decision-making is **crucial for OTT success**—from content planning to pricing strategies.  
- **User engagement patterns** vary significantly based on **demographics, city tiers, and platform offerings**.  
- Mergers in the OTT space can leverage **content strengths & pricing models** to optimize market share.  

## Some Important insights from the Dashboard

- LioCinema has more than 4X the user base of Jotstar.
- Jotstar Dominates the 25-34 Age Segment – A significant portion of Jotstar's user base falls within this age group.
- LioCinema Attracts a Younger Audience – The 18-24 age group prefers LioCinema, whereas Jotstar struggles to capture this demographic.
- Jotstar’s Strength Lies in Tier 1 Cities – Most of its users come from metropolitan areas.
- LioCinema Thrives in Tier 2 & Tier 3 Cities – It has a stronger presence in smaller cities, attracting a wider audience.
- Paid Subscription Gap – A striking 72% of Jotstar’s users are paying subscribers(Premium OR VIP), while only 36% of LioCinema’s users(Premium or Basic) fall into the paid category.
- Jotstar Leads in Engagement Across All Ages – With an 80%+ active rate, Jotstar maintains strong user participation across every age group.
- LioCinema Struggles with Young Viewers – A 43% inactivity rate among the 18-24 age group suggests challenges in retaining younger audiences.
- Jotstar’s Premium Users Are Highly Engaged – With a 95% active rate, Jotstar’s premium subscribers show strong retention, followed by an 86.2% active rate in the VIP plan.
- LioCinema’s Premium Engagement Lags Behind – Its 77% active rate in the premium plan is notably lower than Jotstar’s 95% active rate in the Premium Plan.
- Jotstar’s revenue has grown by ~11.8x from Jan (0.7M) to Nov (8.3M).
- LioCinema’s revenue has grown by ~27.5x from Jan (0.2M) to Nov (5.5M), showing a strong acceleration in later months.
- Jotstar has nearly 2X the content of LioCinema.
- Jotstar has a higher upgrade rate, while LioCinema experiences a higher downgrade rate.
- Jotstar maintains an overall ratio of 1.9 (>1), indicating that for every downgrade, there are still 1.9 upgrades, keeping it in a healthy position.
- LioCinema’s overall ratio stands at 0.2 (<1), indicating that for every downgrade, only 0.2 users upgrade a clear sign of retention challenges.
- Jotstar has generated 2X more revenue than LioCinema during the analysis period.
- Jotstar outperforms LioCinema in converting free users to paid subscribers, with an overall transition rate nearly 7x higher.
