# Code Dependency Graphs

Note: Various software call dependency graphs have been used in the literature. We provide the benchmarks used in ““https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.13724”, as these posed the most comprehensive and available collection. 
 “https://ieeexplore.ieee.org/document/6065001” used a software call graph from a device called a “Phillips Medical System Eindhoven medical scanner”, which is lost. Python and Eclipse subversion control logs are also currently lost.
Origin Notes: The authors of “https://ieeexplore.ieee.org/document/6065001” used https://depfind.sourceforge.io/ to extract the commit history.
graph features handled: directed edges
Graph features in papers: dynamic,layered graphs,n-layers,weighted edges,bundled edges (generated),compound graphs,hierarchical,dynamic,dynamic (discrete),layered graphs,n-layers,layered graphs,n-layers
Origin Paper: A Random Sampling O(n) Force-calculation Algorithm for Graph Layouts (https://www.notion.so/A-Random-Sampling-O-n-Force-calculation-Algorithm-for-Graph-Layouts-a0bc2ae6ebdb4e8cbddb924c0484cfad?pvs=21)
Originally found at: http://vis.cs.ucdavis.edu/~ogawa/datasets/ (broken)
https://osf.io/dcz5h 
Size: 128-2956 nodes, 310-10845 edges
Number of Graphs: 11
Appeared in years: 2011,2006,2015,2018
Type of Collection: Aggregate collection
is it stored properly?: No
must be analyzed: No
In repo?: Yes
Related to Literature - Algorithm (1) (Dataset tag relations): Hierarchical Edge Bundles: Visualization of Adjacency Relations in Hierarchical Data (https://www.notion.so/Hierarchical-Edge-Bundles-Visualization-of-Adjacency-Relations-in-Hierarchical-Data-697233ee3f8d4d25b96f61924fca0cc9?pvs=21), Parallel Edge Splatting for Scalable Dynamic Graph Visualization (https://www.notion.so/Parallel-Edge-Splatting-for-Scalable-Dynamic-Graph-Visualization-789b312aeab84d299667fe1278554820?pvs=21), An Efficient Framework for Generating Storyline Visualizations from Streaming Data (https://www.notion.so/An-Efficient-Framework-for-Generating-Storyline-Visualizations-from-Streaming-Data-d06da0be3b5244b791f30c22ff2b7277?pvs=21)
cleaned format?: Yes
duplicate?: No
link works?: No
Added in paper: No
OSF link json: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d90f0994a6be0ec112e76b
Origin paper plaintext: A Random Sampling O(n) Force-calculation Algorithm for Graph Layouts
Page id: 3b6beec0413c486184cee398056e6c87
unavailable/skip: No
Cleaned ALL data: No
OSF link gexf: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d94840803e0c0bf6558bd1
OSF link gml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d96dc01101aa0ea66a0bee
OSF link graphml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d970111101aa0ea36a0c62
first look: No
sparkline data: {'min': 128, 'max': 2956, 'step_size': 1000, 'num_bins': 3, 'bins': [0, 1000, 2000], 'num_nodes': [8, 1, 2]}
Related to Literature - Algorithm (Dataset tag relations) 1: Parallel Edge Splatting for Scalable Dynamic Graph Visualization (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Parallel%20Edge%20Splatting%20for%20Scalable%20Dynamic%20Graph%208fed21af91cf4c4aaf6a05ccb0335d43.md), Hierarchical Edge Bundles: Visualization of Adjacency Relations in Hierarchical Data (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Hierarchical%20Edge%20Bundles%20Visualization%20of%20Adjacen%208a6e80b49e2540cf8b0c8da83bbda7ff.md), An Efficient Framework for Generating Storyline Visualizations from Streaming Data (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/An%20Efficient%20Framework%20for%20Generating%20Storyline%20Vi%200a3f35ebac3f468cb9c3adee03f62a06.md), CFGExplorer: Designing a Visual Control Flow Analytics System around Basic Program Analysis Operations (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/CFGExplorer%20Designing%20a%20Visual%20Control%20Flow%20Analyt%20656cb91a95ea4c6cbfca60aa5ab8707b.md)

# Body

### Statistics

![four_in_one.svg](Code%20Dependency%20Graphs%203b6beec0413c486184cee398056e6c87/four_in_one.svg)

## Software Dependency Calls

### Descriptions from Literature

From “[A Random Sampling O(n) Force-calculation Algorithm for Graph Layouts](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.13724)”:

> The software graphs show dependencies in several software packages [**[vB11](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.13724#cgf13724-bib-0076)**, **[vB02](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.13724#cgf13724-bib-0075)**, **[vB12](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.13724#cgf13724-bib-0077)**, **[vBB13](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.13724#cgf13724-bib-0078)**, **[vvBB14](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.13724#cgf13724-bib-0082)**].
> 

From “[Parallel Edge Splatting for Scalable Dynamic Graph Visualization](https://ieeexplore.ieee.org/document/6065001)”:

> We collected the 21 available releases of JUnit as compiled Java bytecode and extracted the method call dependencies using *DependencyFinder* (depfind. sourceforge.net). The package and class structure provides a natural hierarchy on the methods of the system. The resulting dynamic graph consists of 2,817 vertices connected by 15,339 edges, where each edge is weighted by 1.
> 

### Example Figures

From [Parallel Edge Splatting for Scalable Dynamic Graph Visualization](https://ieeexplore.ieee.org/document/6065001):

![Untitled](Code%20Dependency%20Graphs%203b6beec0413c486184cee398056e6c87/Untitled.png)

**Fig. 6.** Call dependencies between methods in 21 releases of the JUnit project: all (top), added (left), and removed (right) dependencies.

## Phillips Medical Software Call Graph (Lost)

### Descriptions from Literature

From “[Hierarchical Edge Bundles: Visualization of Adjacency Relations in Hierarchical Data](https://ieeexplore.ieee.org/document/4015425)”:

> The software is part of a medical scanner and was provided by Philips Medical Systems Eindhoven. Three hierarchy levels – layers, units, and modules – consisting of 284 nodes are used together with the associated call graph for the elements at the lowest level of the hierarchy, i.e., 1,011 adjacency relations representing module-to-module calls.
> 

### Example Figures

From “[Hierarchical Edge Bundles: Visualization of Adjacency Relations in Hierarchical Data](https://ieeexplore.ieee.org/document/4015425)”:

![Untitled](Code%20Dependency%20Graphs%203b6beec0413c486184cee398056e6c87/Untitled%201.png)

******************Fig. 13.****************** A software system and its associated call graph (caller = green, callee = red). (a) and (b) show the system with bundling strength β = 0.85 using a balloon layout (node labels disabled) and a radial layout, respectively. Bundling reduces visual clutter, making it easier to perceive the actual connections than when compared to the non-bundled versions (figures 2a and 11a). Bundled visualizations also show relations between sparsely connected systems more clearly (encircled regions); these are almost completely obscured in the non-bundled versions. The encircled regions highlight identical parts of the system for (a), (b), and figure 15.

### Subversion Control Logs (Lost)

From “[An Efficient Framework for Generating Storyline Visualizations from Streaming Data”:](https://ieeexplore.ieee.org/document/7015617)

> The datasets we used for this study were:
…
*Python Subversion Control Logs* (*Python*) [30] 
E*clipse Subversion Control Logs* (*Eclipse*) [30]
…
These datasets all contained temporal logs of events in which entities interact.
> 

=== STOP RENDERING ==

I cannot find the Phillips medical software call graphs - the paper implies they were directly given to the author so it might be hard to get. 

Subversion control logs also lost. Broken link from UCDavis. 

M. Ogawa. Software development history logs [Online]. Available:
[http://vis.cs.ucdavis.edu/~ogawa/datasets/](http://vis.cs.ucdavis.edu/~ogawa/datasets/), Jan. 2015.