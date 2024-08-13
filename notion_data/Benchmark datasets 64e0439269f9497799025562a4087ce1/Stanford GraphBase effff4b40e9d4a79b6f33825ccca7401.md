# Stanford GraphBase

Note: We do not currently provide this dataset for download.
Origin Notes: Compiled by Donald Knuth, the https://www-cs-faculty.stanford.edu/~knuth/sgb.html consists of programs and datasets for network analysis. The datasets accompany a textbook, “The Stanford GraphBase: A Platform for Combinatorial Computing”. Perhaps the first mention we found of the very popular “Les Miserables” network of character interactions.
graph features handled: Dynamic, Dynamic (discrete), Labeled nodes
Graph features in papers: clusters (generated),generic,planar,spatial,clusters (generated),weighted edges,dynamic,dynamic (discrete),layered graphs,n-layers,bipartite,layered graphs,generic
Origin Paper: The Stanford GraphBase: A Platform for Combinatorial Computing (https://www.notion.so/The-Stanford-GraphBase-A-Platform-for-Combinatorial-Computing-f28a00500d684add8b0de06339dfd128?pvs=21)
Originally found at: https://www-cs-faculty.stanford.edu/~knuth/sgb.html
Appeared in years: 2017,2016,1997,2004,2019
Type of Collection: Missed it
is it stored properly?: No
must be analyzed: No
In repo?: No
Related to Literature - Algorithm (1) (Dataset tag relations): Crossing Minimization in Storyline Visualization (https://www.notion.so/Crossing-Minimization-in-Storyline-Visualization-2953ec267f7f468bb4b306faee452952?pvs=21), Graph Layouts by t-SNE (https://www.notion.so/Graph-Layouts-by-t-SNE-6adb46473eb2415294b0d797ad86b077?pvs=21), Simple and Efficient Bilayer Cross Counting (https://www.notion.so/Simple-and-Efficient-Bilayer-Cross-Counting-6f978d8b0ceb4a6eb7df52ed82999861?pvs=21), 2-Layer Straightline Crossing Minimization (https://www.notion.so/2-Layer-Straightline-Crossing-Minimization-99889f8092bf47c7973040551b298d28?pvs=21), Anisotropic Radial Layout for Visualizing Centrality and Structure in Graphs (https://www.notion.so/Anisotropic-Radial-Layout-for-Visualizing-Centrality-and-Structure-in-Graphs-c604b563b3594a69b6c8e57b5ce9f02f?pvs=21)
cleaned format?: No
duplicate?: Yes
link works?: No
Added in paper: No
Origin paper plaintext: The Stanford GraphBase: A Platform for Combinatorial Computing
Page id: effff4b40e9d4a79b6f33825ccca7401
unavailable/skip: Yes
Cleaned ALL data: No
first look: No
Related to Literature - Algorithm (Dataset tag relations) 1: Graph Layouts by t-SNE (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Graph%20Layouts%20by%20t-SNE%203af4ccbc89b547a38748745511744997.md), Anisotropic Radial Layout for Visualizing Centrality and Structure in Graphs (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Anisotropic%20Radial%20Layout%20for%20Visualizing%20Centrali%20c964c73e1c2946f992cb72bac2b19c42.md), Crossing Minimization in Storyline Visualization (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Crossing%20Minimization%20in%20Storyline%20Visualization%20adc579d114c9412e8dad9e068e18d960.md), 2-Layer Straightline Crossing Minimization (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/2-Layer%20Straightline%20Crossing%20Minimization%209f4d9dc9520e495ba5a1ef31fdd34760.md), Simple and Efficient Bilayer Cross Counting (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Simple%20and%20Efficient%20Bilayer%20Cross%20Counting%20f879285ff264423cb974db4969614248.md), A Random Sampling O(n) Force-calculation Algorithm for Graph Layouts (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/A%20Random%20Sampling%20O(n)%20Force-calculation%20Algorithm%2086599a831f314d1cb8871a5a92420d0f.md)

# Body

### Descriptions from Literature

From “[Crossing Minimization in Storyline Visualizations](https://doi.org/10.1007/978-3-319-50106-2_29)”:

> Since the instances “Anna Karenina” and “Les Miserables” are very big, we have split them into chapters and sequences of chapters. The resulting test-bed is made of eight chapters, seven pairs of chapters, six triples of chapters and five quadruples of chapters from “Anna Karenina”, and five chapters, four pairs of chapters and three triples of chapters from “Les Mis ́erables”, plus the entire “Adventures of Huckleberry Finn”, “Inception-sf”, “Inception”, “Star Wars”, “The Matrix-sf”, and “The Matrix”.
> 

From “[Anisotropic Radial Layout for Visualizing Centrality and Structure in Graphs](https://doi.org/10.1007/978-3-319-73915-1_28)”:

> The third dataset is a graph of character associations in the famous French novel Les Miserables (Fig. 5) [18]. This graph consists of 77 nodes, each representing a character in the novel, and 254 weighted edges where the weights represent the number of chapters that feature both characters associated with an edge.
We see the that the main protagonist Valjean (marked in red) is placed prominently in all three visualizations (Fig. 5). However, other key characters in the plot such as Inspector Javert (blue) and Cosett (orange), who do not appear often with characters other than the protagonist (and thus have low betweenness centrality) are treated differently. While the radial layout relegates them to the periphery (far from Valjean) (Fig. 5b), MDS (Fig. 5a) paints a conflicting picture with regard to their centrality, e.g., Cosett’s node almost overlaps with Valjean despite its low centrality. In contrast, the proposed ARL (Fig.5c) is able to coherently convey the low centrality of the Inspector Javert and Cosett, as well as, their closeness to Valjean. The above issue of distance distortion appears to be a frequent occurrence in the radial layout due to many characters who have a low centrality value causing them to end up being packed in the outer periphery. A case of contrast is that of the character Bishop Myriel (green) who despite being associated with several characters, is only seen with Valjean once.
> 

### Example Figures

From “[Crossing Minimization in Storyline Visualizations](https://doi.org/10.1007/978-3-319-50106-2_29)”:

![Screen Shot 2023-08-17 at 4.29.43 PM.png](Stanford%20GraphBase%20effff4b40e9d4a79b6f33825ccca7401/Screen_Shot_2023-08-17_at_4.29.43_PM.png)

From “[Graph Layouts by t-SNE](https://doi.org/10.1111/cgf.13187)”:

![Screen Shot 2023-08-17 at 4.21.24 PM.png](Stanford%20GraphBase%20effff4b40e9d4a79b6f33825ccca7401/Screen_Shot_2023-08-17_at_4.21.24_PM.png)

lesmis is the GraphBase Les Miserables graph

From “[Anisotropic Radial Layout for Visualizing Centrality and Structure in Graphs](https://doi.org/10.1007/978-3-319-73915-1_28)”:

![Screen Shot 2023-08-17 at 4.23.56 PM.png](Stanford%20GraphBase%20effff4b40e9d4a79b6f33825ccca7401/Screen_Shot_2023-08-17_at_4.23.56_PM.png)