# Transit Reliability Insights: MDBF & Road Call Analysis

## Project Overview

This case study analyzes transit reliability across New York City boroughs using **Mean Distance Between Failures (MDBF)** and **Road Call** metrics. The objective is to identify borough-level performance gaps, compare reliability trends, and support maintenance-focused decision-making through an interactive Tableau dashboard.

The project focuses on understanding where vehicle reliability is strongest, where failures are more frequent, and how reliability metrics can help transit agencies prioritize maintenance and service improvement efforts.

---

## Business Problem

Transit agencies need to understand where vehicle reliability is weakest and where operational failures occur more frequently. Lower MDBF and higher Road Call counts may indicate areas that require closer maintenance review, preventive maintenance planning, and service improvement efforts.

Without a clear view of reliability performance across boroughs, decision-makers may struggle to identify underperforming areas, compare trends, and focus maintenance resources effectively.

---

## Understanding the Key Metrics

### What is MDBF?

**MDBF stands for Mean Distance Between Failures.**

It is a transit reliability metric that shows how many miles a bus fleet travels, on average, before experiencing a mechanical failure that results in a Road Call.

A **higher MDBF** generally indicates:

- Better vehicle reliability
- Fewer mechanical failures relative to miles operated
- Stronger maintenance performance
- More dependable service delivery

### How is MDBF calculated?

**MDBF = Total Miles Operated ÷ Total Road Calls**

For example, if buses travel **1,000,000 miles** and record **200 Road Calls**:

**MDBF = 1,000,000 ÷ 200 = 5,000 miles between failures**

This means the fleet experiences one failure-related Road Call approximately every **5,000 miles** of operation.

---

### What is a Road Call?

A **Road Call** refers to a service-related incident caused by a mechanical problem that occurs while a bus is operating in service and requires attention or intervention.

Road Calls are important because they can indicate:

- Vehicle breakdowns or mechanical issues
- Potential service disruptions
- Areas where preventive maintenance may need improvement

In reliability analysis, Road Calls are used as the failure count when calculating MDBF.

---

## Why These Metrics Matter

MDBF and Road Calls are useful together because they help assess fleet reliability from two perspectives:

- **Road Calls** show the number of failure-related incidents.
- **MDBF** adjusts those failures for service mileage, making it easier to compare reliability across boroughs or time periods.

This allows transit agencies to identify underperforming areas, track reliability trends, and support maintenance planning decisions.

---

## Reliability Benchmark

For this analysis, **MDBF above 6,000 miles** is used as a strong reliability benchmark, while values below this level suggest a need for closer review of fleet performance and maintenance conditions.

A higher MDBF means vehicles are traveling farther between failure-related Road Calls, which generally reflects better mechanical reliability.

---

## Objectives

- Compare MDBF performance across boroughs
- Analyze Road Call trends
- Identify best- and worst-performing boroughs
- Track reliability changes over time
- Present insights through an interactive Tableau dashboard
- Support maintenance-focused decision-making

---

## My Role

For this project, I worked as a **Business and Data Analyst**.

My responsibilities included:

- Defining the business problem and analysis objectives
- Preparing and organizing the dataset for analysis
- Calculating and interpreting MDBF and Road Call metrics
- Building an interactive Tableau dashboard
- Comparing borough-level reliability performance
- Identifying key insights and reliability gaps
- Developing business recommendations for maintenance prioritization

---

## Tools Used

- **Tableau** — dashboard development, data visualization, and interactive analysis
- **Excel** — data preparation, cleaning, validation, and metric calculation

---

## Dataset & Assumptions

This project uses a sample transit reliability dataset created for portfolio and case study purposes.

### Dataset Fields Used

- Borough
- Year
- Total Miles Operated
- Road Calls
- MDBF
- Reliability performance indicators

### Assumptions

- Road Calls are treated as failure-related service incidents.
- MDBF is calculated as Total Miles Operated divided by Total Road Calls.
- Borough-level comparisons are used to identify reliability patterns.
- MDBF above 6,000 miles is used as a strong reliability benchmark for this analysis.
- The project is designed to demonstrate business analytics, dashboarding, KPI reporting, and operational decision support.

---

## Dashboard Preview

<img width="1724" height="718" alt="Transit Reliability Dashboard" src="https://github.com/user-attachments/assets/af0962e5-fc80-4f9c-935b-d215e0e096a2" />

[View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/preetii.birajdar/viz/TransitReliabilityInsightsMDBFRoadCallAnalysis/Dashboard1)

---

## Dashboard Features

The Tableau dashboard provides a consolidated view of transit reliability performance using MDBF, Road Calls, and borough-level comparisons.

Key dashboard components include:

- Overall MDBF KPI
- Total Road Calls KPI
- Borough-level MDBF comparison
- Road Call analysis by borough
- Historical MDBF trend view
- Heatmap to identify reliability patterns
- Best- and worst-performing borough highlights
- Reliability benchmark comparison

---

## Key Insights

- **Overall transit reliability in 2026 reached an MDBF of 5,172**, with **8,256 Road Calls**, providing a high-level view of fleet performance for the year.

- **Staten Island was the best-performing borough**, recording the highest MDBF at **9,585**, which indicates stronger vehicle reliability compared with other boroughs.

- **The Bronx was the worst-performing borough**, with an MDBF of **2,694**, highlighting a potential reliability gap that may require deeper maintenance and operational review.

- Borough-level comparison shows that **reliability performance varies significantly across locations**, suggesting that maintenance effectiveness, fleet age, route conditions, or operational intensity may differ by borough.

- The historical MDBF trend table and heatmap reveal **year-over-year fluctuations in reliability**, making it easier to identify boroughs with recurring underperformance or recent improvement.

- The dashboard combines **MDBF, Road Calls, and mileage context**, allowing reliability to be assessed from both service-failure and operating-scale perspectives.

---

## Recommendations

- **Prioritize reliability improvement efforts in the Bronx**, where MDBF performance is the weakest, by reviewing recurring failure causes, vehicle condition, and maintenance patterns.

- **Use Staten Island as a benchmarking reference** to understand practices, asset conditions, or operating factors that may be contributing to stronger reliability outcomes.

- **Monitor MDBF and Road Calls together** rather than in isolation, since combining both indicators provides a more balanced view of fleet health and service disruptions.

- **Conduct borough-level root cause analysis** for periods showing declining MDBF or elevated Road Calls to identify whether issues are linked to fleet age, maintenance frequency, or operational demand.

- **Develop a targeted preventive maintenance strategy** for lower-performing boroughs to reduce unexpected failures and improve service dependability.

- **Continue using dashboard-based KPI tracking** to support management decisions, trend monitoring, and data-driven maintenance prioritization over time.

---

## Business Impact

This project demonstrates how transit reliability data can be transformed into actionable business insights.

The analysis supports:

- Data-driven maintenance prioritization
- Identification of boroughs with weaker reliability performance
- Better understanding of failure-related service disruptions
- Improved monitoring of MDBF, Road Calls, and mileage-based reliability trends
- Benchmarking across boroughs
- Strategic decision-making for fleet reliability planning
- Clear communication of operational performance through dashboard reporting

By combining KPI analysis with visual storytelling, the dashboard helps transit leaders identify where reliability issues are most concentrated and where improvement efforts may have the greatest impact.

---

## Skills Demonstrated

- KPI reporting
- Tableau dashboard development
- Excel-based data preparation
- Data visualization
- Transit reliability analysis
- Operations analytics
- Performance benchmarking
- Business problem framing
- Data storytelling
- Insight generation
- Recommendation development
- Maintenance decision support
- Stakeholder-focused reporting

---

## Project Files

| File / Link | Description |
|---|---|
| `README.md` | Project documentation and business case study |
| Dashboard Preview | Screenshot of the Tableau dashboard |
| Tableau Public Link | Interactive dashboard for exploring MDBF and Road Call trends |

---

## Conclusion

This case study shows how transit reliability metrics such as MDBF and Road Calls can be used to identify performance gaps, compare borough-level reliability, and support maintenance-focused decision-making.

The project highlights the value of dashboard-based KPI tracking for operational performance analysis. By presenting reliability data in a clear and business-focused way, the analysis helps decision-makers understand where service reliability is strongest, where improvement is needed, and how data can support more effective maintenance planning.

---

## Author

**Preeti Birajdar**  
Business & Data Analyst  
Skills: Excel, Tableau, Power BI, SQL, Business Analytics, KPI Reporting, Dashboard Development, Operations Analytics

[GitHub Profile](https://github.com/PreetiBirajdar)
