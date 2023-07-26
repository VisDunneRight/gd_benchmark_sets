# Simple and Efficient Bilayer Cross Counting

Citation name: barth2002
Authors: Wilhelm Barth Petra Mutzel
Bibtex: @InProceedings{barth2002,
author="Barth, Wilhelm
and J{\"u}nger, Michael
and Mutzel, Petra",
editor="Goodrich, Michael T.
and Kobourov, Stephen G.",
title="Simple and Efficient Bilayer Cross Counting",
booktitle="Graph Drawing",
year="2002",
publisher="Springer Berlin Heidelberg",
address="Berlin, Heidelberg",
pages="130--141",
doi=”10.1007/3-540-36151-0_13”,
abstract="We consider the problem of counting the interior edge crossings when a bipartite graph G = (V,E) with node set V and edge set E is drawn such that the nodes of the two shores of the bipartition are drawn as distinct points on two parallel lines and the edges as straight line segments. The efficient solution of this problem is important in layered graph drawing. Our main observation is that it can be reduced to counting the inversions of a certain sequence. This leads to an O(∣E∣+∣C∣) algorithm, where C denotes the set of pairwise interior edge crossings, as well as to a simple O(∣E∣ log ∣Vsmall∣) algorithm, where Vsmall is the smaller cardinality node set in the bipartition of the node set V of the graph. We present the algorithms and the results of computational experiments with these and other algorithms on a large collection of instances.",
isbn="978-3-540-36151-0"
}
DOI: https://doi.org/10.1007/3-540-36151-0_13
year: 2004
Conference: JGAA
link: https://jgaa.info/accepted/2004/BarthMutzelJuenger2004.8.2.pdf
Notes: used in dagre

"Finally, we ran the algorithms on a selection of real-world graphs compiled
from the AT&T directed graph collection by Michael Kr ̈uger of the Max-Planck-
Institut f ̈ur Informatik in Saarbr ̈ucken. We used the first phase of the AGD
Sugiyama implementation in order to obtain layerings with the Longest-Path
and Coffman-Graham options from which we extracted the resulting layer pairs
as test instances. Thus, we compiled two collections of 30,061 instances and
57,300 instances, respectively. For each instance, we applied 10 random shuffles
of the northern and southern layers, each followed by a MEDIAN-ordered run
as explained above. So we ran a total of 601,220 and 1,146,000 instances of the
Longest-Path generated layer pairs and the Coffman-Graham generated layer
pairs, respectively"
paper type: algorithm
Graph feature: Bipartite, Layered graphs
Dataset tag clean: AT&T, AT&T*, Stanford GraphBase
Dataset used: AT&T
dataset size: 2000 + 1400 + 2100
Dataset tag relations: Stanford GraphBase (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Stanford%20GraphBase%20effff4b40e9d4a79b6f33825ccca7401.md), AT&T (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/AT&T%20e86f130c42344169a9d75a61abc7e487.md)
Type of edit to the dataset: rank assignment
Size of graphs (Clean up): 1000 - 500000
Size of graphs: 1000-500000
Easy to find info about graphs?: NO, Text
Results measured: Running Time
Evaluation type (Multi-Select): Quantitative Aggregated
Evaluation type: visual, aggreate
Supplemental material (Multi-select): no
Supplemental material available: no
Does Provide Code: In Paper
Type of storage for supplemental material: NA
To review: No
Go find the datasets: No
Go hunt for citations: No
Great example: No