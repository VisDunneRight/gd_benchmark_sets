# Protein Interactions (Publications)

Note: Various types of protein interaction graphs are recorded in other network collections. We highlight two of them from the surveyed papers. First, we have the temporal Protein Interaction Publications, showing the history of how protein interactions were described in the literature. Second, the Protein Homology graph was provided by the Large Graph Layout project, their links are now broken and the dataset lost.  Nonetheless, http://snap.stanford.edu/biodata/index.html and http://konect.cc/networks/ both also have various dataset of human/other species protein interactions. 
Origin Notes: Protein Interaction Publications were collected from the biological Pathway Commons Database: http://www.pathwaycommons.org/.
graph features handled: Dynamic, Dynamic (discrete), Large, Multigraph
Graph features in papers: generic,large,dynamic,dynamic (discrete),layered graphs,n-layers
Origin Paper: LGL: Creating a Map of Protein Function with an Algorithm for Visualizing Very Large Biological Networks (https://www.notion.so/LGL-Creating-a-Map-of-Protein-Function-with-an-Algorithm-for-Visualizing-Very-Large-Biological-Netw-fff01d52e4ad819da3f3fa6353998c7b?pvs=21), TimeArcs: Visualizing Fluctuations in Dynamic Networks (https://www.notion.so/TimeArcs-Visualizing-Fluctuations-in-Dynamic-Networks-fff01d52e4ad8178a3baf622dd9e4b41?pvs=21)
Originally found at: https://github.com/CreativeCodingLab/TimeArcs/tree/master/IndexCards

https://lgl.sourceforge.net/ (download link broken)
Size: 2961 nodes, 5267 edges
Number of Graphs: 1
Appeared in years: 2008,2016
Type of Collection: Single Graph
is it stored properly?: No
must be analyzed: No
In repo?: Yes
Related to Literature - Algorithm (1) (Dataset tag relations): Rapid Graph Layout Using Space Filling Curves (https://www.notion.so/Rapid-Graph-Layout-Using-Space-Filling-Curves-847c46047b5c400bb9dcf339c8d42f12?pvs=21), TimeArcs: Visualizing Fluctuations in Dynamic Networks (https://www.notion.so/TimeArcs-Visualizing-Fluctuations-in-Dynamic-Networks-968889d3ca4a4109aca698513515e837?pvs=21)
cleaned format?: Yes
duplicate?: No
link works?: No
Added in paper: No
OSF link json: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d94abc0c2b4d0e8d38629c
Origin paper plaintext: LGL: Creating a Map of Protein Function with an Algorithm for Visualizing Very Large Biological Networks, TimeArcs: Visualizing Fluctuations in Dynamic Networks
Page id: fff01d52e4ad810e87deee9ba4ea2077
unavailable/skip: No
Cleaned ALL data: No
OSF link gexf: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d9487494a6be101c12e7a5
OSF link gml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d96cd4803e0c0ca9558d2b
OSF link graphml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d971704cf748115a055882
first look: Yes
sparkline data: {'min': 1, 'max': 227, 'step_size': 10, 'num_bins': 23, 'bins': [0, 10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 110, 120, 130, 140, 150, 160, 170, 180, 190, 200, 210, 220], 'node_degree': [2768, 106, 38, 17, 12, 7, 3, 2, 3, 1, 1, 0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 1]}
Related to Literature - Algorithm (Dataset tag relations) 1: Rapid Graph Layout Using Space Filling Curves (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Rapid%20Graph%20Layout%20Using%20Space%20Filling%20Curves%2010601cd6078a4ea18b17c7d40eda0041.md), TimeArcs: Visualizing Fluctuations in Dynamic Networks (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/TimeArcs%20Visualizing%20Fluctuations%20in%20Dynamic%20Netwo%209d27b7e02aec4b80bc15447255eb4f4c.md)

# Body

## Protein Interaction Publications

### Statistics

![degree_distr.svg](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Protein%20Interactions%20(Publications)%20fb5bc3bb0c5d40468da36d279a114a78/degree_distr.svg)

### Description from the Literature

From [TimeArcs: Visualizing Fluctuations in Dynamic Networks](https://onlinelibrary.wiley.com/doi/10.1111/cgf.12882):

> The data contains the publication information (such as publication year, author, and textual evidence) of interactions between pairs of proteins, as well as their specific interaction type.
> 

> When there are multiple arcs connecting two proteins, it falls into one of the two circumstances. If they have the same color, these arcs indicate that there are supporting evidences in different publications which *confirm* the interaction between two elements. On the other hand, if they have the different colors, the more recent appearance provides either more detailed knowledge about the interaction or shows a *conflict* between different articles regarding the way in which these proteins interact.
> 

### Example Figures

From [TimeArcs: Visualizing Fluctuations in Dynamic Networks](https://onlinelibrary.wiley.com/doi/10.1111/cgf.12882):

![Untitled](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Protein%20Interactions%20(Publications)%20fb5bc3bb0c5d40468da36d279a114a78/Untitled.png)

**Fig. 10**: TimeArcs visualization for interactions around PCAF protein. (1), (2), and (3) in the figure are supporting evidences in literature of “PCAF binds MAML”. 

## Protein Homology (Lost)

### Description from the Literature

From [Rapid Graph Layout Using Space Filling Curves:](https://ieeexplore.ieee.org/document/4658143\)

> The “pgraph” dataset (shown in Figures 2 and 6) is a protein homology graph, which is relatively dense [7].
> 

Consists of 28, 854 vertices and 1,180, 816 edges, found in Table 1 of paper above. 

### Example Figures

From [Rapid Graph Layout Using Space Filling Curves:](https://ieeexplore.ieee.org/document/4658143)

![Untitled](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Protein%20Interactions%20(Publications)%20fb5bc3bb0c5d40468da36d279a114a78/Untitled%201.png)

**Fig. 2.** *A protein homology graph laid out with our space filling curve based approach.* Color corresponds to depth in the clustering hierarchy. |*V*| = 28, 854,|*E*| = 1, 180, 816

From [LGL: Creating a Map of Protein Function with an Algorithm for Visualizing Very Large Biological Networks](https://www.sciencedirect.com/science/article/pii/S0022283604004851)

![Untitled](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Protein%20Interactions%20(Publications)%20fb5bc3bb0c5d40468da36d279a114a78/Untitled%202.png)

**Fig. 3.** The complete protein homology map. A layout of the entire protein homology map; a total of 11,516 connected sets containing 111,604 proteins (vertices) with 1,912,684 edges. The largest connected set is shown more clearly in the inset and is enlarged further in [Figure 4](https://www.sciencedirect.com/science/article/pii/S0022283604004851?via%3Dihub#FIG4).

== STOP RENDERING ==
broken link referenced in [**Rapid Graph Layout Using Space Filling Curves**](../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Rapid%20Graph%20Layout%20Using%20Space%20Filling%20Curves%2010601cd6078a4ea18b17c7d40eda0041.md) : 

Same link referenced in original paper, 

I also found [https://lgl.sourceforge.net/](https://lgl.sourceforge.net/) which contains the link to supposedly download the dataset but it is also broken

Reached out to author - Alex Adai 

[](http://www.marcottelab.org/index.php/OldBioinformaticsServerlgl/)