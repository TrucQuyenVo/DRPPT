Data is generated based on the benchmark instances of VRPD_Instances of Sacramento et al. (2019) 
Data in AMPL is reformatted based on Data in CPP

Data includes: general information (RouteData.txt), information of customers (x.x.x.txt in different sizes and samples), information of PT system (g.xx.txt in different grids)

/instances/nbcus.grid.id.txt
Customers nbCus
Coordinate X	Coordinate	Y	Demand	(Distance matrix is computed based on Euclidian Distance Formulation)

/grids/g.range.txt
nbStation
nbDeparture
Index	X	Y

LINES
line 1: 	station 1 	station 2	station 3	
line 2:	station i	station ...
....

DEPARTURE TIME
trip 1	trip2 	...


