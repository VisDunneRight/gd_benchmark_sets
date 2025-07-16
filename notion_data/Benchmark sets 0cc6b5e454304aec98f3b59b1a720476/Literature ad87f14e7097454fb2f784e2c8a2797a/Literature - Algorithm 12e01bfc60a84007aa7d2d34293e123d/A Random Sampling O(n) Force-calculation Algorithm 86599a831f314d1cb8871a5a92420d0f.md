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
Year: 2019
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
Related to Benchmark datasets (Related to Literature - Algorithm (Dataset tag relations) 1): Social Networks (../../Existing%20benchmark%20datasets%20(1)%204e6ac4f7a1004e179b2efe7128ee12b8/Benchmark%20datasets%20fff01d52e4ad81ae9875ec4733f4a970/Social%20Networks%20fff01d52e4ad811e963fc9641224bac2.md), Walshaw (../../Existing%20benchmark%20datasets%20(1)%204e6ac4f7a1004e179b2efe7128ee12b8/Benchmark%20datasets%20fff01d52e4ad81ae9875ec4733f4a970/Walshaw%20fff01d52e4ad8147a31cf6fd707eae88.md), Stanford GraphBase (../../Existing%20benchmark%20datasets%20(1)%204e6ac4f7a1004e179b2efe7128ee12b8/Benchmark%20datasets%20fff01d52e4ad81ae9875ec4733f4a970/Stanford%20GraphBase%20fff01d52e4ad8183a7bfd55bda2ff06e.md), SNAP (Stanford Network Analysis Platform) (../../Existing%20benchmark%20datasets%20(1)%204e6ac4f7a1004e179b2efe7128ee12b8/Benchmark%20datasets%20fff01d52e4ad81ae9875ec4733f4a970/SNAP%20(Stanford%20Network%20Analysis%20Platform)%20fff01d52e4ad81bba7fdd4700e69d4e8.md), Assorted Collaboration Network (../../Existing%20benchmark%20datasets%20(1)%204e6ac4f7a1004e179b2efe7128ee12b8/Benchmark%20datasets%20fff01d52e4ad81ae9875ec4733f4a970/Assorted%20Collaboration%20Network%20fff01d52e4ad81c6b058fa7c75c14808.md), Transportation Networks (../../Existing%20benchmark%20datasets%20(1)%204e6ac4f7a1004e179b2efe7128ee12b8/Benchmark%20datasets%20fff01d52e4ad81ae9875ec4733f4a970/Transportation%20Networks%20fff01d52e4ad81db96f7d31c609dfe72.md)
Related to Benchmark datasets (Related to Literature - Algorithm (Dataset tag relations) 1) 1: Walshaw (../../Existing%20benchmark%20datasets%20(1)%20d774ccc4903946489c8369c319381d05/Benchmark%20datasets%20fff01d52e4ad81298f4dcb2af7a126a8/Walshaw%20fff01d52e4ad813a8b96dd3fbfc68ad8.md), Transportation Networks (../../Existing%20benchmark%20datasets%20(1)%20d774ccc4903946489c8369c319381d05/Benchmark%20datasets%20fff01d52e4ad81298f4dcb2af7a126a8/Transportation%20Networks%20fff01d52e4ad81af890bc92a14aee5c0.md), Stanford GraphBase (../../Existing%20benchmark%20datasets%20(1)%20d774ccc4903946489c8369c319381d05/Benchmark%20datasets%20fff01d52e4ad81298f4dcb2af7a126a8/Stanford%20GraphBase%20fff01d52e4ad81b78740d6eb034c59f4.md), Assorted Collaboration Network (../../Existing%20benchmark%20datasets%20(1)%20d774ccc4903946489c8369c319381d05/Benchmark%20datasets%20fff01d52e4ad81298f4dcb2af7a126a8/Assorted%20Collaboration%20Network%20fff01d52e4ad81e6ade9eb25f7da3f5f.md), Social Networks (../../Existing%20benchmark%20datasets%20(1)%20d774ccc4903946489c8369c319381d05/Benchmark%20datasets%20fff01d52e4ad81298f4dcb2af7a126a8/Social%20Networks%20fff01d52e4ad81e78e2efb90274be5f4.md), SNAP (Stanford Network Analysis Platform) (../../Existing%20benchmark%20datasets%20(1)%20d774ccc4903946489c8369c319381d05/Benchmark%20datasets%20fff01d52e4ad81298f4dcb2af7a126a8/SNAP%20(Stanford%20Network%20Analysis%20Platform)%20fff01d52e4ad81f0bc11d53cc1f769cb.md)

This evaluation uses 109 common graphs from network science and graph algorithm research (note: many graphs from older re-search are no longer available online).