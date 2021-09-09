# Location-to-open-a-Cafe-in-Sydney-Australia-
Using K-Means Clustering to find the best location to open a new Cafe. 

- Acknowledgements : 
Category:Suburbs of Sydney 
https://en.wikipedia.org/wiki/Category:Suburbs_of_Sydney

Foursquare
https://foursquare.com/city-guide

Applied Data Science Capstone


- Business Understanding :

The main goal of this project is to collect and analyze data in order to select a location in Sydney to open a Cafeteria. 
We want to help a business owner planning to open up a Cafe in a location by exploring better facilities around the Suburb.


- Analytical Approach:

This is an unsupervised machine learning problem where we need to group together suburbs having similar facilities. 
We can use K Means Clustering to solve this problem.


- Data Understanding :

The Wikipedia page contains a list of suburbs in Melbourne. There are 329 suburbs in Sydney,Australia which I extracted using a web scraping technique with the help of Python BeautifulSoup and Request packages.
the geographical coordinates such as latitude and longitude of each suburb were collected using Python’s Geocoder package.
Then, Foursquare API was used to extract details about the various venues present in each suburb.
Once, the location data was extracted by using Geocoder, I used the Folium package to visualize the data on a map. This ensured us that the data we retrieved was correct. Foursquare API was used to obtain the top 100 venues within a radius of 2000 meters.

- Data Requirements:
We would need a list of suburbs, the location of each suburb, and how many cafes are present in the suburb.

- Data Collection:

- List of Suburbs in Sydney, Australia which I have extracted from: https://en.wikipedia.org/wiki/Category:Suburbs_of_Sydney
- Latitude & Longitude of all the suburbs using Geocoder
- venues in each suburb from foursquare API https://foursquare.com/





