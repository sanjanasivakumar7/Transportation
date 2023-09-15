# Transportation #Allocation #heuristics #clustering
A combination of the DB scan method with the heuristic approach of random destination allocation method to determine the best location for placement of bicycle hubs.

This method combines clustering and heuristics to find out the best location for bicycle hubs around the city in the Lake District.
The initial data is obtained from Google Maps ( Longitude and Latitude coordinated), converting the coordinates to Northing and Easting values ( for easier calculation). 
After converting the coordinates, we find the distance between two locations using these coordinates. This would be considered as the cost factor for our heuristic approach later.
The initial destinations are given to the clustering method which is DB SCAN, this method does not need a pre-defined number of clusters, playing around with the parameters would help you find the ideal number of clusters and a minimum number of points per cluster. 
The last and main step of this project is to use Leon Cooper's heuristic method of random destination allocation method to determine the allocation of the bicycle hubs.
