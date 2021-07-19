# **PyBer_Analysis**

## Overview of the PyBer analysis: 

The project aimed to perform exploratory analysis and deliver a series of visualization materials to help improve PyBer (transportation) services in underserved neighborhoods. The results will serve as a baseline to allocate resources strategically for future campaigns. For the outcomes of this project we prepared the following deliverables you can find here [Pyber_First_Analysis](https://github.com/chocoplace/PyBer_Analysis/blob/main/PyBer.ipynb): 
- Import your data into a Pandas DataFrame.
- Merge your DataFrames.
- Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.
- Determine the mean, median, and mode for the following:
  - The total number of rides for each city type.
  - The average fares for each city type.
  - The total number of drivers for each city type.
- Create box-and-whisker plots that visualize each of the following to determine if there are any outliers:
  - The number of rides for each city type.
  - The fares for each city type.
  - The number of drivers for each city type.
- Create a pie chart that visualizes each of the following data for each city type:
  - The percent of total fares.
  - The percent of total rides.
  - The percent of total drivers.

### Resources

Data Source:
- [City_data](https://github.com/chocoplace/PyBer_Analysis/blob/main/Resources/city_data.csv).
- [Ride_data](https://github.com/chocoplace/PyBer_Analysis/blob/main/Resources/ride_data.csv).
- [PyBer_ride_data](https://github.com/chocoplace/PyBer_Analysis/blob/main/Resources/PyBer_ride_data.csv).

Software: Python 3.7.6, Anaconda 4.10.3, Pandas, Jupyter Notebook 6.3.0, and Matplotlib. 

### Results:

Adding to the first PyBer analysis, we were tasked with providing two new deliverables to enhance the general results, the code can access here [Pyber_Challenge](https://github.com/chocoplace/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb): 
- Deliverable 1: A ride-sharing summary DataFrame by city type 
  - Provide total number of rides for each city type: Rural 125 | Suburban 625 | Urban 1,625. Rural cities reported 13 times less rides than Urban cities. 
  - Provide  total number of drivers for each city type: Rural 78 | Suburban 490 | Urban 2,405. Rural cities reported having 30.83 time less drivers than Urban cities. 
  - Determine the sum of the fares for each city: Rural $4,327.93 | Suburban $19,356.33 | Urban $39,854.38. Even so Urban cities reported a greater revenue, Rural cities reported a bigger income in relation with drivers/fare per city. 
  - Determine the average fare per ride for each city type: Rural $34.62 | Suburban $30.97 | Urban $24.52. Rural cities reported a greater average fare per ride in comparison with Urban and Subuerban cities.  
  - Determine the average fare per driver for each city type: Rural $55.48 | Suburban $39.50 | Urban $16.57. Rural cities reported a greater average fare per driver in comparison with Urban and Subuerban cities.  
  - Create and format A PyBer summary DataFrame:
      
    ![Fig.1](https://github.com/chocoplace/PyBer_Analysis/blob/main/analysis/D1.%20PyBer%20Summary%20DataFrame%201.png)
  
    ![Fig.2](https://github.com/chocoplace/PyBer_Analysis/blob/main/analysis/D1.%20PyBer%20Summary%20DataFrame%202.png)
    
  - Final deliverable 1: 
  
    ![Fig.3](https://github.com/chocoplace/PyBer_Analysis/blob/main/analysis/D1.%20PyBer%20Summary%20DataFrame%203.png)


- Deliverable 2: A multiple-line chart of total fares for each city type. 

  - The following  multiple-line graph was created by using Pandas technical skills and two new functions, pivot() andresample(), shows the total fares for each week by city type. From the graph we can highlith the disparities between the different cities and the same time shows they follow the same trend for example the weeks around late Feb and early March:

![PBer_fare_summary](https://github.com/chocoplace/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

### Summary:

The results of this analysis will provide a baseline for our PyBer client to strategize on how to allocate resources and areas of opportunity for growth, for example: 

  1. From data we can determine the market in Urban cities is very competitive for drivers, we can see there is a total of 1,625 total rides per 2,405 drivers, resulting in less than 1 ride per driver. While Suburban cities fluctuate around 1.27 rides per driver and Rural cities are around 1.60 rides per driver. 

  2. Data shows a disparity of earnings between drivers based on city type. Drivers in Urban cities are making three times less than Rural drivers and two times less than Suburban riders. This shows the need to design a targeted program to create equality between the different city drivers. 

  3. The data also shows an important disparity in the number of total rides between cities. It would be important to identify the reasons behind it, for example in Rural cities reported 125 rides vs 1,625 in Urban cities, is this a relation to price or the market needs (less need for riders?)?. This could be an area of opportunity to target campaigns, if it is fees, maybe PyBer can offer a price decrease and if it is because of the market need, a marketing campaign can be designed to boost the rides. 

End

