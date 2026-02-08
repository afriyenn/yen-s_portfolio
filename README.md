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

In 2025, Tripio experienced strong growth in ticket volume (+218% YoY), showing that demand expanded significantly across routes and channels. However, this growth was largely driven by lower-priced tickets, as reflected in a sharp decline in average ticket price (-49% YoY), indicating a shift toward shorter-distance routes or more aggressive pricing. While revenue still grew by 61% YoY, the overall performance highlights a clear trade-off between volume growth and pricing quality, making pricing strategy and route mix key areas for further optimization.

<img width="1734" height="966" alt="image" src="https://github.com/user-attachments/assets/03f9d016-c8ac-4f07-9fe1-689a0768add0" />


### b. Insights Deep Dive
#### Overall Sales Trend:

* Ticket volume grew aggressively in 2025, increasing by 218% YoY compared to 2024. Growth was visible from the start of the year and remained strong across most months, indicating a broad-based demand expansion rather than a one-off spike.
  
* Revenue also increased by 61% YoY, but at a much slower pace than ticket growth. This gap suggests that growth was primarily driven by higher transaction volume instead of higher value per transaction.
  
* The strongest divergence between volume and revenue appeared in the first half of the year, where ticket growth exceeded 300% YoY while revenue growth remained below 40% in several months. This highlights an early-year growth strategy that prioritized scale over monetization efficiency.
  
* December marked a notable inflection point, with both ticket volume (+88% YoY) and revenue (+155% YoY) accelerating simultaneously. This indicates that peak travel periods still play a key role in driving revenue uplift, even within a high-volume growth model.

<img width="1725" height="676" alt="image" src="https://github.com/user-attachments/assets/ef6718f4-9377-4d56-90d1-7dc978e28ee0" />



#### Volume-Led Growth: Tickets Sold vs. AOV Trend

* Growth in 2025 was clearly volume-led, not value-led Ticket volume increased sharply in the first half of the year, peaking around March–April, while AOV continued to trend downward over the same period. This divergence suggests that sales growth was primarily driven by adding more transactions rather than increasing customer value per order.
  
* The lowest AOV period coincided with the most aggressive volume expansion between May and July, AOV reached its lowest levels (around Rp100–105K) at the same time ticket volumes remained elevated. This pattern indicates a deliberate trade-off: Tripio accepted lower average prices to sustain demand growth, likely through more short-distance routes or price-led acquisition efforts.
  
* Volume alone was not sufficient to stabilize revenue momentum despite relatively high ticket volumes in mid-year, overall performance softened as AOV remained suppressed. This shows that beyond a certain point, additional volume could not fully compensate for declining ticket value, limiting revenue scalability under the existing pricing mix.
  
* Year-end performance shows pricing power still exists in peak periods. In November and especially December, AOV rebounded significantly alongside a sharp increase in ticket volume. This suggests that during peak travel periods, Tripio can capture higher-value demand, indicating that the low-AOV trend throughout the year is more structural than seasonal—and potentially adjustable.

<img width="1728" height="706" alt="image" src="https://github.com/user-attachments/assets/cf531128-f2d0-468a-8190-0d7719b3c1e9" />


#### Route Type & Demand Mix Based on #Ticket Sold

* Throughout mid-2025, ticket growth was increasingly driven by short-distance routes, peaking at around 70% of total tickets in July. This marked a clear shift in demand mix compared to early 2025, where long-distance routes still dominated.
  
* The rise of short-distance routes coincided with the lowest AOV levels of the year, reinforcing that volume growth during this period came from lower-priced products rather than higher customer value.
  
* Starting in Q4, the route mix began to rebalance, with long-distance routes recovering to ~55% share. This shift aligned with improvements in both AOV and revenue performance toward year-end.
  
* Overall, the data suggests that 2025 growth was structurally volume-led in mid-year due to short-distance expansion, while long-distance routes remained the primary driver of value during peak periods.

<img width="1724" height="622" alt="image" src="https://github.com/user-attachments/assets/37b897cc-f1d0-44eb-996e-8a810de21020" />


#### Channel Mix & Acquisition Quality

* Offline channels consistently contributed more than half of total ticket volume throughout 2025, peaking at around 65–67% during the first half of the year. This timing aligns closely with field activation efforts and confirms offline as the primary volume engine during the growth phase.
  
* Despite higher volume, offline-acquired tickets were heavily skewed toward short-distance routes, resulting in significantly lower average ticket value. The full-year AOV for offline sales was Rp86k, less than half of online’s Rp239k, indicating a clear quality gap between the two channels.
  
* Online channels, while contributing fewer tickets overall, consistently captured higher-value demand, particularly for long-distance routes. This suggests online sales played a more critical role in revenue quality rather than raw acquisition scale.
  
* Taken together, the data shows that 2025 growth was driven by a deliberate trade-off: offline activation accelerated customer acquisition and market reach, while online channels preserved pricing power. Sustaining growth going forward will require balancing offline volume expansion with stronger value extraction through online channels.

<img width="1732" height="646" alt="image" src="https://github.com/user-attachments/assets/20fa6af7-0eac-4136-8dd3-1d4848e96a04" />


## 1.4 Recommendations:

Based on the insights above, we recommend the following actions across Operations, Sales, and Marketing teams to balance acquisition scale with long-term value creation:

* Operations — Rebalance field activation toward higher-value routes
Field activation has proven effective in generating ticket volume, but it is currently concentrated on short-distance, low-price routes. Operations should selectively prioritize activation on higher-priced and longer-distance corridors, ensuring volume growth does not come at the expense of ticket value.
  
* Operations — Introduce route-level guardrails during activation
While high volume remains important, activation programs should include basic price or route mix guardrails (e.g., minimum average fare targets per location) to prevent excessive dilution of AOV during peak acquisition periods.
  
* Sales — Prioritize onboarding of operators with strong long-distance portfolios
To offset value dilution from short-distance demand, the sales team should focus on acquiring transport operators serving longer-distance routes, where pricing power and revenue per ticket are structurally higher.
  
* Marketing — Shift online acquisition toward value-driven demand
Online channels consistently deliver higher AOV and stronger long-distance penetration. Marketing should double down on online acquisition campaigns targeted at planned, higher-intent travel, positioning online as the primary driver of revenue quality.
  
* Marketing — Convert offline-acquired users into repeat online customers
Field activation successfully introduces new passengers, but long-term value depends on retention. Marketing should actively migrate offline-acquired users to online channels through app incentives, loyalty programs, and rebooking nudges to gradually rebalance channel contribution toward a healthier mix.
  


## 1.5 Assumptions and Caveats:

* Route Type Proxy Definition

Routes were categorized into short-distance and long-distance using ticket price thresholds as a proxy for travel distance. This method highlights value and demand differences but may not perfectly represent operational classifications.

* AOV Smoothing for Analytical Clarity

Monthly AOV figures were smoothed to reduce extreme volatility caused by pricing outliers and partial-month operational changes, particularly during mid-year strategy shifts.

* Sales Type Attribution Consistency
  
Sales channels (offline vs online) were assumed to be consistently labeled across the year. Any misclassification at the transaction level may slightly affect channel-level comparisons.

* Field Activation Impact Intrepretation

Ticket volume increases during activation periods were treated as structurally driven rather than temporary anomalies, under the assumption that no short-term price subsidies were applied.

* Data Anonymization and Modification

All data used in this analysis has been anonymized and modified for portfolio purposes. Company identifiers, figures, and timelines have been adjusted to preserve confidentiality while maintaining analytical integrity.
