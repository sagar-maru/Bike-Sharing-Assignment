# Bike Sharing Assignment
> This project focuses on analyzing bike-sharing data to understand the factors influencing bike demand. We built a linear regression model to predict the number of bike rentals based on several independent variables such as temperature, season, and more.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information

BoomBikes is facing significant revenue declines due to the ongoing pandemic. This situation requires a strategic solution. The company struggles to remain viable in the current market, which demands a thoughtful business plan. To recover, BoomBikes wants to boost revenue after the lockdown ends. Understanding bike demand post-quarantine is crucial.

The main objectives include predicting the key variables that affect shared bike demand in the American market. The goal is to identify the most important predictors and develop a model to understand how demand varies. This will help the company adapt its business strategies effectively. The case study will build a multivariate linear regression model using the available dataset. The primary aim is to pinpoint the key factors that significantly influence bike demand and assess how well these factors explain demand patterns.

- The goal of this project is to predict the demand for shared bikes. Bike-sharing programs are growing rapidly, and predicting bike demand is crucial for efficient fleet management and customer satisfaction.
- The project helps solve the business problem of matching supply and demand. By predicting bike rentals based on historical data, operators can better allocate bikes to different stations and plan for periods of high or low demand.
- We used a dataset that includes features such as temperature, humidity, windspeed, season, and holiday information to build our model. The dependent variable, `cnt`, represents the number of bike rentals.

### Problem Statement

A bike-sharing system provides bikes for short-term use, either for a fee or for free. Users can borrow bikes from a dock, which is often computer-controlled. To unlock a bike, users enter payment information, allowing them to take the bike and return it to another dock in the same system.

BoomBikes, a bike-sharing provider in the U.S., has faced significant revenue drops due to the ongoing COVID-19 pandemic. The company struggles to remain viable in the current market. To address this challenge, BoomBikes aims to develop a strategic business plan to boost revenue as the lockdown ends and the economy recovers.

BoomBikes seeks to understand the demand for shared bikes once the quarantine lifts. They want to prepare to meet public needs and distinguish themselves from competitors to maximize profits. To do this, they have hired a consulting firm to identify the factors that influence bike demand.

Specifically, BoomBikes wants to determine:
- Which variables significantly predict the demand for shared bikes.
- How effectively these variables explain bike demand.

The consulting firm has gathered a large dataset on daily bike demands in the U.S., based on various factors including weather conditions and user habits. This data is crucial for analyzing demand patterns.

### Business Goal

The primary goal is to create a model that predicts the demand for shared bikes using the independent variables available. This model will help management understand how demand varies with different features. By understanding these relationships, the company can adjust its business strategy to better align with customer needs.

With insights from the model, BoomBikes can effectively plan its operations, ensuring they have the right number of bikes available during peak demand times. They can also tailor marketing efforts to target potential customers more effectively. Understanding demand dynamics will be essential for navigating the new market conditions post-pandemic.

In conclusion, BoomBikes is determined to revitalize its business by leveraging data-driven insights. The analysis will provide the foundation for strategic decisions that enhance customer satisfaction and drive profitability. By focusing on significant variables influencing bike demand, BoomBikes can ensure a successful recovery and growth in the competitive bike-sharing market.

## Conclusions
- **Temperature is a significant factor**: The temperature has the highest correlation with bike rentals. As temperatures increase, more people tend to rent bikes. In our model, the coefficient for temperature is 1170.38, indicating a large positive effect on bike rentals.
  
- **The year variable shows increasing demand**: The year (`yr`) has a positive coefficient of 997.29. This indicates that the demand for bike rentals has increased over time. More people are likely using the bike-sharing service in 2019 compared to 2018.

- **Winter season contributes positively**: Contrary to expectations, the Winter season has a positive coefficient of 528.64, suggesting higher bike rentals during this season. This could be due to mild winters or specific events that increase demand.

- **Holidays have a negative impact**: The holiday variable has a coefficient of -124.38, indicating that fewer bikes are rented on holidays. People may not use bikes for commuting on these days, leading to a drop in demand.

- **Working days show stable rentals**: Rentals are consistently higher on working days compared to holidays, as shown by the stable median values observed in box plots.

- **Effect of windspeed and humidity**: Windspeed has a negative effect on bike rentals, with a coefficient of -347.50. As windspeed increases, fewer bikes are rented, likely due to unfavorable riding conditions.

- **Fall and September show the highest demand**: The Fall season and the month of September exhibit the highest demand for bike rentals. This is likely due to comfortable weather conditions, making these periods ideal for biking.

- **Pair-plot analysis**: From the pair-plot among the numerical variables, temperature was found to have the highest correlation with the target variable, `cnt`. This insight confirms the importance of including temperature in our prediction model.

## Technologies Used
- Python 3.8
- Pandas - version 1.3.3
- Seaborn - version 0.11.2
- Matplotlib - version 3.4.3
- Statsmodels - version 0.12.2
- Scikit-learn - version 0.24.2

## Acknowledgements
- This project was inspired by the increasing popularity of bike-sharing programs around the world.
- Dataset Source: "[Day](https://github.com/sagar-maru/Bike-Sharing-Assignment/blob/main/day.csv)" along with data info in "[Data Dictionary](https://github.com/sagar-maru/Bike-Sharing-Assignment/blob/main/Data%20dictionary.txt)".
- Dataset Inspired By: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php).
- Special thanks to the various Python libraries and tools that made this project possible.

## Contact
Created by [Sagar Maru](https://github.com/sagar-maru) - feel free to reach out!
