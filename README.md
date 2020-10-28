# US Real time wild fire model

In this experiment, we will try to use geopandas to combine geo-coded data with open and almost real time burning wildfire data. We will connect to real time basis with an API of the NIFC Current Wildfire perimeters in the U.S.  

First , we will use a spatial join to figure out which of the geo-coded locations in the portfolio are actually burning (irrespective of fire intensity noted below) 

Next, we will classify wildfire according its intensity (acres burned) and draw a buffer around each location and find out which of the locations are within a 5 Km radius to a large wildfire and within a 2 km radius of a medium fire.  

Small fires will be accounted only if our location falls within the perimeter.

