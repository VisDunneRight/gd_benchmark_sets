# Co-Phylogenetic Trees

Note: Each element of the data set is two binary co-phylogentic trees. “Caryophyllaceae & Microbotryum” and “Stinkbugs & Bacteria” are missing but our dataset includes all other files from “https://doi.org/10.1007/978-3-319-73915-1_27”. An additional dataset from “https://almob.biomedcentral.com/articles/10.1186/s13015-014-0031-3”, called “Wolbachia”, is included.
Origin Notes: Collected by the authors of “https://almob.biomedcentral.com/articles/10.1186/s13015-014-0031-3”.
graph features handled: trees
Graph features in papers: binary trees,trees
Origin Paper: EUCALYPT: efficient tree reconciliation enumerator (https://www.notion.so/EUCALYPT-efficient-tree-reconciliation-enumerator-fb8986c3955845d6b05b5df381305502?pvs=21)
Originally found at: https://gitlab.inria.fr/erable/eucalypt/-/blob/master/html/PaperDatasets.zip
Size: 13-773 nodes, 12-772 edges
Number of Graphs: 30
Appeared in years: 2017
Type of Collection: Uniform Benchmark
is it stored properly?: No
must be analyzed: Yes
In repo?: Yes
Related to Literature - Algorithm (1) (Dataset tag relations): Visualizing Co-phylogenetic Reconciliations (https://www.notion.so/Visualizing-Co-phylogenetic-Reconciliations-3f8b94b104d94e498eb0eeb1ec687f1f?pvs=21)
cleaned format?: Yes
duplicate?: No
link works?: No
Added in paper: No
OSF link json: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d90ee40c2b4d0d2e3862b7
Origin paper plaintext: EUCALYPT: efficient tree reconciliation enumerator
Page id: 2440f3927d254148abd93168c1399b43
unavailable/skip: No
Cleaned ALL data: No
OSF link gexf: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d948a24cf748105905574b
OSF link gml: https://osf.io/download/m9wf2/
OSF link graphml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d970c00c2b4d0f5d3862a4
first look: No
sparkline data: {'min': 13, 'max': 773, 'step_size': 100, 'num_bins': 8, 'bins': [0, 100, 200, 300, 400, 500, 600, 700], 'num_nodes': [23, 5, 0, 0, 0, 0, 0, 2]}
Related to Literature - Algorithm (Dataset tag relations) 1: Visualizing Co-phylogenetic Reconciliations (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Visualizing%20Co-phylogenetic%20Reconciliations%20fd4b98c0071f4e96924bacd938e706b5.md)

# Body

### Statistics

![four_in_one.svg](Co-Phylogenetic%20Trees%202440f3927d254148abd93168c1399b43/four_in_one.svg)

### Descriptions from Literature

From “[EUCALYPT: efficient tree reconciliation enumerator](https://almob.biomedcentral.com/articles/10.1186/s13015-014-0031-3)”:

> To test EUCALYPT, we selected 12 datasets from the literature. As we are mostly interested in host-parasite systems, the first 10 datasets concern such relations: EC Encyrtidae & Coccidae [23], GL Gopher & Lice [24], SC Seabirds & Chewing Lice [25], RP Rodents & Pinworms [26], SCF Smut Fungi & Caryophillaceus plants [27], PLML Pelican Lice ML [28] (the trees are generated through a maximum likelihood approach), PLMP Pelican Lice MP [28] (the trees are generated through a maximum parsimony approach), RH Rodents & Hantaviruses [29], PP Primates & Pinworm [30], and FD Fishs and Dactylogyrus [31].
> 

> In addition, we used a dataset of our own which corresponds to arthropod hosts and a bacterium genus, Wolbachia, living inside the cells of their hosts [32,33]. The datasets were chosen to provide a variety in terms of size of the host and parasite trees: those from the literature are relatively small (from 7 to 100 leaves), while our own data provide an example of much bigger host and parasite trees, each having 387 leaves. Moreover, we were careful that the selected datasets cover, as much as possible, a range of situations in terms of coevolution and of the expected frequencies of each event
> 

### Example Figures

From “[Visualizing Co-phylogenetic Reconciliations](https://doi.org/10.1007/978-3-319-73915-1_27)”:

![Screen Shot 2023-08-15 at 10.50.19 AM.png](Co-Phylogenetic%20Trees%202440f3927d254148abd93168c1399b43/Screen_Shot_2023-08-15_at_10.50.19_AM.png)

![Screen Shot 2023-08-15 at 10.50.09 AM.png](Co-Phylogenetic%20Trees%202440f3927d254148abd93168c1399b43/Screen_Shot_2023-08-15_at_10.50.09_AM.png)

![Screen Shot 2023-08-15 at 10.49.57 AM.png](Co-Phylogenetic%20Trees%202440f3927d254148abd93168c1399b43/Screen_Shot_2023-08-15_at_10.49.57_AM.png)

=== STOP RENDERING ===

from [Visualizing Co-phylogenetic Reconciliations](../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Visualizing%20Co-phylogenetic%20Reconciliations%20fd4b98c0071f4e96924bacd938e706b5.md) 
Eucalypt tool (Donati, B., Baudet, C., Sinaimeri, B., Crescenzi, P., Sagot, M.F.: EUCALYPT:
efficient tree reconciliation enumerator. Algorithms Mol. Biol. 10(1), 3 (2015)), trees from a bioinfromatics journal (Wieseke, N., Hartmann, T., Bernt, M., Middendorf, M.: Cophylogenetic reconcil-
iation with ILP. IEEE/ACM Trans. Comput. Biol. Bioinform. 12(6), 1227–1235
(2015))

Figure below: An HP-drawing of a reconciliation of Gopher & Lice drawn by SearchMaximalPlanar. (2) The same instance drawn by ShortenHostSwitch.

![Untitled](Co-Phylogenetic%20Trees%202440f3927d254148abd93168c1399b43/Untitled.png)

![evolu.png](Co-Phylogenetic%20Trees%202440f3927d254148abd93168c1399b43/evolu.png)