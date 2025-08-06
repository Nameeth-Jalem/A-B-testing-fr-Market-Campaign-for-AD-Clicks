Marketing Campaign Analysis: Facebook vs. Google AdWords
🟢 Business Problem
As a marketing agency, our objective was to maximize ROI for a client. We launched two parallel campaigns on Facebook and Google AdWords and needed to evaluate:
Which platform performs better in terms of clicks, conversions, and cost-efficiency
Where should the client reallocate their budget for optimal performance?

🟢 Research Question
Which ad platform delivers:
More conversions
Better Click-Through Rate (CTR)
Higher cost-efficiency (CPC and cost per conversion)?

🟢 Solution Overview
We conducted a full analysis of the daily ad performance for both platforms across 2019 using:
Exploratory Data Analysis (EDA)
Hypothesis testing (A/B testing)
Linear Regression Modeling
Statistical interpretation

🟢 Tools & Technologies
Python: pandas, seaborn, matplotlib, numpy, scipy, sklearn, statsmodels
Jupyter Notebook
A/B Testing Methodology
Linear Regression Modeling
Statistical Analysis

🟢 Dataset Overview
Time Period: Entire year of 2019
Features: Campaign type, daily spend, impressions, clicks, conversions, CPC, cost per conversion
Target Variables: CTR, ROI, conversions
Data Source: Internal ad tracking data from the client

🟢 Project Workflow
1. Data Cleaning
Converted spend and conversion columns to numeric
Handled missing/null values
Corrected data types

2. Exploratory Data Analysis (EDA)
Trend analysis across time
Platform-wise metric comparisons

3. Statistical Testing
Performed A/B testing on conversion rates
Assessed significance of mean differences

4. Correlation & Regression
Measured relationships between impressions, clicks, and conversions
Built linear regression to estimate conversion impact from ad spend

🟢 Key Insights & Recommendations
Facebook delivered higher CTR and lower CPC
AdWords delivered more conversions but at higher cost
Recommend 65% budget allocation to Facebook for better ROI
Regression showed diminishing returns beyond a certain daily spend
