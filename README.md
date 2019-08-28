# Bike-Trips-Data-Analysis

This project uses the 2017 bike trips data from [Capital Bike Share](https://www.capitalbikeshare.com/system-data)

- The data contains 4 csv files representing trips data for four quarters.
- Data has several features like ``` trip start date and time, trip end date and time, start station id and name, end station id and name, bike number and member type. ```
- Analysis is done using Univariate and Multi-variate analysis of the features and creating plots.

### Following questions were answered using the analysis
- Trend of no. of trips each day over the year and in each quarter
- From which Stations most rides are booked
- Which bikes has taken more no. of rides during the quarters.
- Which start stations and end stations have high no. of members or casual riders.
- Which type of riders have longest rides.

### Preditions
- After the analysis, I tried to predict the member type on the basis of the ride data.
- Random Forests was used with a f1 score of 0.71 on training set and 0.69 on test set. 
- Still there is a room of improvement using hyperparameter tuning. 
