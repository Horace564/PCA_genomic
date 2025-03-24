# Spectral clustering on Facebook friend
- The friends data set come from [Stanford Network Analysis Project (SNAP)](https://snap.stanford.edu/)
- The file friends.csv is part of the ego-Facebook dataset on the SNAP website
- The file contains all the related relationship between individuals, namely the edges of graph

## This mini-project is to cluster nodes(firends) with certain constrains as follows:
1. 150 < node_size < 750
2. cluster the data into at least 3 groups
3. the conductance between groups must smaller than 0.1
4. The conductance of $S\subset V$ is defined as
```math
conductance = \frac{E}{D}
```
where E = number of boundary edges of S, D = total degree of S
