# Hawaii Weather Analysis using SQLite & SQLAlchemy
## Overview
Analyze weather data from the Hawaiian island of Oahu during June and December to determine the viability and longevity of a year-round surf and ice cream business on the island.

## Results
![DecemberTemps.png](/Analysis/DecemberTemps.png)
![JuneTemps.png](/Analysis/JuneTemps.png)
- Based on the available temperature data, a Surf & Ice Cream business would likely be a profitable venture for most of the year. While the winter months could see a drop in ice cream sales due to tourists’ association of ice cream to summer months, the average December temperature is still **71.0°** which is still warm compared to most of the United States during December. 
- The most recent data available in the SQLite database is from 2016. More recent temperature data could give us a more accurate picture of *current* viability during a year. 
- Since precipitation is excluded from this analysis, I feel the examination of temperature data to be only one piece of the puzzle. Were investors asked to decide on funding given only temperature data, that analysis could not sufficiently inform.

## Summary
In summary, a Surf & Ice Cream Shop is a perfect combination for the island of Oahu. Surfing in the late fall and winter months see some of the island’s biggest waves (along with big surfing competitions held on the island), and the warm weather in the summer months will draw crowds looking to beat the heat.
###### **Additional Queries**
- Adding summary statistics for precipitation data during the months of June and December would provide a deeper analysis of the shop’s viability to operate year-round.
- Diving deeper into the locations of the weather stations and focusing on their latitudes, longitudes, and elevations could help to select the weather data during June and December that would be most relevant to choosing a location for the flagship of the Surf & Ice Cream brand by excluding data that isn’t (i.e., any station located far from a beach or in the mountains, where temperatures are bound to be cooler no matter the time of year).
