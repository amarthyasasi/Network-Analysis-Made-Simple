## Introduction

## Topic 1: 

- Graph basics: nodes and edges
- Basic programming patterns
- Querying a graph in NetworkX:
    - Number of nodes
    - Querying node metadata
    - Number of edges
    - Querying edge metadata
- Object-to-matrix conversion

## Topic 2: "How important are certain nodes?"

- Metric 1: The number of links going into and out of a node
    - Number of neighbours
    - Degree centrality
- Metric 2: The number of times that node shows up on shortest paths between any two nodes
    - Shortest path algorithm: Breadth-first search
- Not all metrics correlate with one another
- Examples: paper citation network, Twitter network

## Topic 3: "How do we find interesting structures?"

- Definition of a triangle: the simplest complex clique
- Finding triangles
- Finding open triangles
- Example: friend recommendation systems

## Topic 4: "How do I store my graph data?"

- Saving/loading data to disk as Python pickles
- Saving/loading data as node and edge lists (CSVs) with `pandas`
- Example: loading bike sharing (Divvy) data from disk

## Topic 5: "Statistical inference on graphs."

- Statistical inference steps
- Graph summary statistics
- Test statistics
- Node statistic distributions
- Example: inferring node metadata in the Advogato social network

## Topic 6: "What if my nodes aren't of the same type?"

- Definition of unipartite and bipartite graphs
- Constructing bipartite graphs in NetworkX
- Converting from bipartite graphs to unipartite
- Example: product recommendation systems

## Topic 7: References, more exercises, and further reading.

- Allen Downey: Think Complexity
- Allen Downey: Think Stats
- Jake Vanderplas: Statistics for Hackers
- Eric D. Kolaczyk: Statistical Analysis of Network Data