# uK Train 

![Data Model](modellinng.png)  <!-- Add your data model image here -->

## Project Overview
This project analyzes **mock National Rail train ticket data** in the UK from **Jan–Apr 2024**. The dataset includes ticket types, travel dates & times, departure & arrival stations, prices, and journey status.  

The data was **messy**, so I **cleaned it using Power Query**, developed a **star schema data model**, and connected relationships between the fact and dimension tables.  

The goal is to provide actionable insights using **Power BI**, **DAX**, and **data modeling**.

---

## Tools Used
- **Power BI**  
- **DAX** (for KPIs and measures)  
- **Power Query** (for data cleaning & transformation)  
- **Data Modeling** (Fact & Dimension tables)  

---

## Executive Summary (KPIs)
| KPI | Value | Description |
|-----|-------|-------------|
| **Total Trips** | 35K | Total number of journeys recorded |
| **Total Revenue** | 742K | Total revenue generated from tickets |
| **On-Time Performance** | 85% | Percentage of trips that arrived on time |
| **Busiest Travel Period** | Morning | Time period with highest passenger volume |

---

## Peak Travel Times
**Visual:** Column Chart / Cards  

**Insight:**  
> “Passenger travel peaks in the **morning**, with trips significantly higher than afternoon and evening periods. Morning trips were 17k, **183% higher than afternoon** and **39% higher than evening**.”

**Optional Comparison KPIs:**  
- Morning vs Afternoon %  
- Morning vs Evening %  

---

## Most Popular Routes
**Visual:** Top 10 Routes Bar Chart (+ optional Table for details)  

**Insight:**  
> “**London → Manchester** is the most popular route, followed by London → Birmingham, indicating strong commuter and intercity demand.”  

**Bonus:** Bottom 5 Departure Stations  
> “Several smaller stations have consistently low demand, highlighting potential areas for service optimization.”

---

## Revenue by Ticket Type & Class
**Visuals:**  
- Bar Chart: Revenue by Ticket Type  
- Donut/Bar Chart: Revenue by Ticket Class  

**Insight:**  
> “Revenue is primarily driven by **Advance tickets**, while **Standard passengers** contribute a higher average ticket value per journey.”  

**Optional KPI:** Average Revenue per Trip  

---

## On-Time Performance & Delay Reasons
**Visuals:**  
- Donut Chart: Journey Status (On Time, Delayed, Cancelled)  
- Bar Chart: Reasons for Delay  

**Insight:**  
> “85% of journeys were on time, 12% delayed, and 3% cancelled, showing strong overall reliability. Among delayed journeys, the majority of reasons (≈86%) are **unknown**, while the remaining delays are mainly caused by **technical issues** or **weather**.”

---

## Recommendations
- Monitor **Morning travel** to allocate additional resources during peak hours.  
- Investigate **low-demand departure stations** to optimize scheduling or marketing.  
- Track **Advance tickets** and **Standard class revenue** for pricing strategy insights.  
- Explore ways to **reduce unknown delay reasons**, improving data quality for operational decisions.

---

## Project Insights Summary
- The **data was messy**, but after cleaning and **developing a data model**, insights were clear.  
- **Morning trips dominate**, revenue is led by **Advance tickets**, and on-time performance is strong.  
- Delay causes are mostly **unknown**, indicating a need for **better tracking systems**.  
- This dashboard provides a **full picture for management and operational decisions**.

---

