# Strategic Retail Analytics & Visualization Portfolio

## Project Context
This repository showcases a comprehensive business intelligence project completed during the Tata Data Visualisation Virtual Experience on Forage. The primary objective was to transform messy, raw retail transaction data into polished executive dashboards that drive strategic decision-making. Leadership needed clear answers regarding seasonal sales patterns, the viability of non-UK international markets, and the concentration of revenue among top-tier clients. This project successfully bridged the gap between raw numbers and actionable corporate strategy.

## Data Preparation & Analytical Approach
To guarantee the integrity of the insights delivered to the executive team, a strict data processing pipeline was established:

* **Data Cleansing:** Eradicated anomalies from the raw dataset by stripping out all rows containing negative unit prices or negative order quantities, establishing a pristine foundation for analysis.
* **Temporal Analysis:** Modeled month-over-month revenue to uncover seasonal behaviors, establishing a baseline run-rate for the first eight months and calculating the late-year growth trajectory (intentionally excluding incomplete December figures).
* **Geographic Filtering:** Deliberately removed the dominant, saturated UK market from the dataset to properly isolate and evaluate the sales volume and revenue potential of emerging international regions.
* **Client Dependency Check:** Analyzed the purchasing weight of the top 10 accounts to determine customer bargaining power and assess the company's reliance on outlier buyers.

## Dashboard Features & Key Findings

> Use File `Task 3 Dashboard.pbix`

The final visualizations were designed to directly answer leadership's core business questions with high-impact data points:

* **Seasonal Revenue Curves:** Time-series tracking revealed a consistent baseline of roughly $685k in revenue from January through August. This is followed by a dramatic 40% surge in September, ultimately climaxing at $1.5 million in November.
* **International Growth Leaders:** With the UK filtered out, a targeted bar chart identified the Netherlands, Ireland, Germany, and France as the premier high-volume performance centers.
* **Client Revenue Distribution:** A comparative breakdown of the top 10 buyers illustrated a highly diversified revenue stream. The number one purchasing account generated only 17% more revenue than the second-highest, proving the business is not dangerously reliant on a single "whale" client.
* **Global Heatmap:** Spatial mapping exposed a heavy market presence in Europe and Australia, contrasted by minimal traction in the Americas and a complete lack of sales across Africa, Asia, and Russia.

## Executive Recommendations
Driven by the dashboard findings, the following strategies are proposed to maximize future profitability:

* **Optimize for Q4 Demand:** The data proves that September through November is the undisputed peak season. Operations, inventory management, and marketing budgets must be heavily synchronized to capture maximum market share during these months.
* **Scale Proven International Markets:** Because the UK market is already saturated, leadership should redirect localized expansion budgets toward the highest-performing secondary markets—specifically the Netherlands, Ireland, Germany, France, and Australia.
* **Target Global Whitespace:** The geographic mapping reveals a massive, untapped strategic opportunity. Formulating dedicated market-entry strategies for the Americas, Asia, Africa, and Russia could unlock entirely new global revenue streams.
* **Preserve Client Diversification:** The currently low bargaining power of individual buyers is a major structural strength. The company must maintain a wide-net customer acquisition strategy to ensure revenue never becomes critically concentrated in just a few top accounts.
