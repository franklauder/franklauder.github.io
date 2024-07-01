---
title: 'New York Energy Efficiency Dashboard Project'
#subtitle: 'This is a demo'
date: 2024-02-04 00:00:00
featured_image: '/images/energyDasboard/hex_plot.jpg'
excerpt: 'This Dashboard utilizes interactive chlorapeth maps in addition to interactive tables to aid in the analyis of theb New York Energy Efficiency program'
---

![](/images/energyDasboard/tile_plot.jpg)

#![](images/flights/flight5.jpg)


This dashboard project utilizes the Residential Home Energy Efficiency dataset, which encompasses various data points offering valuable insights into residential energy efficiency projects conducted in New York State between 2007 and 2012.

The Residential Existing Homes Program, a market transformation initiative, employs Building Performance Institute (BPI) Goldstar contractors to implement comprehensive energy-efficient improvements. The program employs building science and a holistic approach to decrease energy consumption in the state's existing one-to-four family and low-rise multifamily residential buildings, capturing savings in heating fuel and electricity. Income-based incentives, including an assisted subsidy for households with incomes up to 80% of the State or Median County Income (whichever is higher), are provided by the program. These incentives support the installation of eligible energy efficiency improvements such as building shell measures, high-efficiency heating and cooling measures, ENERGY STAR appliances, and lighting. The dataset backcasts estimated modeled savings for a subset of completed projects against normalized savings calculated by an open-source energy efficiency meter.

The dataset is hosted on the State of New York's open data platform and can be accessed [here](https://data.ny.gov/).

I selected this dataset due to its ability to incorporate U.S. Census data and geospatial analysis, enhancing the depth of the analysis. Integrating data and interactivity into the dashboard equips users with additional tools to gain insights.
The tidycensus and tigris packages were employed to obtain data and New York State shapefiles from the U.S. Census. The leaflet package was utilized to develop interactive choropleth maps, while the DT package was employed to create interactive tables.
The final web application was created using the Shiny and Shiny Dashboard packages.

The project can be accessed via the below link.

<a href="https://lauderf20.shinyapps.io/nyDashboard/" class="button button--large">New York Energy Dashboard Project</a>

<br></br>

In addition, I've created a smaller scale dashboard with Tableau using only energy and census data at the  county level.  The Tableau Public link can be accessed via the below link.

<a href="https://public.tableau.com/views/NewYorkEnergyEfficiencyMonitoring/NYEnergyEfficiencyDashboard?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link" class="button button--large">New York Energy Tableau Dashboard </a>
