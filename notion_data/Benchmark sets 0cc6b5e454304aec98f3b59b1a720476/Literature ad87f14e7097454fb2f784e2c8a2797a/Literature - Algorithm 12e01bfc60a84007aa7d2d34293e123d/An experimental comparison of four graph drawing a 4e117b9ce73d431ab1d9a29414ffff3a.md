# An experimental comparison of four graph drawing algorithms

Citation name: DiBattista1997b
Authors: Giuseppe Di Battista and Ashim Garg and Giuseppe Liotta and Roberto Tamassia  and Emanuele Tassinari  and Francesco Vargiu
Bibtex: @article{DiBattista1997b,
doi = {10.1016/s0925-7721(96)00005-3},
url = {https://doi.org/10.1016/s0925-7721(96)00005-3},
year = {1997},
month = apr,
publisher = {Elsevier {BV}},
volume = {7},
number = {5-6},
pages = {303--325},
author = {Giuseppe Di Battista and Ashim Garg and Giuseppe Liotta and Roberto Tamassia and Emanuele Tassinari and Francesco Vargiu},
title = {An experimental comparison of four graph drawing algorithms},
journal = {Computational Geometry}
}
DOI: https://doi.org/10.1016/S0925-7721(96)00005-3
Year: 1997
Conference: Computational Geometry
Notes: Origin of Rome-Lib

Our test graph generation strategy is as follows. First, we have focused on the important application area of database and software visualization, where Entity-Relationship diagrams and Data-Flow
diagrams are usually displayed with orthogonal drawings.
Second, we have collected 112 "real life" graphs with number of vertices between 10 and 100, from now on called core graphs, from the following sources:
• 54% of the graphs have been obtained from major Italian software companies (especially from Database Informatica) and large government organization (including the Italian Internal Revenue
Service and the Italian National Advisory Council for Computer Applications in the Government (Autorit?z per l'Informatica nella Pubblica Amministrazione));
• 33% of the graphs were taken from well-known reference books in software engineering [18] and database design [1], and from journal articles on software visualization in the recent issues of
Information Systems and the IEEE Transactions on Software Engineering;
• 13% of the graphs were extracted from theses in software and database visualization written by students at the University of Rome "La Sapienza".

Our approach is based on the following scheme. We defined several primitive operations for updating
graphs, which correspond to the typical operations performed by designers of Entity-Relationship and
Data-Flow Diagrams, and attributed a certain probability to each of them. More specifically, the
updating primitives we have used are the following: InsertEdge, which inserts a new edge between
two existing vertices; DeleteEdge,which deletes an existing edge; InsertVertex,which splits an existing
edge into two edges by inserting a new vertex; DeleteVertex,which deletes a vertex and all its incident
edges; and MakeVertex, which creates a new vertex and connects it to a subset of vertices.
The test graphs were then generated in several iterations starting from the core graphs by applying
random sequences of operations with a "genetic" mechanism. Namely, at each iteration a new set of
test graphs was obtained by applying a random sequence of operations to the current test set. Each
new graph was then evaluated for "suitability", and those found not suitable were discarded. The
probability of each primitive operation was varied at the end of each iteration.
The evaluation of the suitability of the generated graphs was conducted using both objective and
subjective analyses. The objective analysis consisted of determining whether the new graph had similar
structural properties with respect to the core graph it was derived from. We have taken into account
parameters like the average ratio between number of vertices and number of edges and the average
number of biconnected components. The subjective analysis consisted in a visual inspection of the
new graph and an assessment by expert users of Entity-Relationship and Data-Flow diagrams of its
similarity to a "real-life" diagram. For obvious reasons, the subjective analysis has been done on a
randomly selected subset of the graphs.
paper type: algorithm, comparison
Graph feature: generic
Dataset tag clean: Custom (Replicable), Rome-Lib
Dataset used: Rome-Lib
dataset size: 11582 + 112
Dataset tag relations: Rome-Lib (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Rome-Lib%20c2f20984de724f4c89764b0bc494e99e.md)
Type of edit to the dataset: NA
Size of graphs (Clean up): 10 - 100
Size of graphs: 10-100
Easy to find info about graphs?: In Figure, Text
Results measured: Area, Aspect Ratio, Edge Bends, Edge Length, Num Crossings
Results measured comment: Total and max version of edge bends and edge length
Evaluation type (Multi-Select): Quantitative Aggregated
Evaluation type: aggregate, visual
Supplemental material (Multi-select): Data
Supplemental material available: No
Does Provide Code: No
Type of storage for supplemental material: external website - not their own
To review: No
Go find the datasets: No
Go hunt for citations: No
Great example: No
Related to Benchmark datasets (Related to Literature - Algorithm (Dataset tag relations) 1): Rome-Lib (../../Existing%20benchmark%20datasets%20(1)%204e6ac4f7a1004e179b2efe7128ee12b8/Benchmark%20datasets%20fff01d52e4ad81ae9875ec4733f4a970/Rome-Lib%20fff01d52e4ad81aba440e2480769b62a.md)
Related to Benchmark datasets (Related to Literature - Algorithm (Dataset tag relations) 1) 1: Rome-Lib (../../Existing%20benchmark%20datasets%20(1)%20d774ccc4903946489c8369c319381d05/Benchmark%20datasets%20fff01d52e4ad81298f4dcb2af7a126a8/Rome-Lib%20fff01d52e4ad81c6a9f8ecb881634ab6.md)

![Untitled](An%20experimental%20comparison%20of%20four%20graph%20drawing%20a%204e117b9ce73d431ab1d9a29414ffff3a/Untitled.png)