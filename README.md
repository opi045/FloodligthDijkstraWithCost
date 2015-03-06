# FloodligthDijkstraWithCost
This codes are originally taken from Floodlight git (https://github.com/floodlight/floodlight/blob/master/src/main/java/net/floodlightcontroller/topology/TopologyInstance.java). 
However some modifications are made to allow topologyinstance class to calculate actual link cost of the network and influence the behaviour of path calculation (choose the path with highest cost/weight/bandwidth) using dijkstra algorighm.
