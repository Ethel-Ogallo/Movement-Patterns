# Movement-Patterns
An analysis of the movement of  passengers/tourists around the world.  
### Introduction
This analysis seeks to answer: __"What are the main movement patterns of incoming and outgoing passengers around the world between 1995 and 2019?"__.The two years were chosen based on the data available and would be able to show a trend on the movement patterns. This is an analysis  on the incoming arrival, departures of tourists and also the top 100 busiest airports in the world.   
The following hypothesis are form a preview of the data:  
1. The busiest airports/countries is United states and china and this might be due to a large number of airports in the top 100 list.  
2. The most busiest countries/airports receive the highest number of incoming arrivals as well as the highest number of outgoing departures.  
3. High income economies should record a high number of incoming arrivals and departures as they have the income to travel often compared to lower income economies.  
4. The regions of the world may vary in number of arrivals and departures but based on the busiest airports and countries and economies, North America and Asia might receive a high number of arrivals and departure.  

### Analysis  
Data was sourced from open source Kaggle: https://www.kaggle.com/datasets/batrosjamali/top-100-airports-of-the-world  and from the world bank data bank  https://data.worldbank.org/indicator/ST.INT.ARVL .The data was analyzed using SQL in Google Bigquery.  

### Conclusion
1. The busiest airport is in United states; Hartsfield-Jackson Atlanta International Airport . When grouped by country the United States records the highest number of passengers handled followed by China and this can be attributed to the fact that they have the highest number of airports in the top 100 most busiest airports with 25 and 16 airports respectively. The rest of the countries record 4 total airports and below.  
2. The busiest airports by country also prove to be recording a high number of incoming passengers and outgoing passengers. The top rank varies in comparison from 1995 and 2019. In 1995 Mexico registered the highest number of arrivals and departures but in 2019 it is the US with china closely behind it. Departures in 1995 the top rank is Mexico still with US ranking top in 2019.This also shows a high correlation with number of departures and umber of arrivals.  
3. High income economies do record a high amount of arriving passengers and increasing by year however lower middle income economies record a higher level of arrivals compared to upper middle income economies. This could be because people from higher income areas are more prone to visit lower income areas as these tend to be areas such as the Caribbean which have a tropical climate.  
4. The region Europe and Central Asia records the highest number of incoming passengers in both 1995 and 2006 with North America ranking fourth. This could be because of  most of the countries n the region being in the European Union which allows members to travel freely within. Despite lacking data fro 1995 for Europe, in 2019 it still recorded the highest number of departures, however based on the number of arrivals in 2019 and the numbers positively correlating it safe to assume it also recorded the highest number of departures in 1995.There was missing data for Sub Sahara Africa for both 1995 and 2019.  
