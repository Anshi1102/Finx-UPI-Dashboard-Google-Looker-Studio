# Finx-UPI-Dashboard-Google-Looker-Studio

# Introduction
In the evolving fintech landscape of India, Unified Payments Interface (UPI) has emerged as a game changer — offering real-time, seamless payment experiences. But behind every successful transaction lies a complex data trail that can unlock deep business insights.
In this project, I created an interactive analytics dashboard using Google Looker Studio to analyze UPI transactional data and highlight success rates, failures, revenue impact, customer trends, and merchant behavior. This dashboard provides valuable, visual insights for stakeholders across payments, product, and customer experience teams.

# Project Objectives
The main goals of this project were:
1) Track the success vs failure ratio of UPI transactions
2) Quantify the revenue lost due to failed transactions
3) Analyze user preferences based on device, age, and city
4) Identify top-performing and underperforming banks
5) Highlight failure-prone payment methods and merchants
6) Empower decision-makers with real-time, visual insights

# Tools Used
1) Google Looker Studio (formerly Data Studio)
2) Custom calculated fields for metrics and age bucketing
3) Filters for device, city, and payment method
4) CSV data exported from a transactional database

# Key Metrics Visualized
# 1) Transaction Overview
- Total Transactions: 1,985
- Successful Transactions: 1,666 (83.9%)
- Failures: 319 (16.1%)
- Revenue Impact due to Failures: ₹278.24
  
# 2) Monthly Trend: Success vs Failure
Visualized over 7 months (Jan–Jul 2025), this time-series helps stakeholders spot dips and peaks in transaction health, enabling proactive issue resolution.

# 3) Failures by Device, Payment Method, and Bank
This section highlights technical and process-level issues:
- Laptop users faced the most failures (127), indicating UX or connectivity issues
- UPI ID method had the most failures (121), suggesting server or API lags
- ICICI, HDFC, and SBI topped bank-wise failure counts

# 4) City-wise Performance
Cities like Mumbai (306), Kolkata (297), Bangalore (292), and Delhi (277) accounted for the highest transaction volumes. However, even top cities had a non-negligible failure rate.

# 5) User Demographics
- Age group 25–35 had the highest success rates
- Devices: Laptops (37.1%), Mobiles (32.4%), Tablets (30.5%)
- Cities: Mumbai, Hyderabad, Bangalore, and Delhi formed 68.5% of the user base
- 31.5% of transactions came from “Other” regions — highlighting rural UPI adoption

# 6) Top Merchants & Categories
Merchants like Flipkart, Amazon, Spotify, Swiggy, and Netflix led in transaction volume.
# Category share:
- E-commerce: 29.3%
- Food Delivery: 28.5%
- Travel & Others: 27.4% and 14.9% respectively
This section helps identify both opportunities and risk areas in merchant partnerships.

# Geographic and Demographic Insights
The dashboard provides a geographical heatmap and age-device segmentation, enabling businesses to:
- Personalize campaigns
- Improve user interfaces for high-failure devices
- Prioritize city-specific infrastructure fixes
- Target specific age groups with tailored offerings
  
# Key Learnings
Google Looker Studio is a powerful, free platform that can bring static data to life with interactive filters and smart visualizations.
Failure patterns are often device or bank-specific, not just user-related.
Even a 16% failure rate can lead to significant revenue loss — ₹278.24 in this sample alone.

# Link: https://lookerstudio.google.com/s/h1sdlErllQw

# Next Steps
For future iterations, I plan to:
- Integrate real-time data feeds
- Add predictive modeling for failure forecasting
- Include hourly breakdowns for peak traffic analysis
- Embed alerts for high failure spikes using Looker integrations

# Conclusion
This project shows how visual analytics can uncover hidden patterns in UPI transactions and offer powerful, data-driven insights for improving financial products. With the right tools — like Google Looker Studio — organizations can go beyond raw numbers and make smarter decisions that improve customer experience and operational efficiency.
