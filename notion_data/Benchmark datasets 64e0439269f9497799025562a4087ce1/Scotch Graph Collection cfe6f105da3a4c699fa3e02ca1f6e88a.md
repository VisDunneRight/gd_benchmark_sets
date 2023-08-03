# Scotch Graph Collection

Note: The SCOTCH software package is produced by the SCOTCH project whose goal is to study static mapping by the means of graph theory, using a “divide and conquer'' approach.
The SCOTCH software package for static mapping embodies all the algorithms and graph bipartitioning heuristics developed within the SCOTCH project.
Author: Francois Pellegrini (mailto:pelegrin@labri.u-bordeaux.fr)
Origin Notes: Collection consisting of graphs from various sources including topological meshes, meshes related to physical problems (fluid dynamics, structural mechanics, combinatorial optimization), and interprocess communicaiton graphs for a parallel computing implementation of a factorization solver. 
Collected from Steve Hammond, the Harwell-Boeing Collection, Bruce Hendrickson, and Horst Simon.
graph features handled: large
Graph features in papers: 2
Originally found at: https://wotug.org/parallel/libraries/communication/scotch/Graphs/
Size: The graphs range from 7 to144649 nodes, and 10 to 1074393 edges.
Number of Graphs: 39
format: Scotch (.src files) - first line is the number of vertices followed by . number of arcs (2 time |E|). Then each line represents a vertex with the following format:
id load degree   adjencency list(load to_id)  
Child collections: Walshaw (Walshaw%20e40b37a1147942d89ff1d8dfad285256.md)
Appeared in years: 1
Type of Collection: Uniform Benchmark
is it stored properly?: No
must be analyzed: No
In repo?: Yes
Related to Literature - Algorithm (1) (Dataset tag relations): ACE: A Fast Multiscale Eigenvectors Computation for Drawing Huge Graphs (https://www.notion.so/ACE-A-Fast-Multiscale-Eigenvectors-Computation-for-Drawing-Huge-Graphs-44f8183954f14ada944d642d9ff1298e?pvs=21), A Fast Multi-Scale Method for Drawing Large Graphs (https://www.notion.so/A-Fast-Multi-Scale-Method-for-Drawing-Large-Graphs-a49d7ec5808945baae7a5246a191c986?pvs=21)
cleaned format?: Yes
duplicate?: No
link works?: Yes
Added in paper: No
OSF link: https://osf.io/download/2stjq/
Page id: cfe6f105da3a4c699fa3e02ca1f6e88a
unavailable/skip: No
Cleaned ALL data: No
OSF link for node-link format: https://osf.io/download/2rnzb/
Related to Literature - Algorithm (Dataset tag relations) 1: A Fast Multi-Scale Method for Drawing Large Graphs (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/A%20Fast%20Multi-Scale%20Method%20for%20Drawing%20Large%20Graphs%20fdc9e1d148bc4fcd848d8b4cc959cdfd.md), ACE: A Fast Multiscale Eigenvectors Computation for Drawing Huge Graphs (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/ACE%20A%20Fast%20Multiscale%20Eigenvectors%20Computation%20for%205e8de72ea8d0436babf760ca379cc457.md)
first look: No
sparkline data: {'min': 7, 'max': 144649, 'step_size': 10000, 'num_bins': 15, 'bins': [0, 10000, 20000, 30000, 40000, 50000, 60000, 70000, 80000, 90000, 100000, 110000, 120000, 130000, 140000], 'num_nodes': [24, 4, 1, 2, 2, 0, 1, 1, 0, 1, 0, 1, 0, 0, 2]}

# Body

### Statistics

![four_in_one.svg](Scotch%20Graph%20Collection%20cfe6f105da3a4c699fa3e02ca1f6e88a/four_in_one.svg)

===  STOP RENDERING ===

```

			===========================

			The SCOTCH graph collection

			===========================

The graphs that comprise this collection have been gathered from various
sites and people (Steve Hammond, the Harwell-Boeing collection, Bruce
Hendrickson, and Horst Simon). They are all stored in SCOTCH source graph
format (.src), and are accompanied with their geometry file (.xyz) whenever
available.

This directory contains:

ar_*		: Architecture graphs for classical topologies, mostly meshes.

fe_*		: Triangular and quadrangular unstructured meshes related to
		  fluid dynamics, structural mechanics, or combinatorial
		  optimization problems.

nd_*		: Valuated interprocess communication graphs issued from a
		  parallel implementation of a sparse block Cholesky
		  factorization solver, which represent partitions of the
		  unknowns induced by a nested dissection method.
		  The nd_ref0, nd_ref1, nd_ref2, nd_ref3, and nd_ref4 graphs
		  are aliases for the nd_2047.7750, nd_2453.47659,
		  nd_2815.84406, nd_3093.105713, and nd_3470.135148 graphs,
		  respectively.
```

Author: Francois Pellegrini (*[pelegrin@labri.u-bordeaux.fr](mailto:pelegrin@labri.u-bordeaux.fr)*)