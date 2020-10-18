# RideshareTrips
Uber, Lyft, taxi data export from the city of Chicago. Analyzed to see trends and other information in the data.

1st question was:  How far away are the pickup and dropoff locations from a CTA train station? Ultimately, if we added stations, how many less trips could we eliminate?

- Downloaded Uber/Lyft Rideshare trips 
- Downloaded taxi trips
- Downloaded CTA Stations list
- Combined rideshare and taxi trips
- Extracted unique combinations of pickup longitude and latitude, dropoff longitude and latitude
- Cross joined each combination against each CTA station.
- For each combination, how far away is each station from the dropoff/pickup location?
- For each combination, grab the closest station
- Now each pickup location has a "closest station" and each dropoff location has a "closest station"

This itself was worth the trouble. You can start to look at individual trips and how lazy they are: 0.7 miles for a single non-shared ride.
