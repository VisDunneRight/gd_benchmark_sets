# A Random Sampling O(n) Force-calculation Algorithm for Graph Layouts

Citation name: gove2019
Authors: Gove, R.
Bibtex: @article{gove2019,
author = {Gove, R.},
title = {A Random Sampling O(n) Force-calculation Algorithm for Graph Layouts},
journal = {Computer Graphics Forum},
volume = {38},
number = {3},
pages = {739-751},
keywords = {CCS Concepts, • Human-centered computing → Graph drawings; Empirical studies in visualization},
doi = {https://doi.org/10.1111/cgf.13724},
url = {https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.13724},
eprint = {https://onlinelibrary.wiley.com/doi/pdf/10.1111/cgf.13724},
abstract = {Abstract This paper proposes a linear-time repulsive-force-calculation algorithm with sub-linear auxiliary space requirements, achieving an asymptotic improvement over the Barnes-Hut and Fast Multipole Method force-calculation algorithms. The algorithm, named random vertex sampling (RVS), achieves its speed by updating a random sample of vertices at each iteration, each with a random sample of repulsive forces. This paper also proposes a combination algorithm that uses RVS to derive an initial layout and then applies Barnes-Hut to refine the layout. An evaluation of RVS and the combination algorithm compares their speed and quality on 109 graphs against a Barnes-Hut layout algorithm. The RVS algorithm performs up to 6.1 times faster on the tested graphs while maintaining comparable layout quality. The combination algorithm also performs faster than Barnes-Hut, but produces layouts that are more symmetric than using RVS alone. Data and code: https://osf.io/nb7m8/},
year = {2019}
}
DOI: https://doi.org/10.1111/cgf.13724
year: 2019
Conference: EuroVis
link: https://onlinelibrary.wiley.com/doi/10.1111/cgf.13724
paper type: algorithm
Technique: force-directed
Graph feature: generic
Dataset tag clean: C. Walshaw's graph collection, Collaboration Networks, Custom (Non Replicable), Metro Maps, SNAP, Stanford GraphBase, SuiteSparse Matrix Collection
dataset size: 109
Dataset tag relations: Stanford GraphBase (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Stanford%20GraphBase%20effff4b40e9d4a79b6f33825ccca7401.md), Transportation Networks (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Transportation%20Networks%20720a658bb1914b51910c480d86943e80.md), SNAP (Stanford Network Analysis Platform) (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/SNAP%20(Stanford%20Network%20Analysis%20Platform)%201cd77eaee57147ce8263b2f9eaa2589c.md), Walshaw (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Walshaw%20e40b37a1147942d89ff1d8dfad285256.md), Assorted Collaboration Network (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Assorted%20Collaboration%20Network%206062ff126f474a50b5f3dc9b945d43da.md), Social Networks (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Social%20Networks%2090888b3285d042d49072985b05f95203.md)
Type of edit to the dataset: added/removed edges, generated, truncated
Size of graphs (Clean up): 18-143437
Easy to find info about graphs?: In Table, Text
Results measured: Angular Resolution, Crossing Angle, Num Crossings, Running Time, Shape
Evaluation type (Multi-Select): Quantitative Aggregated, Visual Comparison
Supplemental material (Multi-select): appendix
Does Provide Code: In Paper
Type of storage for supplemental material: publisher website
To review: No
Go find the datasets: No
Go hunt for citations: No
Great example: No

This evaluation uses 109 common graphs from network science and graph algorithm research (note: many graphs from older re-search are no longer available online).