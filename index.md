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
<img src="images/RF Matrix.png.png?raw=true"/>
<img src="images/History.png?raw=true"/>
---

[Home Credit Default Risk Prediction (SQL, Machine Learning, Python)](https://github.com/shuchangliang/Projects/blob/master/Home%20Credit%20Default%20Risk.ipynb)
-	Calculated credit-to-income ratio, average income, numbers of bad debt and refused accounts, etc. for 300,000 records using SQL.
-	Prepared data by removing empty records and imputing missing values, and identified features correlated to defaulted accounts.
-	Transformed categorical variables into dummy variables using one-hot encoding.
-	Implemented and compared Logistic Regression and Random Forest models, the performance of the later method was improved by 17%.
<img src=“images/Random Forest AOC.png?raw=true”/>
---

[Post Marketing Campaign Analysis (A/B Testing, BI, SQL, Python)](https://github.com/shuchangliang/Projects/blob/master/Post%20Campaign%20Analysis%20rev.1.ipynb)
-	Acquired data from marketing campaigns of a Portugal bank, and implemented data pipeline with SQL connector in Python.
-	Visualized 10,000 campaign records in Plotly, an interactive plot enables segmentation of different campaigns and other characteristics (e.g. users per age group, valid offers per day).
-	Completed conversion and retention rate analysis, determining the most effective channel which obtained highest conversion rate (34%).
-	Applied A/B testing on the email channel, the statistical significance showed the customized emails improved marketing efficiency by 39%.











---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
