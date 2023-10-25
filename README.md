# Big Data Project: Analyzing the Impact of Weather on Flight Delays

## Project Overview

In this Big Data project, I explored the relationship between various weather conditions and flight delays, using Hadoop and Spark, executing queries within a Jupyter Notebook to provide insightful answers to critical business questions.

## Data Sources

**Weather Data**: [US Weather Events (2016 - 2021) | Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-weather-events)
- **Description:** This extensive dataset encompasses 7.5 million weather events across 49 U.S. states, chronicling a wide range of weather phenomena such as rain, snow, storms, and freezing conditions. It draws from historical weather reports collected from 2,071 airport-based weather stations nationwide between January 2016 and December 2021.

**Airline Delay and Cancellation Data**: [Airline Delay and Cancellation Data, 2009 - 2018 | Kaggle](https://www.kaggle.com/datasets/yuanyuwendymu/airline-delay-and-cancellation-data-2009-2018)
- **Description:** This dataset, provided by the U.S. Department of Transportation's Bureau of Transportation Statistics, meticulously tracks the on-time performance of domestic flights operated by major carriers. It offers daily airline information spanning over a decade.

## Business Questions

Our analysis, conducted within the timeframe of 2016-17, focuses on answering several pivotal business questions:

1. Is there a substantial correlation between hail events and flight delays?
2. Are cold weather days significantly associated with flight delays?
3. What weather conditions exert the most pronounced impact on flight delays?
4. How often do weather events like fog and storms affect airline schedules?
5. What is the percentage change in weather events affecting airline schedules from 2016 to 2017?

## Key Insights

### Hail and Flight Delays
Despite a notable percentage increase in hail incidents from 2016 to 2017, the relatively low sample size (less than 500 incidents) prevents us from drawing meaningful conclusions regarding the impact of hail on flight delays.

### Cold Weather Days and Flight Delays
Contrary to expectations, the frequency of cold weather days witnessed a 6.6% decrease from 2016 to 2017, dropping from 28,544 to 26,660 days. This suggests a lack of correlation between cold weather days and flight delays.

### Impactful Weather Conditions
The weather conditions with the most significant impact on flight delays, in order, are Rain (6.90%), Storm (4.20%), and Fog (2.21%).

## Based on our analysis, the following conclusions emerge:

1. **Hail**: While hail incidents experienced a significant increase, it's important to note that the sample size is extremely low, with fewer than 500 incidents. Therefore, drawing meaningful conclusions about the impact of hail on flight delays is not feasible.

2. **Rain**: Rain, with the most substantial percentage increase, becomes an influential factor in our analysis. The sample size, exceeding 600,000 incidents, provides a solid foundation for drawing conclusions.

3. **Storms**: Storms also show a noticeable increase in incidents. Although the sample size ranges from 6,400 to 6,800, it is meaningful enough to suggest that storms have a significant impact on flight timing.

4. **Fog**: While fog incidents saw a slight increase and did affect the number of flight delays, the impact was relatively minor compared to the factors mentioned above.

5. **Snow and Cold**: Surprisingly, both snow and cold weather incidents decreased from 2016 to 2017. These categories had a substantial number of incidents. As such, we can confidently conclude that snow and cold weather are less influential in terms of flight delays.

## Business Recommendations

Our findings lead us to recommend a focused approach to mitigating flight delays:

- **Prioritize Rain, Storm, and Fog:** Days with these weather conditions have the most substantial impact on flight delays. Rain, in particular, stands out as a significant factor.

- **Implement Adjusted Schedules:** To minimize the costs associated with delays, including direct costs to passengers and indirect costs, we suggest closely monitoring flights during these weather conditions and implementing schedules that account for potential delays.
