# Proposal: NYC Trip-Duration Prediction
## Introduction:
The goal of this statistical analysis is to help us understand the relationship between trip duration and other features in the dataset that affect the trip duration.

## Business Problem:
Predect the trip duration time that depends on specific features extracted from the dataset.
## Project Management Approach:
 - Scrum
 
## Data description:
- **id**:  a unique identifier for each trip
- **vendor_id:**  a code indicating the provider associated with the trip record
- **pickup_datetime:** date and time when the meter was engaged
- **dropoff_datetime:** date and time when the meter was disengaged
- **passenger_count:**  the number of passengers in the vehicle (driver entered value)
- **pickup_longitude:** the longitude where the meter was engaged
- **pickup_latitude**   the latitude where the meter was engaged
- **dropoff_longitude:** the longitude where the meter was disengaged
- **dropoff_latitude:**  the latitude where the meter was disengaged
- **store_and_fwd_flag:**  This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to  the server - Y=store and forward; N=not a store and forward trip.
- **trip_duration:**  duration of the trip in seconds

## Size of Data:
  - Number of rows: 1458644
  - Number of columns: 11
## Dataset sourec:
from Kaggle website [[Kaggle]](https://www.kaggle.com/c/nyc-taxi-trip-duration/data)

## Questions:
1. which days has the highest number of passengers? Or in which hour?
2. What is the relationship between the location and the trip duration?
3. which days contain the Highest time duration? (Days of traffic!!)
4. In which place was the largest number of passengers?
5. Is the duration time of the trip affect the number of passengers per day?
6. Is the passenger number affect the trip duration?
7. What’s the number of trips per hour in each day?
8. Are there specific locations with long trip duration? 

## Algorithms:
- Linear Regression
- Polynomial Regression

## Tools:
### Softwares:
<hr>

1. VScode
2. Trello
3. Jupyter
4. Github
5. PowerPoint
6. Zoom

### Languages & Libarry
<hr>

1. Python
   - Pandas
   - numpy
   - seaborn
   - plotly
   - sklearn
   
## MVP goals:
1. Find out what factors affect on the trip duration.
2. We want to know which neighborhood have alot of trafic.
3. Find how many trip per hour we can reach in one day.
4. We want to see if there is a specific day that have alot of trafic.

## Team Members
 - Shatha Alghamdi | Leader
 - Elham Alzahrani
 - Ayad ALHarbi
 - Shaima Alzahrani

