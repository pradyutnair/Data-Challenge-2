# Dataset Creation
The primary focus is on the Street Dataset provided by the Government of UK and is available here- https://data.police.uk/data/ 

### Step 1

The data was filtered to only include the years 2017-2021 and rows containing reports by the 'City of London Police.'

### Step 2

Additional data was gathered externally. The features and sources have been listed down below:

1. **Sun Hours in the UK**: https://www.statista.com/statistics/322602/monthly-average-daily-sun-hours-in-the-united-kingdom-uk
2. **Unemployment Rate in the UK**: https://www.ons.gov.uk/employmentandlabourmarket/peoplenotinwork/unemployment/timeseries/mgsx/lms
3. **HPI of London**: https://www.statista.com/statistics/286025/united-kingdom-uk-monthly-house-price-index-in-london/

### Step 3

The features were then manually input into a csv file and aggregated with the index set to a YYYY-MM format. The final dataset has five columns with the first one 
being the Month (Index) and the last attribute being Total Antisocial Behaviour and Public Order Crimes.


