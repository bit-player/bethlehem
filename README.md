# bethlehem
2019 holiday card data

This repository provides data on white Christmases in Bethlehem, Pennsylvania. The data formed the basis of a holiday card prepared for 2019.

![2019 holiday card](Christmas-card-2019-v2.png)

The point of the project was to look at weather data for the Christmas season at one location, over several decades, to see if any climatic trends might be visible. The chosen place was Bethlehem, Pennsylvania, where the average temperature at this time of year is reasonably close to the freezing point. Thus a small change in temperature might conceivably have a noticeable effect on whether precipitation falls as rain or snow.

We draw no firm conclusions about the outcome, beyond the observations noted in the text on the back of the card.

The weather data were downloaded from the [National Centers for Environmental Information](https://www.ncdc.noaa.gov/cdo-web/), a service of NOAA, the National Oceanic and Atmospheric Administration. Specifically, the data come from the Global Historical Climatology Network – Daily database.

We downloaded the files through a web form interface. This is *not* the best way to go about it. I discovered only too late that NOAA offers an [API](https://www.ncei.noaa.gov/support/access-data-service-api-user-documentation) for programmatic access, as well as single files with the complete record of daily observations from a specific weather station.

The station we consulted is designated USW00014737; it is located at Allentown Lehigh Valley International Airport, about three miles northwest of downtown Bethlehem. Observations are available from 1948 to the present.

From the raw data files we extracted readings for the last six and the first six days of each year, or in other words December 25 through January 6 of the following year. The three variables of interest for each day were average temperature, total snowfall (measured from midnight to midnight) and snow depth on the ground (measured at 7 a.m. each day).

The tableau of year-by-year icons reduces the numerical data to binary variables. The background color indicates whether the average temperature over the 12 days was at or below 32 degrees Fahrenheit *(blue)* or above 32 *(red)*. Snowflakes indicate that measureable snow was recorded on at least one day during the period. Similarly, a white tree signifies that nonzero snow depth was recorded on at least one day.

## Data Limitations

The data set appears to be nearly complete, but it's not perfect. Throughout much of the 70-year period the field for average daily temperature is blank. We therefore substituted the average of the daily high and low temperatures (and did this consistently even when a reported average was present). More troubling, for a few years measuements of snow depth were apparently made only sporadically. Thus for four years (1997, 2002, 2004, and 2005) we estimated the snow depth from snowfall totals.




