# Customer Segmentation/Ranking 


Project performed with Unsupervised learning because of unavailability of labels in data.
Description: Customers ranking on the basis of Recency Frequency Monetary RFM method, The resulting segments can be ordered from most valuable (highest recency, frequency, and value) to least valuable (lowest recency, frequency, and value). 
Dsiclaimer: Dataset available in Simplilearn, not exposed to public

Steps:
  1. Perform exploratory data analysis(EDA) for fields, this includes univariate, bivariate analysis
  2. Preprocess data for necessary fields, handle missing values
  3. Perform cohort analysis, create cohort groups by Months/Month index
  4. Summarize the cohort results for example "Customers enrolled to website in 2010-12 and purchased till next 3 months (cohort index=3)"
  5. Calculate "RetentionRate" based on cohort index for example "38% of Customers enrolled/joined in website 2010-12 and are retained in 2011-01"
  6. Perform RFM Analysis.
        i.   Recency based on Recent purchased Date and First purchase Date
       ii.  Frequency based on number of purchases(Invoices) per each customer
       iii. Monetory based on Total money spent using UnitPrice*Quanity purchased
  7. Use "Qcut" technique after combining results from above step to determine "Best Customers", "Huge Spenders but not visiting recently", "Least Spenders" etc
  8. Exported data to a file and properly linked the sheets to perfectly design visualizations using Tableau showcase customer segments.
  9. Applied scaling techniques and done modelling using KMeans, KMode to form clusters.
  10. Written Conclusions 
    # Model grouped the clusters and found that Cluser 3 is having Least spending customers, Clusters 1 and 4 are having huge spenders more frequent customers and         actively participating in transactions/buying more.
    # Cluster 0 and Cluster 2 is moderately spending and moderate active users
        

Interested to see Tableau work? Follow me here :
https://public.tableau.com/views/Retail_Unsupervised_cap_Proj/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link
