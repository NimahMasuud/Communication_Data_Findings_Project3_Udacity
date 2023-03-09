# (Dataset Exploration of Ford GoBike System Data)
## by (your Nimatallahi Masuud)


## Dataset
### Introduction

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
>The dataset contains 183,412 entries including information about when and where the trip began and finished, the duration of each trip in seconds, and some user information. The goal is to determine the relationship between trip duration and bike share for all trips and other explanatory variables in the dataset
>The dataset has 16 columns and misappropriate Data type in the for start_time and end_time columns.

### Main Interest in the dataset/Features that help support my investigation
>My main feature(s) of interest in this dataset are: duration_sec,duration_minute and bike_share for all_trip and The features that help in this investigation are user_type, member_gender, member_birth_year(age), start_time, end_time(hour, day and month)



## Summary of Findings

> The following are the important findings in the Data Wrangling & cleaning process.

1. The missing values found were removed as they didn't show any statistical significance in the dataset.

2. The datetime columns types were converted to an appropriate data type.

3. New features were created from datetime columns (showing day, day of week, hour) to give more insights.

4. New feature was created from the member_birth year to form the age column and member birth year column was removed.

5. Outliers were detected in the age columns and removed due to non-statistical significance.

6. Some unnecessary features were removed to focus more on the significant features

>The following are the important Findings in Data from exploratory visualizations

1. Most Users are subscribers as 90.93% of total trips are for subscribers showing that people will be more likely to engage in the service on consistent basis and subscribe.

2. Customers have consistently longer trips across all hours of the day. However,subcribers has shorter trips 

2. Males represent around 76.2 % of the total trips giving more indication about females not prefering bikes as go to for workouts.

3. There is a clear different usage pattern between customers and subscribers
between features.

4. Trips duration is highest at age range from 20 to 40 as they are the most users.

5. Youthful members are more willing to share the bike.

6. Most trips fall in Thursday,Tuesday,Friday and this indicate that people use bike trips mostly for work and school. 

7. Customers on the other hand tend to use bikes for fun, their usage is concentrated during weekend and majorly for entertainmen.

8. Rush hour in bike trips would be between around 7 - 9am and 4 -6pm which is very logical and this might be related to the time when employees and students go to and leave work and school.

9.The distribution of both Start and End of Day of week shows that the demand for trips gradually increases from its highest levels on Thursday it then declines untill reaching its lowest levels on Saturday and Sunday. This is due to the fact that Saturday and Sunday are the weekend in the United States of America.


## Key Insights for Presentation

1. Most Users are subscribers as 90.93% of total trips are for subscribers showing that people will be more likely to engage in the service on consistent basis and subscribe.

2. Most trips fall in Thursday,Tuesday,Friday and this indicate that people use bike trips mostly for work and school.

3. The distribution of both Start and End of Day of week shows that the demand for trips gradually increases from its highest levels on Thursday it then declines untill reaching its lowest levels on Saturday and Sunday. This is due to the fact that Saturday and Sunday are the weekend in the United States of America.
