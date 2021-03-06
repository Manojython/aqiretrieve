# aqiretrieve
Python package for AQI retrieval from EPA API

AQI Retrieve provides the data for the Air Quality Index of the United States from the [AirNow](https://www.airnow.gov/).
The data collected is at a County level.

Current air quality data for more than 500 cities across the U.S.

The dataset that is generated consists of the following columns:

1. State
2. County
3. Date
4. Ozone
5. PM 2.5
6. PM 10

Description for each of above item can be found [here](https://www.airnow.gov/all-publications/)

**Usage:**
```
from aqiretrieve import getData

getData()

```
Since we retrieve data for each state, it requires quite some time depending on the provided date range.

This will create a .csv file with the aforementioned Columns

All we are doing here is getting the data from AirNow.gov and converting the same to a readable CSV file. 

Complete credit for all the data goes to [AirNow](https://www.airnow.gov/)





