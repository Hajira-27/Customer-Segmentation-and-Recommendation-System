Customer-Segmentation-and-Recommendation-System
---------
Objective

To analyze customer purchasing behavior and categorize them into distinct groups to enable personalized marketing strategies and product recommendations.

-----
Dataset
Customer Transaction Dataset containing:

InvoiceNo: Unique transaction ID

StockCode: Item code

Description: Product name

Quantity & UnitPrice: Purchase details

CustomerID: Unique user ID

Country: Geographic location

--------
Models Used

K-Means Clustering (for segmentation)

RFM Analysis (Recency, Frequency, Monetary)

--------
Techniques
Data Cleaning: Handled missing values and removed cancelled transactions.

Feature Engineering: Created total spend metrics and encoded categorical variables.

Outlier Handling: Scaled and filtered Quantity/UnitPrice to improve model accuracy.

--------
Key Findings
Segment Distribution: Identified 4 key groups (VIP, High-Value, Regular, Budget).

Behavior: Small groups of VIPs drive significant revenue compared to mass "Regular" users.

--------
Recommendations: Top products vary significantly by cluster, allowing for targeted CSV exports.

--------
Tools
Python: Pandas, Scikit-learn, Matplotlib, Seaborn

-------
Power BI: For visual dashboarding and cluster profiling

-------
Results
The model successfully identified segments with the following distribution:

Regular Customers: 3177

Budget Customers: 1143

High-Value Customers: 16

Premium VIP Customers: 2

--------------
Project Structure

Tcs_intern.ipynb: Main Jupyter Notebook containing the analysis pipeline.

dashboard.pbix: Power BI dashboard for visual exploration of segments.

top_products_cluster_*.csv: Generated output files containing top products for each segment.
