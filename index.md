## Portfolio
---
### Project Samples
[Digital Marketing Analysis - Google Merchandise Store Dashboard (Google Analytics, BigQuery, Tableau)](https://public.tableau.com/app/profile/angelo.chen/viz/GoogleAnalyticsDashboard_16443587309150/Dashboard)
<br><br>
Identified traffic patterns and visitor digital footprint to measure  effectiveness of Google e-commerce business store:
- ETL: Queried Google Analytics data in BigQuery to extract customer behavior from unnested hit-level raw data (1.4 million records)
- BI: Re-created Google Analytics dimensions and metrics (total sessions, average duration on pages, bounce rate, etc.)
- Visualization: Built dynamic dashboard which displays monthly/yearly traffic (total sessions, average pageviews, average duration) per source and per location, acquisition amounts per channel, and bounce rate per page
- Marketing optimization: Identified channel optimization opportunity and recommended optimal marketing budget allocation to drive further growth
<img src="images/Screen Shot 2022-05-09 at 12.16.39 PM.png?raw=true"/>

---

[Retailer Marketing RFM & CLV Analysis (Machine Learning, Python)](https://github.com/angelochenyx/BI-Projects/blob/main/Retail%20Marketing%20RFM%20%26%20CLV%20Analysis.ipynb)
<br><br>
Developed a RFM customer segmentation model for a UK based retailer leveraging 2 years of data and built a forward looking, predictive, customer level CLV model to optimize marketing campaign:
- ETL: Loaded transaction data in Python, check and confirm accuracy, completeness, and consistency of data
- BI: Monitored customer cohort and retention chart
- RFM Model: Segmented customers into 3 clusters (high, medium and low value) based on their recency, frequency and monetary values
- CLV Model: Analyzed Frequency/Recency to predict future purchase and alive probability using the BG/NBD model, and estimate customer lifetime value using the Gamma-Gamma model and Discounted Cash Flow (DCF) method
<img src="images/cohort & retention.png?raw=true"/>
<img src="images/RF Matrix.png?raw=true"/>
<img src="images/History.png?raw=true"/>

---

[Home Credit Default Risk Prediction (SQL, Machine Learning, Python)](https://github.com/angelochenyx/BI-Projects/blob/main/Home%20Credit%20Default%20Risk.ipynb)
<br><br>
Build machine learning models to predict loan default probability and manage credit risk for a global non-bank consumer lender leveraging data from 3 sources, 4 tables, millions of records:
- ETL: Created key measures correlated to credit risk using MySQL, load data by connecting database to Python, prepare data by removing empty records and imputing missing values, identify features correlated to default, and leverage one-hot encoding for applied categorical variables
- Logistic Regression Model: Performed train/test split and applied the model on training data to predict default probability, implemented ROC curve to evaluate the performance, AUG (Area Under the ROC Curve) is 0.616 (>0.5) that means the model performs better than random prediction
- Random Forest Model: Taking the same steps as above, AUG is 0.701 that shows Random Forest Model is 14% more efficient than Logistic Regression Model
<img src="images/LRM.png?raw=true"/>
<img src="images/Random Forest.png?raw=true"/>

---

[Post Marketing Campaign Analysis (A/B Testing, Python)](https://github.com/angelochenyx/BI-Projects/blob/main/Post%20Campaign%20Analysis.ipynb)
<br><br>
Calculated marketing metrics to analyze campaign performance of a Portugal bank, and implemented A/B testing to evaluate marketing impacts:
- ETL: Loaded marketing campaign data (10,000 records) for 4 weeks (1 month) in Python
- BI: Identified the most effective channel (email) with the highest conversion rate (33.8%), and the overall retention rate (66.8%) by visualizing the key metrics
- A/B Testing: Conducted statistical test to confirm a 38.9% lift in conversion rate from email channel driven by this campaign with high confidence (reaching stats sig)
<img src="images/conversion rate.png?raw=true"/>










---

