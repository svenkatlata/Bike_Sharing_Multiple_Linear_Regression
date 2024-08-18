# Bike Sharing - Multiple Linear Regression Problem

> To Model the demand for shared bikes with the available independent variables, which would be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model would be a good way for management to understand the demand dynamics of a new market.

## Table of Contents

- [Problem Statement](#problem-statement)
- [Conclusions](#conclusions)
- [Application of Findings](#application-of-findings)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)

## PROBLEM STATEMENT

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

## Conclusions

#### 1. Seasonal and Monthly Effects

- **Monthly Influence**:
  - The coefficients for `month_may` (0.0798) and `month_mar` (0.0499) indicate increased counts in these months, suggesting higher activity or demand.
  - The positive coefficient for `month_sept` (0.0974) also points to heightened activity in September.
- **Seasonal Influence**:
  - The positive coefficient for `season_winter` (0.1306) suggests that winter months see higher counts, potentially due to seasonal factors driving increased activity.

#### 2. Day of the Week Influence

- **Negative Impact on Mondays and Sundays**:
  - The coefficients for `weekday_mon` (-0.0270) and `weekday_sun` (-0.0324) show lower counts on these days, reflecting reduced activity.
- **Positive Impact on Saturdays**:
  - The positive coefficient for `weekday_sat` (0.0263) suggests that Saturdays experience higher counts, possibly due to increased weekend activities.

#### 3. Weather Conditions

- **Negative Impact of Bad Weather**:
  - The negative coefficient for `weather_situations_bad` (-0.1404) indicates a significant decrease in counts during bad weather, showing the impact of adverse conditions on activity.

#### 4. Influence of Temperature, Humidity, and Wind Speed

- **Temperature**:
  - The strong positive coefficient for `temperature` (0.6100) suggests that warmer temperatures are associated with increased counts, indicating that warm weather encourages activity.
- **Humidity and Wind Speed**:
  - The negative coefficients for `humidity` (-0.2044) and `wind_speed` (-0.1247) imply that higher humidity and wind speed reduce activity levels.

#### 5. Yearly Trend

- **Positive Trend in 2019**:
  - The positive coefficient for `year_2019` (0.2242) indicates that counts were higher in 2019, suggesting a possible upward trend over time.

#### 6. Overall Model Fit

- **Model Strength**:
  - The high R-squared (0.832) and adjusted R-squared (0.828) values indicate that the model explains a substantial portion of the variance in counts.
  - The F-statistic (200.9) and its p-value (4.83e-180) confirm that the model is statistically significant.

## Application of Findings

- **Operational Planning**: The Organization can adjust their operations or staffing based on the identified seasonal and weekly patterns, preparing for higher activity during certain months and weekends.
- **Weather-Responsive Strategies**: The Company might implement strategies like offering promotions during bad weather or adjusting outdoor activities according to the forecast.
- **Long-Term Growth Preparation**: The positive trend in 2019 suggests potential future growth, encouraging businesses to scale operations or expand capacity.
- **Targeted Interventions**: Understanding the effects of temperature, humidity, and wind speed on activity can guide improvements, such as optimizing HVAC systems to enhance comfort and potentially increase activity levels.

## Technologies Used

Data Cleaning and Manipulation, and Exploratory Data Analysis using:

- Python - version 3.12.4
- NumPy - version 1.26.4
- Pandas - version 2.2.2

Data Visualization using:

- Matplotlib - version 3.9.1.post1
- Seaborn - version 0.13.2

Model Building using:

- Scikit-Learn - version 1.5.1
- Statsmodels - verion 0.14.2

## Acknowledgements

**This is an Assignment done as a part of Executive PG Programme in AI & ML from IIIT, Bangalore by upGrad.**

_Batch: ML C65_

## Contact

Reach out to the creators on GitHub using,

- [Venkat Lata](https://github.com/svenkatlata)
