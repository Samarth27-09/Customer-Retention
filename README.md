# Telco Churn Analysis & Retention Strategy

This repository contains a comprehensive churn analysis for a telecommunications company. The project focuses on identifying the key drivers of customer churn and providing actionable insights through an interactive Power BI dashboard to support proactive retention strategies.

-----

## Project Overview

Customer churn is a significant challenge in the competitive telecommunications industry. This project leverages the Kaggle Telco Churn Dataset to explore the characteristics of customers who leave the service versus those who stay.

The core of this project is a dynamic Power BI dashboard designed to empower business teams to understand churn patterns, identify high-risk customer segments, and make data-driven decisions to improve customer loyalty and reduce revenue loss.


## Key Features & Analysis

  * **Customer Segmentation:** Analyzed churned vs. non-churned customer segments based on key attributes like **tenure**, **contract type**, **monthly charges**, and **service usage patterns**.

  * **Interactive Dashboard:** Built a multi-section Power BI dashboard with dynamic filters and slicers to allow for an intuitive exploration of churn patterns and customer characteristics.

  * **Churn Driver Identification:** Identified and quantified the impact of high-risk churn indicators, such as customers on **month-to-month contracts** and those with **short tenure**.

  * **Actionable Insights:** Delivered clear, data-backed recommendations for business teams to effectively prioritize customer segments and design targeted interventions to reduce churn.

-----

## Data Source

The analysis is performed on the **Telco Customer Churn** dataset, which is publicly available on Kaggle.

  * **Dataset:** [IBM Watson Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

-----

## Tools Used

  * **Data Analysis & Visualization:** Microsoft Power BI

-----

## Key Insights & Recommendations

The analysis surfaced several critical factors that strongly correlate with customer churn:

1.  **Contract Type is the Strongest Predictor:** Customers with **month-to-month contracts** exhibit a significantly higher churn rate compared to those on one-year or two-year contracts.

      * **Recommendation:** Launch targeted campaigns to incentivize month-to-month customers to upgrade to longer-term contracts by offering loyalty discounts, bundled services, or exclusive perks.

2.  **New Customers are a High-Risk Segment:** Customers with a **short tenure** (e.g., under 12 months) are far more likely to churn as they have not yet established long-term loyalty.

      * **Recommendation:** Implement a structured customer onboarding program. Proactively engage with new customers during their first 3-6 months to ensure a positive experience and address any early-stage issues.

3.  **Higher Monthly Charges Drive Churn:** The churn rate increases steadily with higher **monthly charges**, especially among customers using Fiber Optic services who may be more sensitive to price vs. performance.

      * **Recommendation:** Review the pricing structure for premium services. Conduct a value-for-money analysis and consider introducing loyalty tiers or personalized bundles for high-spending customers to enhance perceived value.

-----

## How to View the Project

You can interact with the live dashboard via the link below or download the `.pbix` file to explore the data model, transformations, and DAX measures.
