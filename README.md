## Subscription-Cancelation-Analysis
Analysis of user subscription cancellations to find out why users are canceling and find opportunities to lower churn.

## Executive Summary:
Facing significant churn and resulting revenue loss, the company's leadership seeks deeper insights into the drivers of subscription cancellations to inform future retention efforts. 
This analysis uses user-reported cancellation reasons to identify trends and provide recommendations to support future retention efforts.

## Business Problem:
Company leadership has noticed significant churn this year, which has had a significant negative impact on revenue, so they're planning a company-wide retention effort. However, we don't currently have any insights or reporting on churn, so the analytics team has decided to analyze user-reported data from the product's cancellation workflow to identify trends in why users are cancelling.

## Methodology:
- Exploratory Data Analysis
- Product Funnel Analysis
- Data Visualization

## Skills:
- SQL
- CTEs, CASE, Union, View creation
- Data visualization
- Data Wrangling
- Data Cleaning
- Data Science Notebook
- Snowflake Data Warehouse

## Results & Business Recommendations:
**Results:**
- 64% (just under 2 in 3 or almost two-thirds) of all users did not select a third reason for cancellation.
- Of users who selected a third reason, 23% selected 'Bad customer service'.
- ~45% of users selected either 'Expensive' or 'Went to a competitor' as a reason for cancelling subscription.
- ~30% selected either 'Not useful' or 'Bad customer service.'
- Not finding the product useful was the first reason users selected for cancelling their subscription, followed by 'expensive' and 'going to a competitor.'

**Recommendations:**
- Do we need a third reason, or should we improve user experience by removing the third option?
- Add an open-ended question encouraging users to give more specific feedback, ex: 
 - What part of the product did not meet your expectations? 
 - How can we improve the product? 
 - What improvement or added feature would you find helpful in using the product?
 - What can we do that our competitors can't that would keep users from churning? What is our competitive advantage? How can we improve it or communicate it more effectively?
- Since most users have selected "Expensive" and "Not Useful" as reasons for canceling, we should roll out better onboarding and provide more help early in their subscription to ensure they understand the product and find it useful. If they find the product more useful and valuable, they may also become less cost-sensitive.
- For cost-conscious users, we could also implement a rescue tactic at the start of the cancellation workflow that offers a substantial discount to keep their subscription.
- Since the most common secondary cancellation reason is "Went to Competitor," we should research the market and ensure we stay up to date with industry trends.

## Next Steps:
- Explore the engagement of canceled subscriptions and see how they interacted with the product. 
  - What features did they or did they not use? How often did they use the product? What if we compare them to non-cancelled subscriptions? Does anything stand out that could inform future retention efforts?
- Work with the product manager to understand how we can improve the cancellation workflow by adding in rescue tactics and adding friction without increasing user frustration.
