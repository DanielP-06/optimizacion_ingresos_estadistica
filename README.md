# optimizacion_ingresos_estadistica
Income Optimization Statistics Project

Revenue Optimization: Strategic Prioritization and Statistical Validation of an E-commerce A/B Test
Project Description
This project aims to improve revenue on an e-commerce platform through two complementary approaches: strategic prioritization of growth hypotheses and statistical analysis of an already executed A/B Test.

The first part uses the RICE and ICE frameworks to evaluate and rank nine growth hypotheses based on their Reach, Impact, Confidence, and Effort, in order to identify the initiatives with the highest potential return.

The second part focuses on analyzing an A/B Test, exploring key metrics such as cumulative revenue, cumulative average order size, and conversion rate. Anomaly detection and treatment (outliers) are performed to ensure the reliability of the statistical analysis, which culminates in significance tests to determine if the observed differences between the experimental and control groups are statistically significant.

The final outcome is a data-driven recommendation for implementing improvements and making strategic decisions.

Data
Three datasets are used:

hypotheses_us.csv: Contains the nine growth hypotheses with their metrics (Reach, Impact, Confidence, Effort).
orders_us.csv: Contains information about orders placed during the A/B Test (transaction ID, user ID, date, revenue, A/B group).
visits_us.csv: Contains the daily number of visits for each A/B Test group.
Methodology
Hypothesis Prioritization:

Calculation and comparison of ICE and RICE scores for each hypothesis.
Analysis of the impact of the 'Reach' factor on prioritization.
Determination of the hypotheses with the highest priority according to the RICE framework.
A/B Test Analysis:

Data preprocessing, including checking for and handling users in both groups.
Exploration and visualization of cumulative metrics (revenue, average order size, conversion rate).
Identification of outliers in the number of orders per user and in the order value.
Statistical significance analysis of the difference in conversion rate (with raw and filtered data).
Statistical significance analysis of the difference in average order size (with raw and filtered data).
Decision making based on the test results.
Repository Structure
README.md: This file.
notebook.ipynb: The Jupyter/Colab notebook with all the code and analysis.
hypotheses_us.csv: Hypotheses data file.
orders_us.csv: A/B Test orders data file.
visits_us.csv: A/B Test visits data file.
Key Conclusions and Recommendations
Prioritization using the RICE framework, which considers reach, identified hypotheses with greater overall impact potential compared to ICE.
The A/B Test analysis revealed that Group B had a significantly higher conversion rate than Group A, even after removing outliers.
Although Group B showed a higher average order size in the raw data, this effect was not statistically significant when high-revenue outliers were removed.
Decision: Based on the statistically significant improvement in conversion rate, it is recommended to stop the A/B Test and scale the solution implemented in Group B.
This project demonstrates the importance of strategic prioritization and rigorous statistical analysis, including anomaly handling, to make data-driven decisions that drive growth and revenue.
