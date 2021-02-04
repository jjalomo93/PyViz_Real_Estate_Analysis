# San Francisco Real Estate Analysis

![San Francisco Park Reading](Images/san-francisco-park-reading.jpg)

*[San Francisco Park Reading by Juan Salamanca](https://www.pexels.com/photo/park-san-francisco-reading-61109/) | [Free License](https://www.pexels.com/photo-license/)*

## Background

Based on information from 2010-2016, I have created a dashboard to provide various analysis on the San Francisco real estate market. Analysis includes: average price per square foot, average gross rent, average housing units sold per year, and most expensive locations. All of this analysis is done for San Francisco as a whole and is broken out by neighborhood.

## Dashboard

The dashboard created is broken into five tabs:
* Welcome: This tab uses MapBox API to plot the neighborhoods of San Francisco alongside their average housing prices
* Yearly Analysis: This tab uses 2010-2016 data to show yearly averages for housing units sold per year, average sales price by square foot per year, and average gross rent per year. These are visualized with HvPlot.
* Neighborhood Analysis: This tab breaks down average pricing data (price per sqft and gross rent) by neighborhood and also shows the top 10 most expensive neighborhoods in San Francisco. Lastly, there is a plot that shows a direct comparison between average gross rent and average sales price per sqft. These are visualized with HvPlot.
* Parallel Plots Analysis: This tab shows parallel coordinates and categories plots that shows the comparison between gross rent, sales price per sqft, housing units sold, and each neighborhood of San Francisco.
* Sunburst Plot Analysis: The last tab of the dashboard shows a sunburst plot that shows the breakdown of prices for the top 10 most expensive neighborhoods by year.