# World Bank Trade Data

Origin Notes: Bilateral trade value in 1999 (total imports+exports), from https://wits.worldbank.org/module/ALL/sub-module/ALL/reporter/ALL/year/ALL/tradeflow/ALL/pagesize/50/page/1.
graph features handled: Categorical nodes, Dense
Graph features in papers: clusters (generated),generic,generic,large
Origin Paper: The WTO promotes trade, strongly but unevenly (https://www.notion.so/The-WTO-promotes-trade-strongly-but-unevenly-fff01d52e4ad81429cd3e8d463c14784?pvs=21)
Originally found at: https://wits.worldbank.org/module/ALL/sub-module/ALL/reporter/ALL/year/ALL/tradeflow/ALL/pagesize/50/page/1
Size: 194 nodes, 10,080 edges
Number of Graphs: 1
Appeared in years: 2006,2015
Type of Collection: Single Graph
is it stored properly?: No
must be analyzed: No
In repo?: Yes
Related to Literature - Algorithm (1) (Dataset tag relations): Energy Models for Graph Clustering (https://www.notion.so/Energy-Models-for-Graph-Clustering-650b53a4f2f8488f9e5eab77f118aefe?pvs=21), Untangling the Hairballs of Multi-Centered Small-World Online Social Media Networks (https://www.notion.so/Untangling-the-Hairballs-of-Multi-Centered-Small-World-Online-Social-Media-Networks-8d6315c26f82480cb56a0256ef7ec569?pvs=21)
cleaned format?: Yes
duplicate?: No
link works?: No
Added in paper: No
OSF link json: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d90e390c2b4d0d2e386256
Origin paper plaintext: The WTO promotes trade, strongly but unevenly
Page id: fff01d52e4ad81789e69c60438939e50
unavailable/skip: No
Cleaned ALL data: No
OSF link gexf: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d949494cf7481075055615
OSF link gml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d96d610c2b4d0f6438622a
OSF link graphml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d970654cf748115a0557d4
first look: No
sparkline data: {'min': 6, 'max': 192, 'step_size': 10, 'num_bins': 20, 'bins': [0, 10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 110, 120, 130, 140, 150, 160, 170, 180, 190], 'node_degree': [1, 0, 4, 9, 9, 16, 20, 17, 21, 10, 9, 11, 10, 5, 5, 8, 5, 7, 15, 12]}
Related to Literature - Algorithm (Dataset tag relations) 1: Energy Models for Graph Clustering (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Energy%20Models%20for%20Graph%20Clustering%20b2b82813b6124d1fbd17b1e84e8043fe.md), Untangling the Hairballs of Multi-Centered Small-World Online Social Media Networks (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Untangling%20the%20Hairballs%20of%20Multi-Centered%20Small-W%20690af12a963849cd80c0285d27221086.md)

# Body

### Statistics

![degree_distr.svg](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/World%20Bank%20Trade%20Data%20e6e54a00bc574c639cfa165458c71232/degree_distr.svg)

### Descriptions from Literature

From “[Energy Models for Graph Clustering](https://doi.org/10.1007/978-3-540-24595-7_40)”:

> The difference between conventional energy models, node-repulsion LinLog, and edge-repulsion LinLog can be illustrated with a model of the trade between ten North American and European countries. The nodes of the graph correspond to the countries, and the edge weights specify the trade volume between each pair of countries. Because of geographical closeness and free trade agreements, countries on the same continent trade more intensively than countries on different continents. Figure 1 shows the minimum energy layouts of the trade graph for the three force and energy models. The layout of the widely used Fruchterman-Reingold model [20] does not show any clear groups at all. The layout of the node-repulsion LinLog energy model groups the countries (nodes) primarily according to their total trade volume (degree). Only the layout of the edge-repulsion LinLog energy model shows the expected grouping according to continents.
> 

### Example Figures

From “[Untangling the Hairballs of Multi-Centered Small-World Online Social Media Networks](https://doi.org/10.7155/jgaa.00370)”:

![Screen Shot 2023-08-17 at 5.17.54 PM.png](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/World%20Bank%20Trade%20Data%20e6e54a00bc574c639cfa165458c71232/Screen_Shot_2023-08-17_at_5.17.54_PM.png)

From “[Energy Models for Graph Clustering](https://doi.org/10.1007/978-3-540-24595-7_40)”:

![Screen Shot 2023-08-17 at 5.13.41 PM.png](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/World%20Bank%20Trade%20Data%20e6e54a00bc574c639cfa165458c71232/Screen_Shot_2023-08-17_at_5.13.41_PM.png)

=== STOP RENDERING ===

world bank: [www.worldbank.org](http://www.worldbank.org/)