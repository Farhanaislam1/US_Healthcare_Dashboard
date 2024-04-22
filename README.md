# US Healthcare Dashboard
## I have created this dashboard for my capstone project to understand the Healthcare Referrals & Economic Activity in Local Communities in US. 
This dashboard provides a comprehensive analysis of healthcare referrals and economic activity within local communities in the US. It focuses on understanding referral volumes between healthcare providers operating in the same municipality, using three statistical models (linear, quadratic, and log-linear regression). The dataset used originates from the Centers for Medicare and Medicaid Services, specifically the Physician Shared Patient Patterns dataset, covering Medicare and Medicaid activity from 2009 to 2015. For this dashboard, the focus is on data from 2011. To ensure accuracy and relevance, the data was processed into a SQL relational database, aggregating it to a geographic level and filtering for individual providers within the same city.
The dashboard evaluates the performance of linear, quadratic, and log-linear regression models, aiming to determine which one best explains the scaling of referral networks and referral volume concerning the number of providers in a city. Based on the analysis, linear and log-linear models exhibit the best fit, with consideration of R2 values. However, it's acknowledged that linear assumptions may not always hold true in real-world scenarios, and outliers can impact model parameters. Additionally, the study's limitations include the focus on 2011 data, which may limit generalizability, and the recommendation to explore additional variables and dataset breadth for enhanced model robustness.
Overall, this dashboard provides valuable insights into healthcare referrals and economic activity, offering recommendations for future model enhancements and considerations for real-world application.
