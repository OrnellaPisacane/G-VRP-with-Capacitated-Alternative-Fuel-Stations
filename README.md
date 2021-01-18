# Green-Vehicle-Routing-Problem-with-Capacitated-Alternative-Fuel-Stations

For each node of the network, we report:
ID= a unique identifier
Type: d=depot, c=customer, f=station
Longitude
Latitude
Then, for each pump, we report the occupancy profile expressed through a binary array whose dimension is equal to the number of 30-minutes timeslots. In particular, 0 means that the pump is available. Instead, 1 indicates that the pump is occupied.
For the instances with 5 pumps, we give the pumps availability instead of the occupancy. Same information is given also for the instances with 15 customers and 4 pumps and a clustered customers distribution.
For more details, we refer the readers to the following two works:
Bruglieri, M., Mancini, S., & Pisacane, O. (2019). The green vehicle routing problem with capacitated alternative fuel stations. Computers & Operations Research, 112, 104759.
Bruglieri, M., Mancini, S., & Pisacane, O. (2021). A more efficient Cutting Planes Approach for the GreenVehicle Routing Problem with Capacitated AlternativeFuel Stations. Submitted to Optimization Letters.
