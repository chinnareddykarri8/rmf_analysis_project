**E-commerce Customer Segmentation with RFM Analysis**

Project Goal:
My primary goal in this project is to perform RFM Analysis to segment customers effectively. Through this analysis, we aim to:
● Gain a deeper understanding of customer buying behaviour.
● Identify and categorize customers into meaningful segments.
● Extract actionable insights that can inform marketing and business strategies.

Data Description:
To embark on this RFM journey, I started with a dataset containing crucial information, including customer IDs, purchase dates, and transaction amounts. As a critical initial step, I converted the purchase dates into DateTime objects.

Calculating RFM Values:
● Recency: I calculated the recency value by measuring the number of days since each customer's last purchase.
● Frequency: Frequency was determined by counting the number of unique orders made by each customer.
● Monetary: The monetary value represents the total amount spent by each customer.

RFM Scoring:
To make RFM values more meaningful, I assigned scores to them:
● Recency Score: Higher scores indicate more recent purchases.
● Frequency Score: Higher scores correspond to higher purchase frequencies.
● Monetary Score: Higher scores reflect greater monetary contributions.

RFM Value Segmentation:
I segmented customers based on their RFM scores into three distinct categories: "Low-Value," "Mid-Value," and "High-Value." This segmentation provides an initial glimpse into customer segments, setting the stage for more in-depth analysis.
