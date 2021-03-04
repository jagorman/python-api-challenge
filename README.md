

Does the distance to the equator affect the climate of a region?
 In this repository, I 
randomly select over 500 unique cities based on their latitude and longitude measurements, check the weather in each city using API, and compare


# python-api-challenge

##Weather

In this challenge, I ask a simple question.
 "Does a city's latitude and longitude play a part in its weather?" 

To try to find the answer I analyze over 500 cities around the world, based on their latitude and longitude measurements. I then plot charts showing linears regression by hemisphere. All data is saved in a csv file, and in images

## Vacation

Now for the real fun! Who doesn't love plotting the ideal vacation?

To do this, I use gmaps and Google Places API. 

Pulling from the csv file created in Weather, I first create a map showing humidity in every city. I narrow down the parameters based on what my ideal weather type, and create a data frame. From there I use Google API to find one
hotel for every city on my list.

From there, I place the map markers over the existing humidity map
