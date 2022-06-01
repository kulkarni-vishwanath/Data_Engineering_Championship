# Data_Engineering_Championship

### All you need to know about the ‘Data Engineering Championship’

With the dataset provided, the participants need to analyse and create features of the following description.

* 'DATE': create the date from year, month and day of the week
* 'LOW': Lower value of DEP_TIME_BLK
* 'HIGH': Higher value of DEP_TIME_BLK
* 'TIMESTAMP': create a timestamp with date and lower value of DEP_TIME_BLK
* 'WIND_CHILL':  the perceived temperature due to cooling effect of wind blowing
* 'PRCP_SNOW_RATIO': ratio of precipitation and snow
* 'PLANE_AGE_AIRLINE_AIRPORT_FLIGHTS_MONTH_RATIO': ratio of plane age and airline and airport flights months.
* 'SEAT_DISTRIBUTION': Ratio of seats and in  concurrent flight CONCURRENT_FLIGHTS
* 'SEAT_DISTRIBUTION_NORMALISED': normalized values of ratio of seats and in  concurrent flight


### Data Description

| __Variable__ | __Description__ |
|-------------|------------|
| MONTH          | Month|
| DAY_OF_WEEK          | Day Of Week |
| DEP_DEL15  |Binary of a departure delay over 15 minutes (1 is yes) |
| DISTANCE_GROUP | Distance group to be flown by departing aircraft |
| DEP_BLOCK | Departure block |
| SEGMENT_NUMBER | The segment that this tail number is on for the day |
| CONCURRENT_FLIGHTS | Concurrent flights leaving from the airport in the same departure block |
| NUMBER_OF_SEATS | Number of seats on the aircraft |
| CARRIER_NAME | Carrier  |
| AIRPORT_FLIGHTS_MONTH | Avg Airport Flights per Month |
| AIRLINE_FLIGHTS_MONTH | Avg Airline Flights per Month |
| AIRLINE_AIRPORT_FLIGHTS_MONTH | Avg Flights per month for Airline AND Airport |
| AVG_MONTHLY_PASS_AIRPORT | Avg Passengers for the departing airport for the month |
| AVG_MONTHLY_PASS_AIRLINE | Avg Passengers for the airline for the month |
| FLT_ATTENDANTS_PER_PASS | Flight attendants per passenger for airline |
| GROUND_SERV_PER_PASS | Ground service employees (service desk) per passenger for airline |
| PLANE_AGE | ge of departing aircraft |
| DEPARTING_AIRPORT | Departing Airport |
| LATITUDE| Latitude of departing airport |
| LONGITUDE|  Longitude of departing airport|
| PREVIOUS_AIRPORT| Previous airport that aircraft departed from |
| PRCP| Inches of precipitation for the day |
| SNOW| Inches of snowfall for the day|
| SNWD| Inches of snow on the ground for the day |
| TMAX| Max temperature for the day |
| AWND| Max wind speed for the day |

### Evaluation Metric
The evaluation metrics for this competition is [mean absolute error](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html#sklearn-metrics-mean-absolute-error)

### Leaderboad
**LB Score:** 1.69

**LB Rank:** 20/89

Link to the Leaderboard can be found [here](https://machinehack.com/hackathons/data_engineering_championship/leaderboard).
