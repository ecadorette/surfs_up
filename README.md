# surfs_up
Module9

## Overview
The purpose of this analysis is to analyze weather data for Hawaii to determine if a surf and ice cream shop would have enough sales to stay open year round.

## Analysis
Using `Python`,`Pandas`, and `SQAlchemy` the data was filtered to June and December to compare the daily temperatures.

June summary:
![June_temps](https://user-images.githubusercontent.com/114450503/224556633-550371c6-ec33-403b-8bb9-cd29d520911d.png)

December summary:
![Dec_temps](https://user-images.githubusercontent.com/114450503/224556717-7150e1e0-4f4e-45cd-8074-c6f575413c5a.png)

## Results
- Average temperatures between June and December only differ 4 degrees. This suggests sales in December may be roughly the same as sales in June.

- The minimum temperature captured in December was 56 degrees, compared to 64 degrees in June. While average temperatures may be very similar the temperature between months can still be different, it will still be colder in December than in June. 

- It's worth noting that the number of recorded temperatures vary between months, with the December dataset having 183 less recorded temperatures than June. This has potential of skewing the data to make December seem warmer than it is.

## Summary
If it was my decision to determine what sales would look like in December versus June after looking at this analysis, I would go back to the drawing board for more data. I would recommend weather data be pulled for several years to get a better picture of temperatures overall. I would also look into other factors like water temperature, wave/temperature preferences for surfers, and when tourists are most likely to visit. A strategic approach may be to have the shop be open for both surf equipment and ice cream during the summer, and maybe just surf equipment in the coldest months. 
