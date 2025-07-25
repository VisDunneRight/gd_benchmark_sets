# California

Note: Data contains links related to an online search of the word “California” as nodes.
Origin Notes: We found this dataset on the webpage of a 2002 computer science course at Cornell, instructed by Jon Kleinberg. The original name was Pages that match the word “California”. They mention how the data was queried from a search engine, and that many of the original links are broken.  It is not clear whether Kleinberg collected the data, or compiled it for the course.
graph features handled: Clusters (generated), Large
Graph features in papers: clusters (generated),generic,large,generic,large
Origin Paper: The Structure of Information Networks (https://www.notion.so/The-Structure-of-Information-Networks-fff01d52e4ad81afbfdbc3e767e57e6a?pvs=21)
Originally found at: https://www.cs.cornell.edu/courses/cs685/2002fa/data/gr0.California
Size: 4772 nodes, 8965 edges
format: first character determines node or edge (n/e). For nodes, we then have node id and the link of the webpage. For edges we have two node ids. 

n 1 www.link.com
…
e 1 200
Appeared in years: 2008
Type of Collection: Single Graph
is it stored properly?: No
must be analyzed: No
In repo?: Yes
Related to Literature - Algorithm (1) (Dataset tag relations): A Treemap Based Method for Rapid Layout of Large Graphs (https://www.notion.so/A-Treemap-Based-Method-for-Rapid-Layout-of-Large-Graphs-7d9e14d48d9e452da4fcf8b64b007ea5?pvs=21), Rapid Graph Layout Using Space Filling Curves (https://www.notion.so/Rapid-Graph-Layout-Using-Space-Filling-Curves-847c46047b5c400bb9dcf339c8d42f12?pvs=21)
cleaned format?: Yes
duplicate?: No
link works?: Yes
Added in paper: No
OSF link json: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d90e48803e0c0b00558baa
Origin paper plaintext: The Structure of Information Networks
Page id: fff01d52e4ad81e5aa98cbb9c7a51b4b
unavailable/skip: No
Cleaned ALL data: No
OSF link gexf: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d9492e803e0c0c0f558b9d
OSF link gml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d94da70c2b4d0ea138634b
OSF link graphml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d9700094a6be112912e9a5
first look: Yes
sparkline data: {'min': 0, 'max': 175, 'step_size': 10, 'num_bins': 18, 'bins': [0, 10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 110, 120, 130, 140, 150, 160, 170], 'node_degree': [4401, 246, 54, 20, 17, 5, 7, 4, 4, 2, 1, 0, 5, 2, 1, 0, 1, 2]}
Related to Literature - Algorithm (Dataset tag relations) 1: A Treemap Based Method for Rapid Layout of Large Graphs (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/A%20Treemap%20Based%20Method%20for%20Rapid%20Layout%20of%20Large%20G%20f96d2a808a5f4df2a781d9a890e2b266.md), Rapid Graph Layout Using Space Filling Curves (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Rapid%20Graph%20Layout%20Using%20Space%20Filling%20Curves%2010601cd6078a4ea18b17c7d40eda0041.md)

# Body

### Statistics

![degree_distr.svg](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/California%20e0a841bc57c045b5a8514110cfe85635/degree_distr.svg)

### Descriptions from Literature

From [“A Treemap Based Method for Rapid Layout of Large Graphs](https://ieeexplore.ieee.org/document/4475481)”:

> This particular graph is a non-weighted graph of links between search results for the word “California” (also in Figures 6, 8, and 9, |V|=6107,|E|=15160).
> 

From “[Rapid Graph Layout Using Space Filling Curves](https://ieeexplore.ieee.org/document/4658143)”:

> The “california” dataset (shown in Figures 5 and 8) consists of the links between the webpages found from a search for the word 'California' [4].
> 

### Example Figures

From [“A Treemap Based Method for Rapid Layout of Large Graphs](https://ieeexplore.ieee.org/document/4475481)”:

![Untitled](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/California%20e0a841bc57c045b5a8514110cfe85635/Untitled.png)

**Fig. 1.** *A graph laid out using our treemap based approach*. This graph portrays the links between websites that came from a search on the word “California” [7]. Nodes are clustered into a hierarchy, and laid out by applying a treemap to this hierarchy. Levels of the hierarchy below a threshold are clustered together into larger nodes. It can very easily be seen that there are three primary groups of websites that link to each other, and a plethora of others that are not as tightly linked.

From “[Rapid Graph Layout Using Space Filling Curves](https://ieeexplore.ieee.org/document/4658143)”:

![Untitled](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/California%20e0a841bc57c045b5a8514110cfe85635/Untitled%201.png)

**Fig. 5** *Separating clusters.* By adjusting the spacing between nodes according to the clustering information, clusters can be separated.

== STOP RENDERING ==

[https://www.cs.cornell.edu/courses/cs685/2002fa/data/gr0.California](https://www.cs.cornell.edu/courses/cs685/2002fa/data/gr0.California)