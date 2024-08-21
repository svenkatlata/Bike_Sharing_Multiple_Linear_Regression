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

1. **Temperature:**

   - **Coefficient:** 0.4254
   - **Insight:** Each 1°C increase in temperature is associated with an increase of approximately 0.43 units in the target variable. Warmer temperatures have a strong positive impact, so it's crucial to ensure resources and strategies align with warmer periods to maximize outcomes.

2. **Year Effect:**

   - **2019:** Coefficient = 0.2496
   - **Insight:** Being in the year 2019 is associated with a significant increase in the target variable. This suggests a positive trend or event specific to 2019 that drove higher outcomes. Understanding these factors can help replicate success in future years.

3. **Seasonal Effects:**

   - **Spring:** Coefficient = -0.1551
     - **Insight:** The target variable decreases during the spring season. This might indicate less favorable conditions or lower demand, necessitating adjustments in operations or marketing during this period.
   - **October:** Coefficient = 0.0890
     - **Insight:** October sees a slight increase in the target variable. This positive seasonality could be leveraged for strategic planning.
   - **September:** Coefficient = 0.0718
     - **Insight:** September also shows a positive effect on the target variable, suggesting a potential for increased activity or demand during this month.
   - **July:** Coefficient = -0.0591
     - **Insight:** The target variable tends to decrease in July. This drop might be due to seasonal factors like vacations or reduced activity, requiring tailored strategies to mitigate this effect.

4. **Humidity:**

   - **Coefficient:** -0.1447
   - **Insight:** Each 1% increase in humidity is associated with a decrease of 0.14 units in the target variable. High humidity has a dampening effect, possibly making conditions less favorable. Strategies might include adjustments or incentives during humid periods.

5. **Weather Situations:**

   - **Good Weather:** Coefficient = 0.0512
     - **Insight:** Good weather situations have a positive effect on the target variable, leading to an increase. This suggests that favorable weather conditions should be a key consideration in planning and marketing efforts.
   - **Bad Weather:** Coefficient = -0.1443
     - **Insight:** Bad weather conditions lead to a significant decrease in the target variable. It's important to anticipate this drop and possibly counteract it with promotions or operational adjustments during adverse weather.

6. **Wind Speed:**

   - **Coefficient:** -0.0895
   - **Insight:** Higher wind speeds negatively impact the target variable, leading to a decrease. This could indicate less favorable conditions for activities or behaviors driving the target variable, suggesting a need for adjustments or communication during windy conditions.

7. **Weekday Saturday:**

   - **Coefficient:** 0.0908
   - **Insight:** The target variable increases on Saturdays, highlighting the importance of this day in planning operations or marketing. Higher availability and targeted promotions could help capitalize on this weekend boost.

8. **Working Day:**
   - **Coefficient:** 0.0571
   - **Insight:** The target variable is higher on working days compared to non-working days, indicating a work-related or weekday-driven demand. This insight can be used to optimize scheduling and resource allocation during the workweek.

## Recommendations:

- **Align Operations with Weather and Seasonal Trends:** Adjust availability, marketing, and resources to align with favorable weather conditions and peak months, particularly in warm weather and during high-demand months like September and October.
- **Targeted Promotions:** Use seasonal and weather-based promotions to counteract negative impacts from factors like humidity, wind, or bad weather conditions.
- **Weekend Optimization:** Increase focus on Saturdays, ensuring adequate resources and promotions to take advantage of the natural increase in the target variable on this day.
- **Monitor Annual Trends:** Analyze and adapt strategies based on annual trends, such as the significant increase observed in 2019, to sustain growth and capitalize on favorable conditions.

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
