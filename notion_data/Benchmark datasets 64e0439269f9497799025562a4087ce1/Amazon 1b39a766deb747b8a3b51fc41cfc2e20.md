# Amazon

Note: This dataset is a proper subset of SNAP%20(Stanford%20Network%20Analysis%20Platform)%201cd77eaee57147ce8263b2f9eaa2589c.md and can be found there.
Origin Notes: Wallinger et al. randomly filter data from the original dataset collected by Leskovec et al. in “The dynamics of viral marketing”. Leskovec et al. collected 15 million recommendations made from June 2001, to May 2003 by looking at the “Customers who Bought This Item Also Bought” feature in the Amazon online shopping platform.
graph features handled: directed edges, large
Graph features in papers: bundled edges (generated),spatial
Originally found at:  http://snap.stanford.edu/data/#amazon
Size: 1 graph, 192k vertices and 269k edges
Number of Graphs: 0
Origin Paper: SNAP Datasets: Stanford Large Network Dataset Collection (https://www.notion.so/SNAP-Datasets-Stanford-Large-Network-Dataset-Collection-b5f4bd2e98834a638a5c4ab563047d28?pvs=21), The dynamics of viral marketing (https://www.notion.so/The-dynamics-of-viral-marketing-f45ebdd22e5f4a95a1456bc1ae1b0fdb?pvs=21)
Child collections: SNAP (Stanford Network Analysis Platform) (SNAP%20(Stanford%20Network%20Analysis%20Platform)%201cd77eaee57147ce8263b2f9eaa2589c.md)
Appeared in years: 2022
Type of Collection: Subset of other collection
is it stored properly?: No
must be analyzed: No
In repo?: No
Related to Literature - Algorithm (1) (Dataset tag relations): Edge-Path Bundling: A Less Ambiguous Edge Bundling Approach (https://www.notion.so/Edge-Path-Bundling-A-Less-Ambiguous-Edge-Bundling-Approach-932f56be1ec24c50a2c3fc65a37ed172?pvs=21)
cleaned format?: No
duplicate?: No
link works?: No
Added in paper: No
Origin paper plaintext: SNAP Datasets: Stanford Large Network Dataset Collection, The dynamics of viral marketing
Page id: 1b39a766deb747b8a3b51fc41cfc2e20
unavailable/skip: Yes
Cleaned ALL data: No
Related to Literature - Algorithm (Dataset tag relations) 1: Edge-Path Bundling: A Less Ambiguous Edge Bundling Approach (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Edge-Path%20Bundling%20A%20Less%20Ambiguous%20Edge%20Bundling%20%20fcfa5882e692481298cbee906e005c30.md)
first look: Yes

# Body

### Description from Literature

From [Edge-Path Bundling: A Less Ambiguous Edge Bundling Approach:](https://ieeexplore.ieee.org/document/9552919)

> **Amazon Subset**
> 
> 
> This dataset consists of products with edges indicating that they are commonly co-purchased. We randomly filtered edges from the original graph [33], [34]. It has |V|=192k vertices and |E|=269k edges.
> 

### Example Figures

From [Edge-Path Bundling: A Less Ambiguous Edge Bundling Approach:](https://ieeexplore.ieee.org/document/9552919)

![Untitled](Amazon%201b39a766deb747b8a3b51fc41cfc2e20/Untitled.png)

== STOP RENDERING ==

look here: [https://github.com/mwallinger-tu/edge-path-bundling/tree/master/data](https://github.com/mwallinger-tu/edge-path-bundling/tree/master/data) from [**Edge-Path Bundling: A Less Ambiguous Edge Bundling Approach**](../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Edge-Path%20Bundling%20A%20Less%20Ambiguous%20Edge%20Bundling%20%20fcfa5882e692481298cbee906e005c30.md) 

Note: Amazon is the only dataset not included in their GitHub. They randomly sampled a graph with 192k vertices and 269k edges from the data collected by Leskovec et al in the SNAP dataset

Original dataset: [http://snap.stanford.edu/data/#amazon](http://snap.stanford.edu/data/#amazon)

 doi: 10.1145/1134707.1134732 (subgraph of a SNAP collection graph)