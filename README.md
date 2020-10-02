# Tableau-for-the-Citi-
Webscraping and data cleaning using Python libraries: Splinter and Urllib.
Visualization with Tableau.

[Link to Tableau Public](https://public.tableau.com/profile/cerejarosinha#!/vizhome/Citibike-in_the_City/Dashboard1?publish=yes)

### This interactive map allows the user to interact with Citi Bike activity for the last month of 2018.

Some obervations:

* The visualizations highlight that men and subscribers far outweigh the alternative in regular use.

* Very few bikes were returned on New Years Eve. 

* Is celebratory biking on the rise, or did people fail to return them?

* Popular start stations and ending stations are not the same.

* The majority of the activity seems to take place in redevelopment and commercial areas of lower Manhattan, Brooklyn near the bridges and Long Island City, Queens.

* The most popular starting times seem to mimic a 9-5 work schedule. It's not conclusive for several reasons, the most obvious being that I did not pull weekends out of the data. Perhaps if I did, the peaks would have been more extreme.

This is a simple project illustrating the how multiple modalities can combine to grab, clean and visualize data.  In this case, I used information readily available from NY State for the collaboration with Citibank to provide bike rentals throughout the Greater Manhattan area. The analysis itself is not particularly complicated. With more time, I would have included a larger database and calculations for forecasting methods.
# Screenshots:

```
from bs4 import BeautifulSoup
import pandas as pd
from selenium import webdriver
from io import BytesIO
from zipfile import ZipFile
from urllib.request import urlopen
import os
import csv
from datetime import datetime
```

## Dashboard
<a href="url"><img src="https://github.com/sherirosalia/tableau-for-the-city/blob/master/images/Dashboard.png" align="center"></a>

## Nonsubscribers vs Subscribers
<a href="url"><img src="https://github.com/sherirosalia/tableau-for-the-city/blob/master/images/Customers.png" align="center"></a>

## Ride Map
<a href="url"><img src="https://github.com/sherirosalia/tableau-for-the-city/blob/master/images/RideMap.png" align="center"></a>

## Starting Times
<a href="url"><img src="https://github.com/sherirosalia/tableau-for-the-city/blob/master/images/StartTimes.png" align="center"></a>

## Top Pick Up Stations
<a href="url"><img src="https://github.com/sherirosalia/tableau-for-the-city/blob/master/images/StartStations.png" align="center"></a>

## Top Drop Off Stations
<a href="url"><img src="https://github.com/sherirosalia/tableau-for-the-city/blob/master/images/EndStations.png" align="center"></a>

## New Years Eve
<a href="url"><img src="https://github.com/sherirosalia/tableau-for-the-city/blob/master/images/31.png" align="center"></a>
