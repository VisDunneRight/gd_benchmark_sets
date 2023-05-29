# Scotch Graph Collection

Added in paper: No
Appeared in years: 1
Graph features in papers: 2
In repo?: Yes
Note: The SCOTCH software package is produced by the SCOTCH project whose goal is to study static mapping by the means of graph theory, using a “divide and conquer'' approach.
The SCOTCH software package for static mapping embodies all the algorithms and graph bipartitioning heuristics developed within the SCOTCH project.
Author: Francois Pellegrini (mailto:pelegrin@labri.u-bordeaux.fr)
Number of Files: 39
Origin Notes: Collection consisting of graphs from various sources including topological meshes, meshes related to physicla problems (fluid dynamics, structural mechanics, combinatorial optimization), and interprocess communicaiton graphs for a parallel computing implementation of a factorization solver. 
Collected from Steve Hammond, the Harwell-Boeing Collection, Bruce Hendrickson, and Horst Simon.
Page id: cfe6f105da3a4c699fa3e02ca1f6e88a
Related to Literature - Algorithm (1) (Dataset tag relations): https://www.notion.so/ACE-A-Fast-Multiscale-Eigenvectors-Computation-for-Drawing-Huge-Graphs-44f8183954f14ada944d642d9ff1298e, https://www.notion.so/A-Fast-Multi-Scale-Method-for-Drawing-Large-Graphs-a49d7ec5808945baae7a5246a191c986
Related to Literature - Algorithm (Dataset tag relations) 1: https://www.notion.so/A-Fast-Multi-Scale-Method-for-Drawing-Large-Graphs-fdc9e1d148bc4fcd848d8b4cc959cdfd, https://www.notion.so/ACE-A-Fast-Multiscale-Eigenvectors-Computation-for-Drawing-Huge-Graphs-5e8de72ea8d0436babf760ca379cc457
Related to Literature DOIs: https://doi.org/10.1007/3-540-44541-2_18,https://doi.org/10.1109/INFVIS.2002.1173159
Related to Literature DOIs plaintext: https://doi.org/10.1007/3-540-44541-2_18,https://doi.org/10.1109/INFVIS.2002.1173159
Related to Literature plaintext: A Fast Multi-Scale Method for Drawing Large Graphs, ACE: A Fast Multiscale Eigenvectors Computation for Drawing Huge Graphs
Type of Collection: Large Collection (No report)
cleaned format?: Yes
duplicate?: No
format: Scotch (.src files) - first line is the number of vertices followed by . number of arcs (2 time |E|). Then each line represents a vertex with the following format:
id load degree   adjencency list(load to_id)  
is it stored properly?: No
link works?: Yes
must be analyzed: No
unavailable/skip: No
where to find: https://wotug.org/parallel/libraries/communication/scotch/Graphs/

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