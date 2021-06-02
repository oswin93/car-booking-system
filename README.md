# Car-Booking-System
Cab booking system is the process where renting a cab is automated through an app throughout a city
Using this app, people can book a cab from one location to another location. 
Being a cab booking app company, exploiting the understanding of cab supply and demand
could increase the efficiency of their service and enhance user experience by minimizing
waiting time.
# Objective of this project is to combine historical usage pattern along with the open data sources like weather data to forecast cab booking demand in a city.
Data is randomly divided into train and test set. we must predict the total count of cabs booked in each hour covered by the
test set, using the information available prior to the booking period. we need to append the train_label dataset to train.csv as ‘Total_booking’ column.
* Please find the descriptions of the columns present in the dataset as below.
1. datetime - hourly date + timestamp
2. season - spring, summer, autumn, winter
3. holiday - whether the day is considered a holiday
4. workingday - whether the day is neither a weekend nor holiday
5. weather - Clear , Cloudy, Light Rain, Heavy 
6. temp - temperature in Celsius
7. atemp - "feels like" temperature in Celsius
8. humidity - relative humidity
9. windspeed - wind speed
10 Total_booking - number of total booking
# Following are the tasks, which is developed while executing the project
1. Visualize data using different visualizations to generate interesting insights
2. Outlier Analysis
3. Missing value analysis
4. Visualizing Total_booking Vs other features to generate insights
5. Correlation Analysis
6. Feature Engineering
7. Grid search
8. Regression Analysis
9. Ensemble Model
