The instances are formatted as follows:

###For each location the instance provides:
-StringId as a unique identifier
-Type indicates the function of the location, i.e,
---d: depot
---f: recharging station
---c: customer location
-x, y are coordinates (distances are assumed to be euclidean) 
-demand specifies the quantity of freight capacity required
-ReadyTime and DueDate are the beginning and the end of the time window (waiting is allowed)
-ServiceTime denotes the entire time spend at customer for loading operations
