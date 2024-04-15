# Cyclistic

Cyclistic is a bike-share company based in New York City.

## Project Background
Cyclistic has partnered with the city of New York to provide shared bikes. There are bike stations located throughout Manhattan and neighboring boroughs. Customers are able to rent bikes for easy travel between stations at these locations. Cyclistic’s Customer Growth Team wants to understand how their customers are using their bikes; their top priority is identifying customer demand at different station locations.

## Datasets
- [NYC Citi Bike Trips](https://console.cloud.google.com/marketplace/details/city-of-new-york/nyc-citi-bike)
- [Census Bureau US Boundaries](https://console.cloud.google.com/marketplace/product/united-states-census-bureau/us-geographic-boundaries)
- [GSOD from the National Oceanic and Atmospheric Administration](https://console.cloud.google.com/marketplace/details/noaa-public/gsod)
- [Zip Code Spreadsheet](https://github.com/syedtahahmed/Cyclistic-Project/blob/main/2-%20NYC_zip_codes.csv)

## Data Prep
Combined data from the tables received for this project into one reporting table which will be used to develop a dashboard. Used programs like BigQuery and Dataflow to move and analyze data with SQL.

## Tableau Dashboard
- [Link to the Tableau Dashboard](https://public.tableau.com/views/CyclisticProject_17130960119370/CyclisticExemplar?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

### Summer Trends
The first tab of the dashboard is a map of seasonal trends of bike trips in each of the New York boroughs. The largest map shows each of the boroughs. The table compares the number of trips and average trip duration for customers and subscribers in each neighborhood. Three smaller maps focus on July, August, and September: the three months with the highest bike traffic.

### Seasonality
The second tab of the dashboard focuses on seasonality, or trends throughout the year, with the Trip Totals chart and the Trip Counts by Starting Neighborhood table.

#### Trip Totals Chart
The Trip Totals chart visualizes the total number of bike trips taken throughout 2019 and 2020, with a distinction between customers and subscribers. This chart shows that subscribers make up a significantly larger portion of Cyclistic’s users than regular customers. It also shows that there are far more users in warmer months (May–October) than there are in colder months. This makes sense considering that people are less likely to ride bicycles in colder weather.

#### Trip Counts by Starting Neighborhood Table
The Trip Counts by Starting Neighborhood table lists the total number of bike trips started in each neighborhood in each month of 2019 and 2020. It is organized by zip code, borough, and neighborhood. It also uses a color gradient to emphasize the highest and lowest counts of monthly trips. The greater the number of trips, the darker the value is in the table. It also uses light text on the darker values to ensure that the table is readable and accessible. Because the starting location is more indicative of where users look for a bike, it is more important to emphasize starting location when determining where to advertise. The most active stations are in the Lower East Side and the Chelsea and Clinton neighborhoods. The most active months are from May to October.

### Top Trips
The third and final tab of the dashboard is a comparison of the total number of trip minutes by starting neighborhood and ending neighborhood for both customers and subscribers. The two charts are horizontal stacked bar graphs that are ordered from highest to lowest number of minutes (between customers and subscribers combined). These charts lend insight into which locations users are most willing to travel long distances to. The charts show that the Lower East Side and Chelsea and Clinton neighborhoods have the highest total trip minutes for both start and end stations.
