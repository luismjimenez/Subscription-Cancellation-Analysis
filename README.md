# Subscription-Cancelation-Analysis
Analysis of user subscription cancellations to find out why users are canceling and find opportunities to lower churn.

# Executive Summary:
Facing significant churn and resulting revenue loss, the company's leadership seeks deeper insights into the drivers of subscription cancellations to inform future retention efforts. 
This analysis uses user-reported cancellation reasons to identify trends and provide recommendations to support future retention efforts.

# Business Problem:
Company leadership has noticed significant churn this year, which has had a significant negative impact on revenue, so they're planning a company-wide retention effort. However, we don't currently have any insights or reporting on churn, so the analytics team has decided to analyze user-reported data from the product's cancellation workflow to identify trends in why users are cancelling.

# Methodology:
- Exploratory Data Analysis
- Product Funnel Analysis
- Data Visualization

# Skills:
- SQL
- CTEs, CASE, Union, View creation
- Data visualization
- Data Wrangling
- Data Cleaning
- Data Science Notebook
- Snowflake Data Warehouse

# Results & Business Recommendations:
**Results:**

**Recommendations:**
- Since most users have selected "Expensive" and "Not Useful" as reasons for canceling, we should roll out better onboarding and provide more help early in their subscription to ensure they understand the product and find it useful. If they find the product more useful and valuable, they may also become less cost-sensitive.
- For cost-conscious users, we could also implement a rescue tactic at the start of the cancellation workflow that offers a substantial discount to keep their subscription.
- Since the most common secondary cancellation reason is "Went to Competitor," we should research the market and ensure we stay up to date with industry trends.

# Next Steps:
- Explore the engagement of canceled subscriptions and see how they interacted with the product. 
  - What features did they or did they not use? How often did they use the product? What if we compare them to non-cancelled subscriptions? Does anything stand out that could inform future retention efforts?
- Work with the product manager to understand how we can improve the cancellation workflow by adding in rescue tactics and adding friction without increasing user frustration.
