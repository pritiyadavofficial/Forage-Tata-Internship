# Predicting SME Customer Attrition for Energy Providers

## Project Background
This repository houses a complete predictive analytics solution developed as part of the Forage Boston Consulting Group (BCG) Data Science Virtual Experience. 

**The Business Challenge:** A leading energy utility company noticed a troubling increase in churn within their Small and Medium Enterprise (SME) portfolio. The executive team hypothesized that clients were abandoning the service primarily due to price sensitivity. My objective was to rigorously test this assumption using historical data, build a machine learning pipeline to forecast future cancellations, and deliver data-backed retention strategies to leadership.

## Methodology & Technical Approach
To translate raw business data into proactive retention strategies, I executed an end-to-end data science pipeline:

1. **Data Transformation & Feature Engineering:** Synthesized raw consumption logs, financial margins, and historical pricing records into structured, high-value features ready for machine learning ingestion.
2. **Algorithm Implementation:** Selected and trained a Random Forest Classifier. This model was chosen specifically for its capacity to capture non-linear relationships and complex interactions within the dataset to predict binary churn events.
3. **Performance Validation:** Audited the model's predictive power using Precision and Recall metrics. Furthermore, the model was tuned to output continuous probability scores rather than just binary labels to better prioritize at-risk accounts.
4. **Driver Extraction:** Leveraged the Random Forest's feature importance attributes to reverse-engineer the model and isolate the core variables dictating a client's decision to leave.

## Deliverables
To ensure technical findings translated seamlessly into business operations, the final output was formatted for executive use. The pipeline generates a final dataset (`out_of_sample_data_with_predictions.csv`) that maps unseen SME accounts to their specific churn probability scores. This allows the business to feed these predictions directly into their CRM without requiring their teams to interact with the underlying Python architecture.

## Key Findings & Strategic Roadmap
Based on the machine learning feature importance analysis, I proposed the following strategic pivots to the executive team:

* **Pivot Away from Blanket Discounts:** The executive hypothesis was largely incorrect. The model proved that price sensitivity is only a minor contributor to customer attrition. Engaging in broad price-cutting strategies will needlessly damage company profits without significantly improving retention.
* **Focus on Key Drivers (Margins & Usage):** The data shows that the true catalysts for churn are "Net margin and consumption over 12 months" and "Margin on power subscription." Retention teams should immediately redirect their efforts toward high-margin, heavy-consumption SMEs, especially those showing recent volatility in their energy usage.
* **Next Steps for Optimization:** While the model successfully ranks risk and identifies primary drivers, the business should invest in targeted A/B testing. Continued experimentation will help determine the exact price-sensitivity thresholds that eventually push a customer to a competitor.
