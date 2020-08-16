Multiscale Centrality
=====================

Multiscale centrality is a scale dependent measure of centrality on complex networks. 
The code in this repository implements the algorithm and contains a small pipeline to run classic examples. 

More information on the theory can be found in the accompanying paper:
 https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.2.033104
 
## Installation

Required packages: numpy/scipy/matplotlib/networkx/forceatlas2 . 

To install, run in the main folder:

```python setup.py install```

## Tests

In the folder /test, there is a pipeline to compute the multiscale centrality on the graphs used in the accompanying paper. 
It can easily be adaped to be applied to other graphs, see the readme in the test folder.  
