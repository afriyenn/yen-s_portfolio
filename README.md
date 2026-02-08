# yen-s_portfolio
Business &amp; Data Analytics Portfolio


# 📊Project Sales Performance Dashboard 
  
_**How did the Field Activation Program impact business growth and growth quality?**_

## 1.1 Project Background

Tripio is a mid-sized transportation booking platform operating across multiple regions in Indonesia. Between 2022 and 2024, the company experienced steady growth driven by online channels. In September 2024, Tripio expanded its offline acquisition efforts through a field activation program at major transportation hubs, aiming to accelerate app adoption and ticket sales. While this initiative successfully increased transaction volume, management began questioning whether the growth translated into sustainable revenue performance.This project was initiated to evaluate overall sales performance, assess the impact of different sales channels, and identify whether increased volume reflected healthy business growth.

**BIG BUSINESS QUESTION:** Is Tripio’s recent sales growth driven by healthy customer value, or by low-quality volume from offline activation?

Insights and recommendations are provided on the following key areas:

- **Sales Trend Analysis:** Evaluation of historical sales patterns, both globally and by region, focusing on Revenue, Ticket Sold, and Average Ticket Price.
- **Product Level Performance:** An analysis of Tripio's various transport operators, understanding their impact on sales and returns.
- **Channel Performance:** Measure the growth of sales coming from Apps to drive digital transformation and apps downloads.
- **Regional Comparison:** An evaluation of sales and ticket sold by region.

## 1.2 Data Structure & Initial Checks

**a. Data Overview**
- Orders (transaction-level)
- Customers
- Routes / Products (AKDP vs long-distance)
- Channels (Online, Field Activation)
- Regions
- Dates


**b. Data Overview**
- Spike validation post-activation
- AOV consistency across channels
- Route distance vs. revenue distribution
- Channel misclassiffication (offline orders recorded as online)

## 1.3 Executive Summary

### a. Overview of Findings

In 2025, Tripio experienced strong growth in ticket volume (+218% YoY), showing that demand expanded significantly across routes and channels. However, this growth was largely driven by lower-priced tickets, as reflected in a sharp decline in average ticket price (-47% YoY), indicating a shift toward shorter-distance routes or more aggressive pricing. While revenue still grew by 69% YoY, the overall performance highlights a clear trade-off between volume growth and pricing quality, making pricing strategy and route mix key areas for further optimization.

<img width="1728" height="966" alt="image" src="https://github.com/user-attachments/assets/7c1843d3-4f6a-4ad0-aac6-1075bce0c3f0" />


## Insights Deep Dive
### Overall Sales Trend:

* Ticket volume grew aggressively in 2025, increasing by 218% YoY compared to 2024. Growth was visible from the start of the year and remained strong across most months, indicating a broad-based demand expansion rather than a one-off spike.
  
* Revenue also increased by 61% YoY, but at a much slower pace than ticket growth. This gap suggests that growth was primarily driven by higher transaction volume instead of higher value per transaction.
  
* The strongest divergence between volume and revenue appeared in the first half of the year, where ticket growth exceeded 300% YoY while revenue growth remained below 40% in several months. This highlights an early-year growth strategy that prioritized scale over monetization efficiency.
  
* December marked a notable inflection point, with both ticket volume (+88% YoY) and revenue (+155% YoY) accelerating simultaneously. This indicates that peak travel periods still play a key role in driving revenue uplift, even within a high-volume growth model.

<img width="765" height="299" alt="image" src="https://github.com/user-attachments/assets/84eda1f5-960d-466b-a47d-5f7312d6e46e" />


### 2025 Volume-Led Growth: Tickets Sold vs. AOV Trend

* Growth in 2025 was clearly volume-led, not value-led Ticket volume increased sharply in the first half of the year, peaking around March–April, while AOV continued to trend downward over the same period. This divergence suggests that sales growth was primarily driven by adding more transactions rather than increasing customer value per order.
  
* The lowest AOV period coincided with the most aggressive volume expansion between May and July, AOV reached its lowest levels (around Rp100–105K) at the same time ticket volumes remained elevated. This pattern indicates a deliberate trade-off: Tripio accepted lower average prices to sustain demand growth, likely through more short-distance routes or price-led acquisition efforts.
  
* Volume alone was not sufficient to stabilize revenue momentum despite relatively high ticket volumes in mid-year, overall performance softened as AOV remained suppressed. This shows that beyond a certain point, additional volume could not fully compensate for declining ticket value, limiting revenue scalability under the existing pricing mix.
  
* Year-end performance shows pricing power still exists in peak periods. In November and especially December, AOV rebounded significantly alongside a sharp increase in ticket volume. This suggests that during peak travel periods, Tripio can capture higher-value demand, indicating that the low-AOV trend throughout the year is more structural than seasonal—and potentially adjustable.

<img width="1533" height="625" alt="image" src="https://github.com/user-attachments/assets/09f0727f-3482-4f3e-8923-75927b1a3986" />


### 2025 Route Type & Demand Mix Based on #Ticket Sold

* Throughout mid-2025, ticket growth was increasingly driven by short-distance routes, peaking at around 70% of total tickets in July. This marked a clear shift in demand mix compared to early 2025, where long-distance routes still dominated.
  
* The rise of short-distance routes coincided with the lowest AOV levels of the year, reinforcing that volume growth during this period came from lower-priced products rather than higher customer value.
  
* Starting in Q4, the route mix began to rebalance, with long-distance routes recovering to ~55% share. This shift aligned with improvements in both AOV and revenue performance toward year-end.
  
* Overall, the data suggests that 2025 growth was structurally volume-led in mid-year due to short-distance expansion, while long-distance routes remained the primary driver of value during peak periods.

<img width="1534" height="550" alt="image" src="https://github.com/user-attachments/assets/318418d2-1f27-46fd-b0ad-5f152a6c1c3a" />



### Category 4:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 4]



# Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)
  
* Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)
  
* Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)
