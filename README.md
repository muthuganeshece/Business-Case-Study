# Business Case study
Hi👋🏾, Welcome to the Business Case Study Repository! This repository contains a collection of business case studies of various industries dataset.

## Contents
- [**Target Retail Analytics using SQL**](https://github.com/muthuganeshece/Business-Case-Study/blob/8a3da1c8c4bdea8212ad72e94cd8f0bef5fd3d32/Target%20SQL/Solution/Target_SQL.pdf)
- [**Netfix Data Exploration and Visualization**](Netflix/Notebook/EDA.ipynb)
- [**Aerofit Descriptive Analytics**](Aerofit/Notebook/EDA.ipynb)
- [**Walmart Data Analytics: CLT and Confidence Interval**](Walmart/Notebook/Walmart_CLT.ipynb)
- [**Yulu Data Analytics: Hypothesis Testing**](Yulu/Notebook/Yulu_HypothesisTesting.ipynb)

## Target Retail Analytics
- #### Tools and Libraries
  - SQL

## Netfix Data Analytics
To enhance Netflix's revenue, a key strategy is to increase user subscriptions. This can be achieved by analyzing the existing Netflix dataset to identify patterns, preferences, and gaps in the current content offerings. By understanding what drives user engagement and satisfaction, we can make data-driven decisions to attract and retain more subscribers.
  - #### Tools and Libraries
    - Python, Numpy, Pandas, Matplotlib, Seaborn
  - #### Business Insights and Recommendations
    - ***Expand Classic Movie Selection:***
      - `Most movies on Netflix are released after 2010. Including more classic films will attract users from older age groups.`
    - ***Increase Animation Content:***
      - `The platform currently features movies predominantly for adult age groups. Adding more animated movies for kids will attract teenage users.`
    - ***Broaden Geographic Diversity:***
      - `Netflix hosts movies and TV shows from 123 countries. Adding content from the remaining ~70 countries will expand the customer base in those regions.`
    - ***Increase Netflix Originals:***
      - `Only a few movies (2) have been released directly on Netflix before hitting theaters. Increasing this number could boost user engagement.`
    - ***Enhance January and February Lineup:***
      - `Fewer movies and TV shows are added in January and February. Increasing content additions during these months will provide more options for users during this period.`
    - ***Include Influential South Indian Actors:***
      - `In South India, there is a high interest in movies and TV shows, yet none of the influential South Indian actors are listed among Netflix's top 10 actors. Including movies featuring these actors will increase the customer base in those regions.`
    - ***Increase Indian TV Shows:***
      - `Despite India being the second-largest contributor of movies, it ranks seventh in terms of TV shows. Increasing the number of Indian TV shows will expand the customer base.`
    - ***Add More Long-Running TV Shows:***
      - `Currently, only 17 TV shows on Netflix have more than 10 seasons. Increasing the number of shows with longer seasons can help extend user subscriptions.`
    - ***Diversify Genres:***
      - `The genres of movies and TV shows are not uniformly distributed. Horror and sci-fi fantasy movies are comparatively fewer. Increasing content in these genres will attract a broader audience to the platform.`

## Aerofit Descriptive Analytics
Aerofit, a leading brand in the fitness equipment industry, offers a diverse product range including treadmills, exercise bikes, gym equipment, and fitness accessories. To enhance revenue, we aim to provide actionable recommendations based on detailed insights gathered from the sales data. The dataset consists of three months of sales data.
  - #### Tools and Libraries
    - Python, Numpy, Pandas, Matplotlib, Seaborn
  - #### Business Insights and Recommendations
    - ***Female Users:***
      - `Female users have shown less interest in purchasing the KP781 product, regardless of income or other parameters. Offering them an additional discount on Women's Day could increase the likelihood of purchase`
    - ***Partnered Users:***
      - `Partnered users demonstrate a higher interest in buying the treadmill. Focusing advertisements on newlyweds or partnered users can help boost sales.`
    - ***Higher Income Partnered Users:***
      - `Partnered users in the higher income group purchasing the KP781 fall within a narrower age range, implying that newly partnered users are highly likely to make a purchase. Targeting these customers with discounts or promotions could be effective.`
    - ***High Usage Users:***
      - `The KP781 can be recommended to users with higher usage per week, as they are more likely to make a purchase.`

## Walmart Data Analytics: CLT and Confidence Interval
  - #### Tools and Libraries
    - Python, Numpy, Pandas, Scipy, Stats.models, Matplotlib, Seaborn
  - #### Business Insights and Recommendations
    - ***Purchasing Trends:***
        - On Black Friday, the mean purchase amount for men is significantly higher than for women. Offering higher discounts to women could potentially increase revenue. Therefore, targeted promotions based on the gender is likely to have a noticeable impact on revenue.The Hypothesis test also proved the same.
    - ***Marital Status Insights:***
        - Unmarried customers contribute the majority of sales. However, the revenue contribution between unmarried and married customers is not significantly different, making it challenging to distinguish between their mean values with confidence intervals of 90%, 95%, and 99%.
    - ***Age Group Insights:***
        - The 18-45 age group contributes to approximately 75% of sales. Expanding the product variety and increasing discounts on items suitable for other age groups could attract a broader customer base and boost sales.
        - From the Central Limit Theorem analysis, not all age groups exhibit significant differences in purchasing behavior. However, certain age groups do show significant differences. Therefore, targeted promotions based on age groups are likely to have a noticeable impact on revenue.
    - ***City-Specific Promotions:***
        - To increase sales, plan promotional campaigns specifically targeting cities A and C, where there is significant potential for growth.

## Yulu Data Analytics: Hypothesis Testing
- #### Tools and Libraries 
  - Python, Scipy, Statsmodels, combinations
- #### Business Insights and Recommendations
  - ***Trends:*** 
    - Average number of cycles rented is similar between working and non working days
    - Average number of cycles rented is significantly different between each seasons
    - Average number of cycles rented is significantly different between each weather conditions
    - Chisquare test confirmed that Weather condition and season are related
