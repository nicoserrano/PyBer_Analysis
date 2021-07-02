# PyBer_Analysis

#### Analysis on ridesharing data using Pandas, NumPy, and Matplotlib Libraries. 

## Overview of the Analysis
In this project I will be working with ridesharing data from different cities located in urban, suburban, and rural areas. The goal will be to produce a complete analysis with visualizations in order to help PyBer improve access to ridesharing services and determine affordability for underserved neighborhoods. 

## Resources
- Data sources:
  - city_data.csv
  - ride_data.csv

- Software:
  - Python 3.6.1
  - Jupyter Notebook
  - Pandas, NumPy, Matplotlib, and SciPy Libraries 

## Results

Ridesharing services are priced based on supply and demand. Clearly, there are more rides and drivers in urban cities as there are usually more people concentrated in the big cities. Then come suburban cities in second place and rural in last place. 

<img width="591" alt="Pyber_Summary" src="https://user-images.githubusercontent.com/83378141/121763010-f83e3200-cb06-11eb-9efd-83f0e7aae028.png">

![Fig1](https://user-images.githubusercontent.com/83378141/121763934-c11f4f00-cb0d-11eb-8da2-39c8f9ba9bbd.png)

This bubble plot shows how even though rural areas have less rides, their fares are relatively more expensive. Also, there are less drivers available in this type of cities as bubbles are smaller. Suburban cities are in the midpoint between the other two. Their fares are average price and their number of rides range in between 10 to 25 rides per city. Again, with somewhat more drivers available than rural areas but less than urban. And lastly, urban cities happen to have lower fare prices but a lot more rides.

![Fig6](https://user-images.githubusercontent.com/83378141/121764252-98e51f80-cb10-11eb-81db-c5478efee6b8.png) 
![Fig2](https://user-images.githubusercontent.com/83378141/121764606-3b9e9d80-cb13-11eb-98c0-82807bccbb93.png)

Almost 69% of the rides, and therefore the market, come from urban areas. And only 5% from rural. Also, as it can be seen in the box plot the average number of rides for urban areas was 3 times more than in rural. The maximum number of rides in rural areas was the minimum number of rides from urban. PyBer is considerably more present in the these big cities. 

![Fig7](https://user-images.githubusercontent.com/83378141/121764390-81f2fd00-cb11-11eb-8516-fcc05ffcbcf8.png)
![Fig4](https://user-images.githubusercontent.com/83378141/121764626-638e0100-cb13-11eb-92b4-5f6ca17ba333.png)

Urban areas also happen to have the majority of the drivers and rural the minority. Urban areas have 8 times more drivers than rural. The presence of drivers in the suburban areas is also not as large as urban. There is clear imbalance in driver distribution across city types. 

![Fig5](https://user-images.githubusercontent.com/83378141/121763621-90d6b100-cb0b-11eb-8f91-30ce108735b0.png)
![Fig3](https://user-images.githubusercontent.com/83378141/121764647-85878380-cb13-11eb-88c6-17eabc57602f.png)

As for fares, urban areas have the majority with a 63%. Suburban and rural still have a relatively big part of the whole as their fares are more expensive. This can be seen in the box plot as rural areas happen to have a higher overall distribution of fare prices. Nevertheless, their ranges happen to be quite similar. 

![Fares_by_City_Type](https://user-images.githubusercontent.com/83378141/122076186-a75d6080-cdc8-11eb-8085-8545e66a3c1e.png)

And last but not least, the multi-line graph that shows the weekly fares for all three city types from January 2019 to April of the same year. The graph shows that the sum of fares for urban cities was more than $1800 which is more than 3 times the max value for the rural cities. The sum of fares for suburban cities was less than $1500 throughout. Even though we concluded that the fares were more expensive in rural areas, this graph still happens to address that urban sum of fares was relatively a lot higher. This because the sum of fares accounts for all the rides made during that time, which we also concluded that urban cities had a lot more drivers and rides made. 

## Summary

In conclusion, some recommendations that could be made to PyBer are as follows:

- In order to increase market presence in suburban and rural areas, PyBer needs to contract more drivers. As it can be seen in the *driver count box plot*, the spread for rural drivers count is very small in comparison to the other two. There are no more than 10 drivers in the a rural city. The first recommendation would be to create incentives for drivers in these areas that can bring that count up. Assuming there is enough demand and the utilization rate for these current drivers is very high, having more drivers would increase revenue by a lot as fares are very highly priced in rural cities.
- Likewise, the second recommendation would consist on creating the same incentives but for suburban cities as their driver and ride count is still opaqued by urban. Again, this would significantly increase revenue as fares are higher in suburban cities and having more rides would maximize profit.
- And lastly, I would recommend to decrease the driver count in urban cities by a small amount as they account for almost 81% of the total PyBer drivers. It is important that we balance that percentage so that there are more drivers in the other areas, specially rural. By doing this, we would also bring the average fare price in urban areas higher as there might be less supply to cover for that large demand. Again, this would have to be a small change for the system not to collapse for not enough PyBers in urban cities. 





