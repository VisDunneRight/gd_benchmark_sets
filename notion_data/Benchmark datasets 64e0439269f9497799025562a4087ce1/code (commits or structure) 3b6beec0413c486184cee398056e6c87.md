# code (commits or structure)

Added in paper: No
Appeared in years: 3
Cleaned ALL data: No
Graph features in papers: 8
In repo?: Yes
Note: python, JUnit, Eclipse commit history used in papers. Parallel edge splatting used https://depfind.sourceforge.io/ to extract the history. + Phillips Medical System Eindhoven medical scanner software call graph
Page id: 3b6beec0413c486184cee398056e6c87
Related to Literature - Algorithm (1) (Dataset tag relations): Hierarchical Edge Bundles: Visualization of Adjacency Relations in Hierarchical Data (https://www.notion.so/Hierarchical-Edge-Bundles-Visualization-of-Adjacency-Relations-in-Hierarchical-Data-697233ee3f8d4d25b96f61924fca0cc9?pvs=21), Parallel Edge Splatting for Scalable Dynamic Graph Visualization (https://www.notion.so/Parallel-Edge-Splatting-for-Scalable-Dynamic-Graph-Visualization-789b312aeab84d299667fe1278554820?pvs=21), An Efficient Framework for Generating Storyline Visualizations from Streaming Data (https://www.notion.so/An-Efficient-Framework-for-Generating-Storyline-Visualizations-from-Streaming-Data-d06da0be3b5244b791f30c22ff2b7277?pvs=21)
Related to Literature - Algorithm (Dataset tag relations) 1: Parallel Edge Splatting for Scalable Dynamic Graph Visualization (https://www.notion.so/Parallel-Edge-Splatting-for-Scalable-Dynamic-Graph-Visualization-8fed21af91cf4c4aaf6a05ccb0335d43?pvs=21), Hierarchical Edge Bundles: Visualization of Adjacency Relations in Hierarchical Data (https://www.notion.so/Hierarchical-Edge-Bundles-Visualization-of-Adjacency-Relations-in-Hierarchical-Data-8a6e80b49e2540cf8b0c8da83bbda7ff?pvs=21), An Efficient Framework for Generating Storyline Visualizations from Streaming Data (https://www.notion.so/An-Efficient-Framework-for-Generating-Storyline-Visualizations-from-Streaming-Data-0a3f35ebac3f468cb9c3adee03f62a06?pvs=21)
Related to Literature DOIs: https://doi.org/10.1109/TVCG.2011.226,https://doi.org/10.1109/TVCG.2006.147,https://doi.org/10.1109/TVCG.2015.2392771
Related to Literature DOIs plaintext: https://doi.org/10.1109/TVCG.2011.226,https://doi.org/10.1109/TVCG.2006.147,https://doi.org/10.1109/TVCG.2015.2392771
Related to Literature plaintext: Parallel Edge Splatting for Scalable Dynamic Graph Visualization, Hierarchical Edge Bundles: Visualization of Adjacency Relations in Hierarchical Data, An Efficient Framework for Generating Storyline Visualizations from Streaming Data
Type of Collection: Aggregate collection
cleaned format?: No
duplicate?: No
is it stored properly?: No
link works?: No
must be analyzed: No
unavailable/skip: No
where to find: python link was broken, ucdavis link

From [An Efficient Framework for Generating Storyline Visualizations from Streaming Data](https://ieeexplore.ieee.org/document/7015617)

# JUnit Dependency Calls

## Descriptions from Literature

From [Parallel Edge Splatting for Scalable Dynamic Graph Visualization](https://ieeexplore.ieee.org/document/6065001)

> We collected the 21 available releases of JUnit as compiled Java bytecode and extracted the method call dependencies using *DependencyFinder* (depfind. sourceforge.net). The package and class structure provides a natural hierarchy on the methods of the system. The resulting dynamic graph consists of 2, 817 vertices connected by 15, 339 edges, where each edge is weighted by 1.
> 

## Example Figures

From [Parallel Edge Splatting for Scalable Dynamic Graph Visualization](https://ieeexplore.ieee.org/document/6065001)

![Untitled](code%20(commits%20or%20structure)%203b6beec0413c486184cee398056e6c87/Untitled.png)

**Fig. 6.** Call dependencies between methods in 21 releases of the JUnit project: all (top), added (left), and removed (right) dependencies.

# Phillips Medical Sofware Call Graph

## Descriptions from Literature

From [Hierarchical Edge Bundles: Visualization of Adjacency Relations in Hierarchical Data](https://ieeexplore.ieee.org/document/4015425)

> The software is part of a medical scanner and was provided by Philips Medical Systems Eindhoven. Three hierarchy levels – layers, units, and modules – consisting of 284 nodes are used together with the associated call graph for the elements at the lowest level of the hierarchy, i.e., 1,011 adjacency relations representing module-to-module calls.
> 

## Example Figures

From [Hierarchical Edge Bundles: Visualization of Adjacency Relations in Hierarchical Data](https://ieeexplore.ieee.org/document/4015425)

![Untitled](code%20(commits%20or%20structure)%203b6beec0413c486184cee398056e6c87/Untitled%201.png)

******************Fig. 13.****************** A software system and its associated call graph (caller = green, callee = red). (a) and (b) show the system with bundling strength β = 0.85 using a balloon layout (node labels disabled) and a radial layout, respectively. Bundling reduces visual clutter, making it easier to perceive the actual connections than when compared to the non-bundled versions (figures 2a and 11a). Bundled visualizations also show relations between sparsely connected systems more clearly (encircled regions); these are almost completely obscured in the non-bundled versions. The encircled regions highlight identical parts of the system for (a), (b), and figure 15.

# Subversion Control Logs

From **[An Efficient Framework for Generating Storyline Visualizations from Streaming Data:](https://ieeexplore.ieee.org/document/7015617)**

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