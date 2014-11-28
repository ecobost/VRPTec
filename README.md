VRPTec
======
Solves the vehicle routing problem with different search heuristics and algorithms. Done for the Artificial Intelligence Department at Tec de Monterrey in July 2013 (!!please ask for authorization if you plan to use for commercial purposes). A newer version has been developed in the Department with added capabilities. 
Allows you to specify via XML the coordinates of the deposit, every customer that neeeds to be served and the time windows the truck can visit, distance and time between customers capacity of trucks, number of vehicles. It also lets you specify via XML a objective function to maximize, the heuristic to use to generate new solutions and any information to be passed to the algorithm. Results are written to a XML. Read the format files to check how to input and output data.
Tools for transforming Solomon format VRP specifications to VRPTEC format and for visualizing output data in 2d map were implemented but are not provided.
Read the guide (Spanish) for specification of algorithms already implemented. Implementing a new algorithm or algorithm should not be hard.
