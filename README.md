Summary
-------
 
This visualization presents flights canceled due to weather conditions in the United States in the year 2008 by month. The objective is to show the variation in the number of canceled flights per month and which airports are most affected by climate phenomena.

Design
------
I chose to use Albers projection of USA Because it best represents the map of the USA and its territories. For the flights I chose to represent them with a line between the airport of origin and destination. In the initial version the airports of origin and destination had no additional representation. After receiving the feedback I added circles to represent the airport of origin of the flights. I chose the lightblue to color the map and the dodgerblue to the circles of the origin airports because they are soft colors. Because of the large amount of data I decided to use opacity in the design of the lines to be able to identify the regions with the highest concentration of flights. After second feedback I decreased the opacity of lines from 0.1 to 0.035.

The visualization begins with an animation that shows the flights canceled per month sequentially. Afterwards, the user can interact with the visualization by selecting the month of their interest.



Feedback
--------

1- Nice work! I would like to be able to differentiate the airport of origin and destination to better understand where there are more canceled flights.
2- I think you could increase the transparency of the lines to better identify the number of flights canceled mainly in the months with more occurrences.
3- Good job! I was able to identify the months and regions of the US with the highest number of occurrences of canceled flights.

Resources
---------

* GeoJSON USA Map: https://github.com/johan/world.geo.json/tree/master/countries
* 2008 flights data: http://stat-computing.org/dataexpo/2009/the-data.html
* Tutorial do create map using D3: https://bost.ocks.org/mike/bubble-map/
