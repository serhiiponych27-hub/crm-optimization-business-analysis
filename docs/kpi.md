# KPI Framework

## Overview

The KPI framework defines key performance indicators used to monitor sales pipeline performance and CRM adoption.

These metrics help management evaluate sales efficiency, identify bottlenecks in the pipeline, and forecast revenue more accurately.

---

# Core Sales KPIs

## Win Rate

Definition  
Percentage of Opportunities that are successfully converted into deals.

Formula  

Win Rate = Won Opportunities / Total Closed Opportunities

Purpose  

- measure effectiveness of the sales process
- identify changes in sales performance over time

---

## Conversion Rate by Stage

Definition  
Percentage of Opportunities that successfully move from one stage of the pipeline to the next.

Formula  

Stage Conversion Rate = Opportunities entering next stage / Opportunities in current stage

Purpose  

- identify bottlenecks in the sales funnel
- detect stages with the highest drop-off rate

---

## Average Sales Cycle

Definition  
Average number of days required to convert an Opportunity into a closed deal.

Formula  

Average Sales Cycle = Average (Won Date − Opportunity Created Date)

Purpose  

- measure sales efficiency
- forecast deal closing timelines

---

## Overdue Opportunities

Definition  
Number of Opportunities that have no follow-up activity within the defined SLA period.

Purpose  

- monitor sales discipline
- identify neglected opportunities

---

## Top Lost Reasons

Definition  
Distribution of reasons why Opportunities are lost.

Data Source  

LostReason entity associated with OpportunityLost records.

Purpose  

- identify structural issues in the sales process
- support product and pricing improvements

---

## Sales Performance by Manager

Definition  
Comparison of sales metrics across different sales managers.

Key metrics  

- number of Opportunities
- win rate
- average sales cycle
- revenue generated

Purpose  

- identify top performers
- detect training needs

---

## Revenue Forecast

Definition  
Projected revenue based on current pipeline opportunities and their probability of closing.

Formula  

Forecast Revenue = Σ (Opportunity Value × Probability)

Purpose  

- support financial planning
- improve management visibility into future revenue.
