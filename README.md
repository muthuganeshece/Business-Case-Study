ji# Business Case study
Hi👋🏾, Welcome to the Business Case Study Repository! This repository contains a collection of business case studies of various industries dataset.

## Contents
- [**Target Retail Analytics using SQL**](https://github.com/muthuganeshece/Business-Case-Study/tree/main/Target%20SQL)
- [**Netfix Data Exploration and Visualization**](Netflix/Notebook/EDA.ipynb)
- [**Aerofit Descriptive Analytics**](Aerofit/Notebook/EDA.ipynb)
- [**Walmart Data Analytics: CLT and Confidence Interval**](Walmart/Notebook/Walmart_CLT.ipynb)
- [**Yulu Data Analytics: Hypothesis Testing**](Yulu/Notebook/Yulu_HypothesisTesting.ipynb)
- [**Delhivery Feature Engineering: Feature Cleaning & Transformation**](Delhivery/Notebook/Delhivery_FeatureEngineering.ipynb)
- [**Jamboree Education: Linear Regression**](Jamboree/Notebook/Jamboree_LinearRegression.ipynb)
- [**LoanTap: Logistic Regression**](LoanTap/Notebook/LoanTap_LogisticRegression.ipynb)

## Target Retail Analytics
  - #### Tools and Libraries
    - SQL, BigQuery
  - #### Recommendations
    - `Based on Freight Value The freight value for SP, RJ and MG are the highest, indicating that many products ordered from these states may not have nearby sellers. Consequently, identifying frequent product sellers from these states or nearby could help reduce freight costs.`
    - `Based on customer strength in states Customers are not evenly distributed across states; approximately 70% of customers are from SP, RJ, and MG. Moreover, it's likely that a significant portion of these customers resides in tier I cities. Focusing promotional efforts on tier II cities could potentially boost revenue. Additionally, implementing targeted advertising and offering discounts based on geographical location may further enhance sales.`
    - `Based on payment Given the predominant use of credit cards in purchases, implementing discounts or cashback offers tied to credit card could significantly enhance sales`

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
        - `On Black Friday, the mean purchase amount for men is significantly higher than for women. Offering higher discounts to women could potentially increase revenue. Therefore, targeted promotions based on the gender is likely to have a noticeable impact on revenue.The Hypothesis test also proved the same.`
    - ***Marital Status Insights:***
        - `Unmarried customers contribute the majority of sales. However, the revenue contribution between unmarried and married customers is not significantly different, making it challenging to distinguish between their mean values with confidence intervals of 90%, 95%, and 99%.`
    - ***Age Group Insights:***
        - `The 18-45 age group contributes to approximately 75% of sales. Expanding the product variety and increasing discounts on items suitable for other age groups could attract a broader customer base and boost sales.`
        - `From the Central Limit Theorem analysis, not all age groups exhibit significant differences in purchasing behavior. However, certain age groups do show significant differences. Therefore, targeted promotions based on age groups are likely to have a noticeable impact on revenue.`
    - ***City-Specific Promotions:***
        - `To increase sales, plan promotional campaigns specifically targeting cities A and C, where there is significant potential for growth.`

## Yulu Data Analytics: Hypothesis Testing
- #### Tools and Libraries 
  - Python, Scipy, Statsmodels, combinations
- #### Business Insights and Recommendations
  - ***Trends:*** 
    - `Average number of cycles rented is similar between working and non working days`
    - `Average number of cycles rented is significantly different between each seasons`
    - `Average number of cycles rented is significantly different between each weather conditions`
    - `Chisquare test confirmed that Weather condition and season are related`
  - ***Weather-Based Insights:***
    - Obseravation: 
    	- `Light weather conditions (Weather 1 and 2) see high usage of the cycles.`
    - Recommendation: 
    	- `Focus marketing efforts and offer discounts or reduced costs during Weather 1 and 2 conditions to capitalize on high demand`
    	- `Hypothesis test also concludes that Average number of cycles rented is significantly different for weather 1 and 2. Hence the strategies involving weather 1 and 2 will make a significant impact whereas the weather 2 doesn't.`
    	- `Utilize dynamic pricing models that adjust costs based on real-time weather conditions, prioritizing Weather 1 for promotions to maximize revenue.` 
  - ***Weekly usage-Based Insights:***
    - Obseravation: 
    	- `Registered users are predominant on weekdays indicates tbat they rent cycles for commuting to work/students`
    	- `Casual users are predominant on weekends indicating that they commute for leisure`
    	- `Users count during holiday and working day also confirms the above point`
    - Recommendation:
    	- `Increase efforts to grow the registered user base to boost weekday revenue, as they tend to have higher usage rates`
    	- `Introduce weekday subscription plans or loyalty programs for registered users to encourage frequent use`
    	- `On weekends, tailor promotions and offers to attract casual users with leisure-oriented marketing`
      - `Design weekend packages that appeal to casual users, such as group discounts or event partnerships`
  - ***YoY Growth Insights:***
    - Obseravation: 
    	- `Year-over-year (YoY) user growth indicates that current promotion strategies are effective.`
    - Recommendation:
    	- `Continue and refine existing promotional strategies that have proven successful.`
    	- `Analyze which promotional channels and messages have driven the most growth and amplify those efforts.`  
  - ***Time-Based Insights:***
    - Obseravation:
    	- `The average number of casual users peaks between 13:00 and 17:00, indicating high demand during these hours.`
    - Recommendation: 
    	- `Implement dynamic pricing during peak hours to manage demand and maximize revenue. Adjust pricing to reflect the higher value of cycles during peak usage times`
    	- `Set up a pricing model that increases rates during peak hours (13:00-17:00) while offering discounts during off-peak times to balance demand throughout the day`
  - ***Temperature-Based Insights:***
    - Observation: 
    	- `Cycle usage is positively correlated with temperature`
    - Recommendation:
    	- `Hypothesis testing confirms that the average number of cycles rented varies significantly with temperature. Hence the strategies involving temperature bin will make a significant impact`
    	- `Incorporate temperature data into dynamic pricing models. Increase prices during favorable temperature conditions (higher usage) and consider lowering prices or offering incentives when conditions are less ideal.`
    	- `Utilize accurate weather prediction APIs to anticipate demand and adjust pricing accordingly.`

  - ***Humidity-Based Insights:***
    - Observation:
    	- `Cycle usage is negatively correlated with humidity` 
    - Recommendation:
    	- `Hypothesis testing confirms that the average number of cycles rented varies significantly with humidity. Hence the strategies involving humidity will make a significant impact`
    	- `Incorporate humidity data into dynamic pricing models. IAdjust pricing based on humidity levels to encourage usage during less favorable conditions.`
    	- `Utilize accurate weather prediction APIs to anticipate demand and adjust pricing accordingly.`

  - ***Day-Based Insights:***
    - Observation:
    	- `The average number of cycles rented is not significantly different between working days and non-working days`
    - Recommendation:
    	- `The strategies involving working day doesn't significantly impact`
    	- `Maintain consistent pricing across working and non-working days`

  - ***Season-Based Insights:***
    - Observation:
    	- `The average number of cycles rented varies significantly between seasons`
    - Recommendation:
    	- `The strategies involving each seasons will make significantly impact`
    	- `Increase prices during peak seasons with high demand and offer discounts or promotions during off-peak seasons to encourage usage`
    	- `Create seasonal marketing campaigns that highlight the benefits of cycling in each season`

## Delhivery Feature Engineering: Feature Transformation & Cleaning
- #### Tools and Libraries 
  - Python, Numpy, Pandas, Matplotlib
- #### Feature Transformations
  - `data => data`
  - `trip_creation_time => trip_creation_date, trip_creation_hour`
  - `route_type => Cart, FTL`
  - `trip_uuid => trip_uuid`
  - `source_center => Dropped`
  - `source_name => source_city, source_state`
  - `destination_name => dest_city, dest_state`
  - `start_scan_to_end_scan => start_scan_to_end_scan`
  - `is_cutoff => is_cutoff`
  - `cutoff_factor => cutoff_factor`
  - `cutoff_timestamp => cufoff_date, cufoff_time`
  - `actual_distance_to_destination => actual_distance_to_destination`
  - `actual_time => actual_time`
  - `osrm_time => osrm_time`
  - `osrm_distance => osrm_distance`
  - `segment_actual_time => segment_actual_time`
  - `segment_osrm_time => segment_osrm_time`
  - `segment_osrm_distance => segment_osrm_distance`
  - `route_schedule_uuid, source_center, destination_center, od_start_time, od_end_time, factor, segment_factor => Dropped`
- #### Business Insights
  - `All numerical variables are right-skewed with outliers, requiring data preprocessing`
  - `The dataset spans 22 days and contains only domestic deliveries`
  - `Null values are present in the source_name and destination_name fields, needing to be addressed`
  - `Data is split into 70/30 for training/testing`
  - `Actual time/OSRM time ratio (factor) and segment_actual_time/segment_osrm_time ratio (segment_factor) are key variables`
  - `The longest delivery route is between IND284403 and IND474003, consuming more time`
  - `Night trips dominate delivery creation, but take longer`
  - `Bengaluru, Hyderabad, and Mumbai handle the majority of intra-city deliveries`
  - `For intercity deliveries, the Bhiwandi <-> Mumbai and Gurgaon <-> Delhi corridors are the busiest`
  - `Maharashtra, Karnataka, and Tamil Nadu handle the majority of intra-state deliveries`
  - `Delhi <-> Haryana and Haryana <-> UP are the busiest inter-state corridors`
  - `Actual time and segment actual time follow the same distribution, but OSRM time and segment OSRM time do not, indicating inconsistencies in the OSRM data`
  - `OSRM distance and segment OSRM distance follow different distributions, highlighting discrepancies in dataset accuracy`
  - `Trucks take longer on average compared to carts, suggesting trucks are used for longer routes`
- #### Recommendations
  - ***Improve Overnight Trip Scheduling:***
    - `Overnight trips take more time to complete`
    - `To optimize, schedule multiple overnight trips to minimize delays`
  - ***Focus on Tier II and Tier III Cities:***
    - `Since the majority of deliveries occur between metro cities, redirect focus to develop logistics in tier II and III cities for future growth`
  - ***Enhance Logistics for Northern-Eastern Trips:***
    - `Although northern-southern trips cover long distances, northern-eastern trips consume more time`
    - `Invest in better logistics infrastructure to improve delivery efficiency in the eastern regions`
  - ***Recalibrate OSRM Time Algorithm:***
    - `Actual Time and OSRM Time doesn't follow same distribution, indicates that there is a mismatch in the OSRM time calcualtion algorithm`
    - `Infact, mean actual time is greater than mean OSRM time, indicates the algorithm underestimates the delivery time OSRM Time estimation algorithm to be recalibrated to better plan the deliveries`
  - ***Recalibrate OSRM Distance Algorithm:***
    - `Actual Distance and OSRM Distance doesn't follow same distribution, indicates that there is a mismatch in the OSRM distance calcualtion algorithm`
    - `OSRM Distance estimation algorithm to be recalibrated to better plan the deliveries`

## Jamboree Education: Linear Regression 
- #### Tools and Libraries 
  - Python, Numpy, Pandas, SKlearn, Statsmodel
- #### Insights
  - GRE score, TOEFL Score and CGPA are highly correlated 
  - Higher the GRE score, TOEFL score and CGPA mostly likely to get the admission
  - Students with higher test scores (GRE, TOEFL, CGPA) are mostly likely from the highly rated (3+) universities
- #### Recommendations 
  - Linear model could able to achieve 75% score it is recommended to apply non linear machine learning techniques for better score


## LoanTap: Logistic Regression 
- #### Tools and Libraries 
  - Python, Numpy, Pandas, SKlearn, Scipy
- #### Topics
  - EDA
    - UVA, BVA, MVA
    - Null Analysis
  - Outlier Treatment
  - PCA
  - Feature Transformation 
  - Statistical Tests
     - Two sample T-Test
     - Chisquare Test
  - Modeling
    - Logistic Regression 
    - Hyperparameter Tuning
  - Performance Analysis
    - Confusion Matrix 
    - AUC ROC, PR curve
- #### Business Recommendations
  - `Loans were primarily applied from only 10 unique pincodes, highlighting that borrowersare concentrated in a limited number of cities. This suggests that the "Loantap" businessis not yet widely recognized.
It is recommended that the firm expand its reach orenhance marketing efforts in other regions to boost revenue`
  - `The model exhibits a significant number of false positives, indicating a need for additional verification steps before finalizing decisions based on modelpredictions`
  - `To improve the model's performance, additional features should be incorporated infuture iterations`
  - `Around 15% of the data points contain at least one missing value. This indicates the need for a more robust data collection process to enhance model reliability andperformance`
  - `Simple logistic regression model achieves the accuracy of 85% with F1 score being 0.91`


## OLA: Ensemble Learning 
- #### Tools and Libraries 
  - Python, Numpy, Pandas, SKlearn, imblearn
- Business Insights