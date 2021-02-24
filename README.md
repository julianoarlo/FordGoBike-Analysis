# Project: Ford Gobike Data Analysis

# Steps of the Project:
1. Choose the dataset
2. Explore the data
3. Document the story


# 1. Choose the dataset
In this project, I will analyze the data of a bike rental company Ford GoBike’s Trips in San Francisco. I will use FordGoBike Trip data on the month February 2019 as a reference. After gathering the data, I will clean and analyze it, then give insights and visualizations of the analysis of the dataset.

# 2. Explore the data
The dataset contains data of 183,412 bike trips using Ford GoBike with 16 variables such as user characteristics (age, gender, etc.), start and end times, and station locations. At first, I made some general analysis on the overall average durations, most common days of trips, starting times, and user types. Then, I analyzed the top 10 stations with the most trips and decided to subset the dataset by choosing the top 5 stations with the most trips. Then, I made further analysis for the subsetted dataset.

# 3. Document the story
For the general dataset, I made some univariate and bivariate explorations. I found that there are on average substantially more trips on Weekdays than Weekends. I also found that the most common starting times to use the bikes are at peak hours, which are at the start and end of working hours, i.e. around 8:00 and 17:00. The bike users are also mostly subscribers, and the average bike time is around 9 minutes with most of the trips being under 10 minutes. This is consistent to show that the bikes are mostly used as a transportation to work on Weekdays by the same people which subscribes to Ford GoBike, which most likely lives near their workplaces hence explaining the low average duration of 9 minutes.

Then, I subsetted the data for the top 5 stations to make some further univariate, bivariate and multivariate explorations. I separated the trip counts in the top 5 stations by three time periods (morning, afternoon, and night) to see if any stations are busy in a particular time period of the day. I also made multivariate explorations to combine variables such as average duration, gender, age, user types, and days of the week across the top 5 stations. A more detailed explanation for each analysis is provided in the proceeding files.