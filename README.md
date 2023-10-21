# Amazon 2022 RFM Analysis

## Table of Contents
+ [Project Overview](#Project-overview)
+ [Technologies Used](#Technologies-Used)
+ [Project Problem](#Project-Problem)
+ [Project Walkthrough](#Project-Walkthrough)
+ [Project Insights](#Project-Insights)
+ [Screenshots](#Screenshots)
+ [Source](#Source)

## Project Overview
 An in-depth RFM (Recency, Frequency, and Monetary) analysis of Amazon sales using Excel. This project provides valuable insights into customer segmentation, allowing for more targeted marketing efforts.
 
## Technologies Used
+ Excel

## Project Problem
In the context of analyzing Amazon sales data, the primary problem addressed was to identify and understand customer behavior and segment customers effectively for more targeted marketing strategies.

## Project Walkthrough
1. Checked for duplicates and removed them.
2. Created a unique customer ID by concatenating the shipping code, shipping city, and shipping postal code.
3. Filtering Data: focus on the data from the year 2022, as it was the period of interest.
4. Calculating RFM Scores for each customer using the range perecentil function, helping in segmentation.
5. Created a dynamic dashboard to visualize the results of the RFM analysis.

## Project Insights
- Customer segmentation
   - The largest group, at 23.17%, falls into the "At Risk" category, indicating that these customers need attention and retention efforts.
   - The "Champions" group, despite being smaller in size, holds the highest average purchase value at 820. This group's high value makes them a key target for loyalty programs and upselling.
- Average Customer Metrics
   - On average, customers made their last purchase about 96 days ago.
   - Customers, on average, make 9 purchases.
   - The average customer contributes approximately $649.67 to the revenue.
- RFM
   - Champions have the longest time since their last purchase (228 days), indicating they are less frequent but high-value customers.
   - At-risk customers have a shorter time since their last purchase and have the highest purchase frequency (24 purchases), indicating a need for immediate attention.
   - Generated a top 10 customers list based on their RFM scores, this list identifies the most valuable and engaged customers who contribute significantly to success.

## Screenshots
<div style="display: flex; flex-direction: row; gap:10">
  <img  style="margin-bottom: 15px;" src="https://github.com/NilArj/Amazon_sales/blob/db503681a8c494a0710317f20e69ff8c7a208580/Captura%20de%20pantalla%202023-09-12%20233902.png" alt="visualization insights" width="600" height="280">
<img  style="margin-bottom: 10px;" src="https://github.com/NilArj/Amazon_sales/blob/db503681a8c494a0710317f20e69ff8c7a208580/Captura%20de%20pantalla%202023-09-12%20234100.png" alt="excel table" width="600" height="280">
</div>

## Source
[Dataset](https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data)

