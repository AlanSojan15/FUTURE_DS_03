# FUTURE_DS_03
Marketing Funnel & Conversion Performance Analysis
Data Science & Analytics – Task 3 (Future Interns)

 1. Project Overview
This project focuses on analyzing a bank's marketing campaign to understand how potential customers move through the acquisition funnel. By identifying drop-off points and high-converting segments, this analysis provides actionable strategies to increase subscription rates and optimize marketing spend.

 2. Data Strategy & Funnel Stages
I utilized the Bank Marketing (Additional) dataset from the UCI Machine Learning Repository, containing 41,188 records. To analyze the conversion performance, I defined a 3-stage funnel:

Total Reach: All customers contacted during the campaign.

Engaged Leads: Customers who showed interest (defined by a call duration > 60 seconds).

Conversions: Customers who successfully subscribed to the term deposit (y = "yes").

3. Key Analytical Insights
The Channel Gap: Analysis revealed that Cellular outreach is significantly more effective than traditional Telephone (landline) calls. Cellular campaigns achieved a 14.7% conversion rate compared to just 5.2% for telephones.

High-Performing Segments: The most successful demographic segments were Students and Retired individuals. These groups show the highest propensity to convert, suggesting a strong product-market fit.

Temporal Trends: While the highest volume of contacts occurred in May, the highest conversion efficiency (quality of leads) was observed in the latter half of the year.

4. Business Recommendations
Mobile-First Outreach: Phase out landline-based marketing and reallocate the budget toward cellular-focused campaigns to triple the conversion efficiency.

Targeted Personalization: Develop specific marketing creative for the Student and Retired demographics, as these segments provide the highest ROI.

Lead Scoring: Implement a "Lead Scoring" system that prioritizes follow-ups based on the first 60 seconds of call engagement, as duration is a primary predictor of conversion.

5. Tools & Technologies
Power BI: Data Modeling, DAX (Custom Measures), and Funnel Visualization.

Power Query: Data transformation and cleaning (Semicolon delimiter handling).

DAX Measures: * Total Contacts = COUNTROWS('Table')

Conversion Rate % = DIVIDE([Conversions], [Total Contacts], 0)

