# ChordLink: A New Hybrid Visualization Model0

Citation name: Angori2019
Authors: Lorenzo Angori and Walter Didimo and Fabrizio Montecchiani and Daniele Pagliuca and Alessandra Tappini
Bibtex: @incollection{Angori2019,
doi = {10.1007/978-3-030-35802-0_22},
url = {https://doi.org/10.1007/978-3-030-35802-0_22},
year = {2019},
publisher = {Springer International Publishing},
pages = {276--290},
author = {Lorenzo Angori and Walter Didimo and Fabrizio Montecchiani and Daniele Pagliuca and Alessandra Tappini},
title = {{ChordLink}: A New Hybrid Visualization Model},
booktitle = {Lecture Notes in Computer Science}
}
DOI: https://doi.org/10.1007/978-3-030-35802-0_22
Year: 2019
Conference: GD
link: https://link.springer.com/content/pdf/10.1007/978-3-030-35802-0_22.pdf
Notes: turns very-highly connected regions into chord-link diagrams
paper type: algorithm
Technique: force-directed
Graph feature: categorical nodes, high degree, labeled nodes
Dataset tag clean: Collaboration Networks, Fiscal Network
Dataset used: DBLP + Italian Revenue Agency
dataset size: 2
Dataset tag relations: Assorted Collaboration Network (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Assorted%20Collaboration%20Network%206062ff126f474a50b5f3dc9b945d43da.md), Assorted Fiscal Network (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Assorted%20Fiscal%20Network%206610534d6d3b48c5a119b04659153258.md)
Type of edit to the dataset: truncated
Size of graphs (Clean up): 174 - 1766
Size of graphs: 174 nodes, 200 edges (italian revenue agency) + 1766 nodes and 3780 edges (dblp)
Easy to find info about graphs?: In Table
Results measured: Observations
Evaluation type (Multi-Select): Case Study
Evaluation type: case study
Supplemental material (Multi-select): video
Supplemental material available: video on youtube - they say they implemented it but it’s nowhere to be found, no links in the body of the paper, and no code
Does Provide Code: No
Type of storage for supplemental material: external website - not their own
To review: No
Go find the datasets: No
Go hunt for citations: No
Great example: No
Related to Benchmark datasets (Related to Literature - Algorithm (Dataset tag relations) 1): Assorted Fiscal Network (../../Existing%20benchmark%20datasets%20(1)%204e6ac4f7a1004e179b2efe7128ee12b8/Benchmark%20datasets%20fff01d52e4ad81ae9875ec4733f4a970/Assorted%20Fiscal%20Network%20fff01d52e4ad819786dfdd257896fb5a.md), Assorted Collaboration Network (../../Existing%20benchmark%20datasets%20(1)%204e6ac4f7a1004e179b2efe7128ee12b8/Benchmark%20datasets%20fff01d52e4ad81ae9875ec4733f4a970/Assorted%20Collaboration%20Network%20fff01d52e4ad81c6b058fa7c75c14808.md)
Related to Benchmark datasets (Related to Literature - Algorithm (Dataset tag relations) 1) 1: Assorted Fiscal Network (../../Existing%20benchmark%20datasets%20(1)%20d774ccc4903946489c8369c319381d05/Benchmark%20datasets%20fff01d52e4ad81298f4dcb2af7a126a8/Assorted%20Fiscal%20Network%20fff01d52e4ad81958855e0764c23d32f.md), Assorted Collaboration Network (../../Existing%20benchmark%20datasets%20(1)%20d774ccc4903946489c8369c319381d05/Benchmark%20datasets%20fff01d52e4ad81298f4dcb2af7a126a8/Assorted%20Collaboration%20Network%20fff01d52e4ad81e6ade9eb25f7da3f5f.md)

We performed the query “network AND visualization” and limited to 500 the

number of search results (i.e., publications) to be returned. The resulting net-

work consists of 1766 nodes, 3780 edges, and 382 connected components. The

largest of these components contains 118 nodes and 322 edges. A ChordLink

visualization of this component is shown in Fig. 5, where several dense portions

of the original node-link layout have been identified as communities. To make the

diagram easier to read, some communities (on the left side) have been expanded

and some others (on the right side) have been collapsed. We now discuss some

findings that involve tasks (T1) and (T2) in an interleaved manner.