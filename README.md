# PyBer_Analysis
## Overview of the PyBer analysis

This report presents the results of combining two databases. By using Python within the Jupyter Notebook and Matplotlib, it was possible to create data frames and plots that allowed us to understand the relationship between fares, riders, and city type through time. 

### Files 

Code: PyBer_Challenge.ipynb

Resources Folder: city_data.csv, ride_data.csv, Images

Analysis Folder: FigChallenge.png

Analysis: PyBer_Challenge_Report.md

## Results

A cyber data summary, the explanation of a pivot by data and city type, and a plot will be covered within the next paragraphs.

### The PyBer Data Summary

The next image shows information about the Total Rides, Total Drivers, Total Fare, Average Fare per Ride, and Average Fare per Driver in each city type. In this summary, we can see that the urban city type has more amount of total rides and at the same time it has the lowest average fare per ride and per driver. On the other side, the rural city type has fewer total rides and drivers, and with this comes a higher average fare per ride and per driver. 

![Pybersummary](https://github.com/DylanMontemayor/PyBer_Analysis/blob/main/Resources/Images/Pybersummary.png)

### Pivot by date and city type

After reshaping the data, we ended with a pivot in which we added the date as an index and each column has the average fare per city type through the time. 

![Pyberpivot](https://github.com/DylanMontemayor/PyBer_Analysis/blob/main/Resources/Images/Pyberpivot.png)

### Total Fare by city type plot

The next plot summarizes the pivot mentioned before. The x-axis shows the date per month and the y-axis shows the average fare in USD. In this plot, we can see clearly the difference in the average fare per city type. The importance of representing data in plots is that we can detect in seconds the data behavior and seasonality, which is very useful in forecasting. 

![Pyberplot](https://github.com/DylanMontemayor/PyBer_Analysis/blob/main/Resources/Images/Pyberplot.png)

## Summary

Fares are pretty different per city type. The highlight of this report is that with more drivers and demand, the average fares tend to be lower, and with fewer drivers and demand, the average fares tend to be higher. In order to talk more about seasonality we probably need a whole year or even more than one year to be able to compare the data. 
