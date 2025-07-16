# Pajek

Note: Pajek means spider in Slovenian.
Origin Notes: The Pajek Program for Large Network Analysis is a tool developed and hosted by Andrej Vlado and some of their colleges. As part of this program, they later compiled relevant graphs and links to other datasets, which we call today the Pajek collection.
graph features handled: Directed edges, Generic, Large
Graph features in papers: clusters (generated),generic,clusters (generated)
Origin Paper: Pajek datasets (https://www.notion.so/Pajek-datasets-fff01d52e4ad81c1a6bceecb428c606c?pvs=21)
Originally found at: http://vlado.fmf.uni-lj.si/pub/networks/data/
Child collections: SuiteSparse Matrix Collection (SuiteSparse%20Matrix%20Collection%20fff01d52e4ad81448874dfe4b2fdc1f8.md)
Appeared in years: 2006,2019
Type of Collection: Established Network Repo (No report)
is it stored properly?: No
must be analyzed: No
In repo?: No
Related to Literature - Algorithm (1) (Dataset tag relations): A Quality Metric for Visualization of Clusters in Graphs (https://www.notion.so/A-Quality-Metric-for-Visualization-of-Clusters-in-Graphs-4f55f6f5086243d4bcda73e4aa3e2454?pvs=21), Energy Models for Graph Clustering (https://www.notion.so/Energy-Models-for-Graph-Clustering-650b53a4f2f8488f9e5eab77f118aefe?pvs=21)
cleaned format?: No
duplicate?: No
link works?: Yes
Added in paper: No
Origin paper plaintext: Pajek datasets
Page id: fff01d52e4ad81d58362f0edd2cf7dc4
unavailable/skip: Yes
Cleaned ALL data: No
first look: No
Related to Literature - Algorithm (Dataset tag relations) 1: Energy Models for Graph Clustering (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Energy%20Models%20for%20Graph%20Clustering%20b2b82813b6124d1fbd17b1e84e8043fe.md), A Quality Metric for Visualization of Clusters in Graphs (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/A%20Quality%20Metric%20for%20Visualization%20of%20Clusters%20in%20%20a1c61d2b87b4457ca462ce04f80b4720.md)

# Body

### Descriptions from Literature

From “[Energy Models for Graph Clustering](https://doi.org/10.1007/978-3-540-24595-7_40)”:

> **Airline Routing (Figure 5):** The nodes of this graph represent US airports, and the (unweighted) edges represent direct flights. The probability that two airports are connected by a direct flight is strongly related to their geographical distance: Most direct flights are relatively short, and only few large hub airports are connected by direct long-range flights.
The distances in the edge-repulsion LinLog layout resemble the relative geographical distances of the airports remarkably closely, given that the graph does not contain any explicit information about geographical distances.
> 

> **Dictionary (Figure 7):** The nodes represent terms in the Online Dictionary of Library and Information Science (ODLIS), and the edges represent hyperlinks. A hyperlink between two terms exists if one term is used to describe the meaning of the other term, and thus connects semantically related terms.
The edge-repulsion LinLog layout indeed groups semantically related terms, which is better reflected in the VRML file on the supplementary web page than in Figure 7(c). Such a grouping is useful, for example, for discovering the global topic areas (like publishing, printing, information technology, etc.), for identifying entry points for the exploration of topics, or for finding semantically
related terms even if they are not explicitly linked.
> 

From “[A Quality Metric for Visualization of Clusters in Graphs](https://link.springer.com/chapter/10.1007/978-3-030-35802-0_10)”:

> We re-used some datasets from the validation experiments and created some new ones, listed in Table [2](https://link.springer.com/chapter/10.1007/978-3-030-35802-0_10#Tab2). We also selected real world graph datasets with existing vertex categorization, which are listed under the double line in Table [2](https://link.springer.com/chapter/10.1007/978-3-030-35802-0_10#Tab2). The datasets were taken from Pajek [[2](https://link.springer.com/chapter/10.1007/978-3-030-35802-0_10#ref-CR2)] and Stanford Network Analysis Project’s (SNAP) repository [[23](https://link.springer.com/chapter/10.1007/978-3-030-35802-0_10#ref-CR23), [40](https://link.springer.com/chapter/10.1007/978-3-030-35802-0_10#ref-CR40)].
> 

### Example Figures

From “[Energy Models for Graph Clustering](https://doi.org/10.1007/978-3-540-24595-7_40)”:

![Screen Shot 2023-08-17 at 4.05.25 PM.png](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Pajek%20e323e05a735d4151a0bccfec08aa3bd6/Screen_Shot_2023-08-17_at_4.05.25_PM.png)

![Screen Shot 2023-08-17 at 4.06.19 PM.png](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Pajek%20e323e05a735d4151a0bccfec08aa3bd6/Screen_Shot_2023-08-17_at_4.06.19_PM.png)

=== STOP RENDERING ===

[http://vlado.fmf.uni-lj.si/pub/networks/data/](http://vlado.fmf.uni-lj.si/pub/networks/data/)

Direct flights between US airports (332 nodes, 2126 edges). Some

distant airports in Alaska and the South Sea (e.g. Guam) are omitted to improve

readability.

[](http://vlado.fmf.uni-lj.si/pub/networks/doc/)

Collection of other dataset that might not be linked into paper

There is another link to data not mentioned in their repo. (Also part of SuiteSpase Matrix Collection)