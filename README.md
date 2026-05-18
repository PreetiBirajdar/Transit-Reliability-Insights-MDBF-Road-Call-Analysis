# Transit Reliability Insights: MDBF & Road Call Analysis

## Project Overview
This case study analyzes transit reliability across New York City boroughs using Mean Distance Between Failures (MDBF) and Road Call metrics. The objective is to identify borough-level performance gaps, compare reliability trends, and support maintenance-focused decision-making.
## Understanding the Key Metrics

### What is MDBF?
**MDBF stands for Mean Distance Between Failures.**  
It is a transit reliability metric that shows how many miles a bus fleet travels, on average, before experiencing a mechanical failure that results in a road call.

A **higher MDBF** generally indicates:
- Better vehicle reliability
- Fewer mechanical failures relative to miles operated
- Stronger maintenance performance

### How is MDBF calculated?

**MDBF = Total Miles Operated ÷ Total Road Calls**

For example, if buses travel **1,000,000 miles** and record **200 road calls**:

**MDBF = 1,000,000 ÷ 200 = 5,000 miles between failures**

This means the fleet experiences one failure-related road call approximately every **5,000 miles** of operation. 

---

### What is a Road Call?
A **Road Call** refers to a service-related incident caused by a mechanical problem that occurs while a bus is operating in service and requires attention or intervention.

Road calls are important because they can indicate:
- Vehicle breakdowns or mechanical issues
- Potential service disruptions
- Areas where preventive maintenance may need improvement

In reliability analysis, road calls are used as the failure count when calculating MDBF. 

---

### Why these metrics matter
MDBF and Road Calls are useful together because they help assess fleet reliability from two perspectives:

- **Road Calls** show the number of failure-related incidents.
- **MDBF** adjusts those failures for service mileage, making it easier to compare reliability across boroughs or time periods.

This allows transit agencies to identify underperforming areas, track reliability trends, and support maintenance planning decisions. 

### Reliability Benchmark
For this analysis, **For this analysis, MDBF above 6,000 miles is used as a strong reliability benchmark.**, while values below this level suggest a need for closer review of fleet performance and maintenance conditions.

A higher MDBF means vehicles are traveling farther between failure-related road calls, which generally reflects better mechanical reliability.

## Business Problem
Transit agencies need to understand where vehicle reliability is weakest and where operational failures occur more frequently. Lower MDBF and higher road call counts may indicate areas that require closer maintenance review and service improvement efforts.

## Objectives
- Compare MDBF performance across boroughs
- Analyze Road Call trends
- Identify best- and worst-performing boroughs
- Track reliability changes over time
- Present insights through an interactive Tableau dashboard

## Tools Used
- Tableau
- Excel

## Dashboard Preview
<img width="1724" height="718" alt="image" src="https://github.com/user-attachments/assets/af0962e5-fc80-4f9c-935b-d215e0e096a2" />

🔗 [View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/preetii.birajdar/viz/TransitReliabilityInsightsMDBFRoadCallAnalysis/Dashboard1)

## Key Insights

- **Overall transit reliability in 2026 reached an MDBF of 5,172**, with **8,256 road calls**, providing a high-level view of fleet performance for the year.

- **Staten Island was the best-performing borough**, recording the highest MDBF at **9,585**, which indicates stronger vehicle reliability compared with other boroughs.

- **The Bronx was the worst-performing borough**, with an MDBF of **2,694**, highlighting a potential reliability gap that may require deeper maintenance and operational review.

- Borough-level comparison shows that **reliability performance varies significantly across locations**, suggesting that maintenance effectiveness, fleet age, route conditions, or operational intensity may differ by borough.

- The historical MDBF trend table and heatmap reveal **year-over-year fluctuations in reliability**, making it easier to identify boroughs with recurring underperformance or recent improvement.

- The dashboard combines **MDBF, Road Calls, and mileage context**, allowing reliability to be assessed from both service-failure and operating-scale perspectives.

## Recommendations

- **Prioritize reliability improvement efforts in the Bronx**, where MDBF performance is the weakest, by reviewing recurring failure causes, vehicle condition, and maintenance patterns.

- **Use Staten Island as a benchmarking reference** to understand practices, asset conditions, or operating factors that may be contributing to stronger reliability outcomes.

- **Monitor MDBF and Road Calls together** rather than in isolation, since combining both indicators provides a more balanced view of fleet health and service disruptions.

- **Conduct borough-level root cause analysis** for periods showing declining MDBF or elevated road calls to identify whether issues are linked to fleet age, maintenance frequency, or operational demand.

- **Develop a targeted preventive maintenance strategy** for lower-performing boroughs to reduce unexpected failures and improve service dependability.

- **Continue using dashboard-based KPI tracking** to support management decisions, trend monitoring, and data-driven maintenance prioritization over time.
