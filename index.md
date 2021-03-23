# Fayette County and Jefferson County Electric Bill Visualizations
### *By Andrew Bakert*

## Purpose and Data Source
In order to get a better idea of how different electricity price and tariff changes impact people in Kentucky's two largest cities, Louisville and Lexington, I created several visualizations that conveyed the impact across several dimentions, including tenant status, income level as a percent of county median income, and year that the building was built. My data came from the [NREL LEAD database](https://openei.org/doe-opendata/dataset/celica-data), which was compiled using data from 2018. The methodology for creating the dataset can be seen [here](https://www.nrel.gov/docs/fy19osti/74249.pdf). An HTML rendering of the Jupyter Notebook used to create these visualizations is available [here](ky_electricity.html). The full GitHub repository is available [here](https://github.com/BakerTWashington/BakerTWashington.github.io/).

## Percent of Income Spent on Electricity Bill in Jefferson County
The [first visualization](louisville.html) created was illustating the percent of household income spent on electricity by census tract in Jefferson County. The base map shows this data shaded from orange to red by percent spent. There is a tooltip that is shown when hovering over one of the markers, which are placed at the centroid of each tract. This tooltip gives the average household income for the tract and the average percent of household income spent on electricity. Finally, when clicking on one of the markers a bar graph appears unique to each tract which gives the percent spent on electricity by income level as a percent of the county's median household income and the tenant status of the household.

## Percent of Income Spent on Electricity Bill in Fayette County
The [second visualization](fayette.html) performs the same analysis for Fayette County as was performed by the previous visualization.

## Increase in Percent of Income Spent on Electricity Bill in Fayette County
The [third visualization](fayette_diff.html) examines the effect of the proposed Kentucky Utility (KU) rate increase. KU serves Fayette County, so the rate increase anlysis is performed for that area. The specific rates are shown in the [HTML version of the Jupyter Notebook](ky_electricity.html). The format is similar to that of the first two visualizations. However, in this case the increase in percent spent on electricity is visualized.

## Increase in Annual Electricity Bill in Fayette County
The [fourth visualization](fayette_elep.html) shows the increase in annual electricity bills by tract in Fayette County. In this case the tooltip shows the average increase in annual electricity bill by tract. The popup bar graph breaks down bill increase by income level as a percent of county median income and the year range in which the building was built.
