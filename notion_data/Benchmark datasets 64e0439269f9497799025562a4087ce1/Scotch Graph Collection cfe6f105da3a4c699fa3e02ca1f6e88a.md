# Scotch Graph Collection

Note: Collection consisting of graphs from various sources including topological meshes, meshes related to physical problems (fluid dynamics, structural mechanics, combinatorial optimization), and interprocess communication graphs for a parallel computing implementation of a factorization solver. 
Origin Notes: The https://gitlab.inria.fr/scotch/scotch is produced by the https://www.labri.fr/perso/pelegrin/scotch/ whose goal is to study static mapping by the means of graph theory, using “divide and conquer'' graph bipartitioning heuristics. The original link to the data http://www.labri.u-bordeaux.fr/Equipe/PARADIS/Member/pelegrin/graph is broken.
graph features handled: large, mesh
Graph features in papers: generic,large
Originally found at: https://wotug.org/parallel/libraries/communication/scotch/Graphs/
Size: The graphs range from 7 to 144649 nodes, and 10 to 1074393 edges.
Number of Graphs: 39
Origin Paper: Scotch and PT-Scotch Graph Partitioning Software: An Overview (https://www.notion.so/Scotch-and-PT-Scotch-Graph-Partitioning-Software-An-Overview-2845b7c5cbc14fa8a02acfbc1e3a28ef?pvs=21), PT-Scotch: A tool for efficient parallel graph ordering (https://www.notion.so/PT-Scotch-A-tool-for-efficient-parallel-graph-ordering-bb06d1044c6b4029a1216c60eb23de18?pvs=21)
format: Scotch (.src files) - first line is the number of vertices followed by . number of arcs (2 time |E|). Then each line represents a vertex with the following format:
id load degree   adjencency list(load to_id)  
Child collections: Walshaw (Walshaw%20e40b37a1147942d89ff1d8dfad285256.md)
Appeared in years: 2002
Type of Collection: Uniform Benchmark
is it stored properly?: No
must be analyzed: No
In repo?: Yes
Related to Literature - Algorithm (1) (Dataset tag relations): ACE: A Fast Multiscale Eigenvectors Computation for Drawing Huge Graphs (https://www.notion.so/ACE-A-Fast-Multiscale-Eigenvectors-Computation-for-Drawing-Huge-Graphs-44f8183954f14ada944d642d9ff1298e?pvs=21), A Fast Multi-Scale Method for Drawing Large Graphs (https://www.notion.so/A-Fast-Multi-Scale-Method-for-Drawing-Large-Graphs-a49d7ec5808945baae7a5246a191c986?pvs=21)
cleaned format?: Yes
duplicate?: No
link works?: Yes
Added in paper: No
OSF link json: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d90eda803e0c0b00558bc8
Origin paper plaintext: Scotch and PT-Scotch Graph Partitioning Software: An Overview, PT-Scotch: A tool for efficient parallel graph ordering
Page id: cfe6f105da3a4c699fa3e02ca1f6e88a
unavailable/skip: No
Cleaned ALL data: No
Related to Literature - Algorithm (Dataset tag relations) 1: A Fast Multi-Scale Method for Drawing Large Graphs (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/A%20Fast%20Multi-Scale%20Method%20for%20Drawing%20Large%20Graphs%20fdc9e1d148bc4fcd848d8b4cc959cdfd.md), ACE: A Fast Multiscale Eigenvectors Computation for Drawing Huge Graphs (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/ACE%20A%20Fast%20Multiscale%20Eigenvectors%20Computation%20for%205e8de72ea8d0436babf760ca379cc457.md)
OSF link gexf: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d94897803e0c0bfb558d06
OSF link gml: https://osf.io/download/w37bv/
OSF link graphml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d971ca94a6be112a12ea97
first look: No
sparkline data: {'min': 7, 'max': 144649, 'step_size': 10000, 'num_bins': 15, 'bins': [0, 10000, 20000, 30000, 40000, 50000, 60000, 70000, 80000, 90000, 100000, 110000, 120000, 130000, 140000], 'num_nodes': [24, 4, 1, 2, 2, 0, 1, 1, 0, 1, 0, 1, 0, 0, 2]}

# Body

### Statistics

![four_in_one.svg](Scotch%20Graph%20Collection%20cfe6f105da3a4c699fa3e02ca1f6e88a/four_in_one.svg)

### Descriptions from Literature

From [ACE: A Fast Multiscale Eigenvectors Computation for Drawing Huge Graphs](https://doi.org/10.1109/INFVIS.2002.1173159):

> Figure 10c, the 4elt graph, is yet another example of a graph with inherent diversity of distance scales.
> 

### Example Figures

From [A Fast Multi-Scale Method for Drawing Large Graphs](https://doi.org/10.1007/3-540-44541-2_18):

![Screen Shot 2023-08-04 at 8.14.10 AM.png](Scotch%20Graph%20Collection%20cfe6f105da3a4c699fa3e02ca1f6e88a/Screen_Shot_2023-08-04_at_8.14.10_AM.png)

![Screen Shot 2023-08-04 at 8.14.29 AM.png](Scotch%20Graph%20Collection%20cfe6f105da3a4c699fa3e02ca1f6e88a/Screen_Shot_2023-08-04_at_8.14.29_AM.png)

From [ACE: A Fast Multiscale Eigenvectors Computation for Drawing Huge Graphs](https://doi.org/10.1109/INFVIS.2002.1173159):

![Screen Shot 2023-08-04 at 8.30.54 AM.png](Scotch%20Graph%20Collection%20cfe6f105da3a4c699fa3e02ca1f6e88a/Screen_Shot_2023-08-04_at_8.30.54_AM.png)

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