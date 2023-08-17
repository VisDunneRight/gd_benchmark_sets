# Biological Pathways (KEGG)

Note: The pathway data is separated by module, but the individual modules can be combined into a large graph as visualized at https://www.kegg.jp/kegg-bin/show_pathway?map01100
Origin Notes: According to https://www.kegg.jp/kegg-bin/show_pathway?map01100, “the KEGG PATHWAY database is a collection of manually drawn graphical diagrams, called KEGG pathway maps, for metabolic pathways, signaling pathways, pathways involved in various cellular processes and organismal systems, and perturbed pathways associated with human diseases.”
graph features handled: clusters, directed edges, large, partition
Graph features in papers: categorical nodes,clusters (pre-existing),labeled nodes
Originally found at: https://www.kegg.jp/kegg/pathway.html#global
Size: 47-292 nodes, 41-327 edges
Number of Graphs: 13
Origin Paper: KEGG: Kyoto Encyclopedia of Genes and Genomes (https://www.notion.so/KEGG-Kyoto-Encyclopedia-of-Genes-and-Genomes-328d3a813a174805a37121dd63678b4d?pvs=21)
Appeared in years: 2020
Type of Collection: Uniform Benchmark
is it stored properly?: No
must be analyzed: No
In repo?: Yes
Related to Literature - Algorithm (1) (Dataset tag relations): Multi-Level Area Balancing of Clustered Graphs (https://www.notion.so/Multi-Level-Area-Balancing-of-Clustered-Graphs-2d16323782f343ddbe5829efec909c74?pvs=21)
cleaned format?: Yes
duplicate?: No
link works?: No
Added in paper: No
OSF link json: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d90e80803e0c0b04558c14
Origin paper plaintext: KEGG: Kyoto Encyclopedia of Genes and Genomes
Page id: 6d302b16e7af4982a57c5b9aeecfe3b8
unavailable/skip: No
Cleaned ALL data: No
Related to Literature - Algorithm (Dataset tag relations) 1: Multi-Level Area Balancing of Clustered Graphs (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Multi-Level%20Area%20Balancing%20of%20Clustered%20Graphs%201a25e529913b49e2acf235d5f3ec89bb.md)
OSF link gexf: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d948fe803e0c0c0c558b95
OSF link gml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d96d6e1101aa0ea76a0be4
OSF link graphml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d970ab4cf748115a055802
first look: No
sparkline data: {'min': 47, 'max': 292, 'step_size': 50, 'num_bins': 6, 'bins': [0, 50, 100, 150, 200, 250], 'num_nodes': [2, 2, 3, 2, 2, 2]}

# Body

### Statistics

![four_in_one.svg](Biological%20Pathways%20(KEGG)%206d302b16e7af4982a57c5b9aeecfe3b8/four_in_one.svg)

### Descriptions from Literature

From “[Multi-Level Area Balancing of Clustered Graphs](https://doi.org/10.1109/TVCG.2020.3038154)”:

> KEGG Overview Pathway. Fig. 6 is the result of reproducing the KEGG overview pathway map using our approach. The color coding of the category here is directly retrieved from the original KEGG database [43], as similarly incorporated in Metabopolis [64] (see figures in supplementary materials, available online). We also set the same threshold for specifying unimportant vertices as in Metabopolis, so that readers can refer to the paper for comparison (Fig. 6). The advantage of this technique allows us to arrange the vertexts in a balanced fashion by pushing vertexts away from each other. This initially gives users an idea of how big each category is, and explicitly shows which reaction is classified under which category. Users can also identify sub-components effectively since those components with identical topological structures are aligned as neighbors. This also helps users to comprehend which structures are associated with certain types of pathways, such as small chains, stars, etc.
> 

### Example Figures

From “[Multi-Level Area Balancing of Clustered Graphs](https://doi.org/10.1109/TVCG.2020.3038154)”:

![Screen Shot 2023-01-25 at 10.50.53 AM.png](Biological%20Pathways%20(KEGG)%206d302b16e7af4982a57c5b9aeecfe3b8/Screen_Shot_2023-01-25_at_10.50.53_AM.png)

=== STOP RENDERING ===

![Screen Shot 2023-01-25 at 10.52.55 AM.png](Biological%20Pathways%20(KEGG)%206d302b16e7af4982a57c5b9aeecfe3b8/Screen_Shot_2023-01-25_at_10.52.55_AM.png)

![Untitled](Biological%20Pathways%20(KEGG)%206d302b16e7af4982a57c5b9aeecfe3b8/Untitled.png)