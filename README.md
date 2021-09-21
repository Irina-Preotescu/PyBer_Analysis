# PyBer_Analysis
## Overview of the Analysis
This project required an exploratory analysis of rideshare data in order to help improve access to rideshare services, as well as assess adisparities in the ride-sharing data among the city types. I created visualizations using the data provided in order to better convey the findings of the analysis.


### Resources
Python, Pandas, Jupyter Notebook, and Matplot.


## Results
The PyBer Summary DataFrame provides a comparison of the ridesharing services in the 3 types of cities included in this project: rural, surburban, and urban cities. Upon close examination, clear evidence was found for a much larger demand for PyBer in urban cities than in suburban and rural cities combined.

Over the span of 4 months, from January 2019 up until May 2019, data shows that 1,625 rides were recorded in urban cities, 625 in suburban cities, and 125 in rural cities. This means that 68.4% of the total PyBer rides took place in urban cities, 26.3% of rides were in suburban cities, and only 5.3% of rides were in rural cities. The piechart below illustrates these results.

![Fig6](https://github.com/Irina-Preotescu/PyBer_Analysis/blob/4f4e28e07a9173592eac81fe74a0214a37c7ea85/Fig6.png)

Considering this finding, we can expect to see similar trends when inspecting other metrics and criteria for the PyBer rideshare data. When looking at the number of PyBer drivers in each city type, we can, indeed, see a similar pattern, as shown in the figure below. Data shows that there were 2,405 (81%) drivers in urban cities, 490 (16%) drivers in suburban cities, and only 78 (3%) drivers in rural cities.

![Fig7](https://github.com/Irina-Preotescu/PyBer_Analysis/blob/4f4e28e07a9173592eac81fe74a0214a37c7ea85/Fig7.png)

Consequently, the fare shares follow a similar pattern, where urban rides accumulated a total of $39,854.38 in fares, suburban rides a total of $19,356.33, and rural rides a total of $4,327.93. As illustrated in the figure below, this means that out of the total fares for PyBer, 62.7% were from urban cities, 30.5% were from suburban cities, while the rest of 6.8% were from rural cities.

![Fig5](https://github.com/Irina-Preotescu/PyBer_Analysis/blob/47187f0a5c8b375c63c269829303ea46d4a53de4/Fig5.png)

Regarding the cost of rides, the average fare per ride in urban cities was $24.52, while the average fare for rural rides was $34.62, resulting in a considerable discrepancy in price. Suburban rides cost an average of $30.97. Considering that rural areas are more difficult to access, this indicates thare there might be room for improvement when it comes to affordability for rural citizens. The figure below portrays this difference, as well as that between the average fare per driver. Urban drivers obtain an average of $16.57, suburban drivers obtain an average of $39.50, and rural drivers obtain an average of $55.49.

![Fig8](https://github.com/Irina-Preotescu/PyBer_Analysis/blob/5f526744273d500031448845d90a00ac87f26c77/Fig8.png)

By incorporating the multiple-line chart "Total Fare by City Type", we can observe these trends throughout the 4 weeks that were included in the analysis.

![PyBer_fare_summary.png](https://github.com/Irina-Preotescu/PyBer_Analysis/blob/b21da8e4f9643a3754bbee2c424e9680b6defd76/PyBer_fare_summary.png)

A few aspects can be noticed at a first glance:
* There is a significant spike in fares towards the end of February for all city types.
* Urban ride fares experience the greatest fluctuation in price during March, while suburban and rural ride fares experience a more steady flow, with only a slight increase mid-month for suburban rides and a considerable spike for rural rides at the end of the month.
* Both urban and suburban fares are at their peak at the end of February, while rural fares reach their peak at the end of March.

## Summary
Based on these findings, here are 3 business recommendations for addressing some of the disparities among the city types.
1. In order to improve accessibility to PyBer rideshare services in rural cities, PyBer should implement a cheaper option of travel, such as a minibus or bicycle-sharing services. This might help lower the high price of car rides, while providing a cheaper solution to travel in rural areas, which are known to be less dense and harder to access.
2. In order to bridge the gap between fare averages per driver and help urban drivers gain money that is more proportional to the amount of urban rides, PyBer can offer commissions for drivers that reach a certain amount of rides per week. An added commission on top of the money they gain from their original number of rides will help maintain the supply of drivers and prevent them from quittig due to low fares in urban cities.
3. Implement further analysis of other potential factors involved in the high disparity between prices in the rural and urban cities. This will allow PyBer to further detect problems and consequentally develop apprpriate solutions. 
