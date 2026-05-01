# A/B Test Analysis for Online Shooter Game

## 📌 Project Overview
This project evaluates the impact of a premium armor discount on player monetization metrics. Using the **PACE framework** (Plan, Analyze, Construct, Execute), I analyzed a dataset of **1.08 million unique users** (8.6 million transaction records) to determine if the promotion should be implemented globally.

## 🛠️ Tech Stack
*   **Python:** Pandas (Data Wrangling), NumPy.
*   **Statistics:** SciPy (T-tests, Confidence Intervals), Statsmodels.
*   **Machine Learning:** Scikit-learn (K-Means Clustering, StandardScaler, Silhouette Method).
*   **Visualization:** Matplotlib, Seaborn.

## 📈 Key Findings
*   **Statistically Significant Uplift:** The promotion resulted in a **4.1% increase in ARPU** ($0.76 vs $0.73). 
*   **Consistency:** Daily trend analysis confirmed that the Test group consistently outperformed the Control group throughout the 8-day period.
*   **Anomaly Detection:** Identified **8,600+ "hidden cheaters"** by analyzing spending distributions, preventing a major skew in the final results.
*   **Segment Insights:** Casual spenders showed higher price elasticity (+0.61% uplift) compared to high-value players (+0.38%).

## 🏗️ Methodology (PACE Framework)
1.  **Plan:** Data cleaning, deduplication of 7.5M redundant rows, and data type standardization.
2.  **Analyze:** Exploratory Data Analysis (EDA), outlier detection using the 99.9th percentile threshold, and time-series visualization.
3.  **Construct:** Hypothesis testing (Welch’s T-test), calculation of 95% Confidence Intervals, and K-Means segmentation.
4.  **Execute:** Business recommendations based on statistical and behavioral insights.

## 🚀 Business Recommendation
Based on the results, I recommend a **full rollout** of the promotion. Additionally, I suggest targeting Cluster 0 (Casual Spenders) for future discount events to maximize conversion.
