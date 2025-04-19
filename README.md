
# RFM Analysis and K-Means Clustering

This repository demonstrates how to perform **Recency, Frequency, and Monetary (RFM)** analysis on customer transactional data, followed by **K-Means clustering** to segment customers into different groups. The project provides insights into customer behavior, which can be useful for targeted marketing or personalized recommendations.

## Overview

The project uses customer transactional data (CSV format) to perform RFM analysis and clustering. The analysis is followed by:
1. **RFM Calculation**: We calculate Recency, Frequency, and Monetary metrics for each customer.
   - **Recency**: Number of days since the most recent purchase.
   - **Frequency**: Number of unique orders made by the customer.
   - **Monetary**: Total amount spent by the customer.
   
2. **K-Means Clustering**: After normalizing the RFM values, K-Means clustering is applied to segment customers into distinct groups based on their purchasing behavior.

3. **Visualizations**: The project also includes several visualizations to explore the customer clusters and RFM distributions.

