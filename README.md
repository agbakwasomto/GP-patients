# GP-patients
These <a href="https://github.com/agbakwasomto/GP-patients/blob/main/Bedford%20council.xlsx">data </a> are from GP records across three combined Local Authorities and concern the distribution of diabetes.
GP Patient's Data: BLMK Obesity Report
# Description
This dashboard provides an analytical overview of patient data across the BLMK (Bedfordshire, Luton, and Milton Keynes) region, focusing specifically on obesity prevalence and its potential socioeconomic indicators. The report analyzes a total registered patient population of 1,103,136, identifying 85,216 obese patients. The data visualizations incorporate demographic breakdowns for the year 2023 and explore the relationship between regional deprivation scores and health outcomes.
# Data Cleaning
The raw healthcare dataset was pre-processed and cleaned within Microsoft Excel to ensure the integrity of the analysis. Power Query was utilized for the ETL (Extract, Transform, Load) process. This involved standardizing patient records, cleaning up demographic categorizations, merging local authority geographic data with deprivation scores, and formatting the dataset into a clean, tabular structure ready for visualization.
# Data Analysis and Visualisation
The core analysis relies on Excel's Pivot Table functionality, which was used to aggregate patient counts, calculate prevalence percentages, and summarize deprivation scores across the different local authorities.
The dashboard is structured to provide both high-level summaries and detailed demographic insights, featuring the following visualizations:
High-Level KPIs: Summary cards displaying the Total Patient count (1,103,136) and the total Obese Patient count (85,216) across the BLMK region.
Prevalence Distribution (By Local Authority): A bar chart showing how the total obese population is distributed across the region (e.g., Milton Keynes accounts for 27.91% of the region's obese patients).
Obesity Rate (In each Local Authority): A bar chart detailing the specific obesity prevalence rate within each area's distinct population (e.g., Bedford Borough has an 8.44% prevalence rate).
Deprivation Tracking: A bar chart comparing the Average Deprivation Score across the four local authorities.
Correlation Analysis: A line/scatter plot with a trendline mapping the relationship between varying deprivation scores and overall obesity prevalence.
Demographic Breakdown: A grouped bar chart illustrating the 2023 Population Distribution by age groups (<18, 18-65, >65) for each local authority.
Interactive Filters: Regional slicers at the top allow users to isolate data for Bedford Borough, Central Bedfordshire, Luton, or Milton Keynes.
# Inferences
Based on the dashboard's visualizations, several key insights can be drawn regarding the region's health profile:
Regional Averages: The overall obesity prevalence across the entire BLMK region is approximately 7.7% (85,216 out of 1.1M patients).
Prevalence vs. Distribution: While Milton Keynes has the highest share of the region's total obese patients (27.91% due to its larger overall population), Bedford Borough actually has the highest obesity rate within its own population (8.44%).
Socioeconomic Factors: Luton records the highest Average Deprivation Score (25) in the region, more than double that of Central Bedfordshire (12).
Deprivation Correlation: The line chart tracking the relationship between deprivation and obesity shows a slight positive trendline, suggesting a potential correlation where higher deprivation scores may link to marginally higher obesity prevalence, though variations exist.
Demographics: Across all four local authorities, the working-age population (18-65) represents the vast majority of registered patients, followed by the under-18 demographic.
# Dashboard
<img width="1027" height="666" alt="GP data" src="https://github.com/user-attachments/assets/04949d78-2fa3-4a1d-829c-f1ebdee41560" />
