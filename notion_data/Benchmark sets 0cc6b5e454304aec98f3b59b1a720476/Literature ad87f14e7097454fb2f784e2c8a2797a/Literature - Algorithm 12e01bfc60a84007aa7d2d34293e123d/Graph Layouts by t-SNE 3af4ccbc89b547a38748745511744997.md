# Graph Layouts by t-SNE

Citation name: kruiger2017
Authors: Kruiger, J. F. and Rauber, P. E. and Martins, R. M. and Kerren, A. and Kobourov, S. and Telea, A. C.
Bibtex: @article{kruiger2017,
author = {Kruiger, J. F. and Rauber, P. E. and Martins, R. M. and Kerren, A. and Kobourov, S. and Telea, A. C.},
title = {Graph Layouts by t-SNE},
journal = {Computer Graphics Forum},
volume = {36},
number = {3},
pages = {283-294},
doi = {https://doi.org/10.1111/cgf.13187},
url = {https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.13187},
eprint = {https://onlinelibrary.wiley.com/doi/pdf/10.1111/cgf.13187},
abstract = {Abstract We propose a new graph layout method based on a modification of the t-distributed Stochastic Neighbor Embedding (t-SNE) dimensionality reduction technique. Although t-SNE is one of the best techniques for visualizing high-dimensional data as 2D scatterplots, t-SNE has not been used in the context of classical graph layout. We propose a new graph layout method, tsNET, based on representing a graph with a distance matrix, which together with a modified t-SNE cost function results in desirable layouts. We evaluate our method by a formal comparison with state-of-the-art methods, both visually and via established quality metrics on a comprehensive benchmark, containing real-world and synthetic graphs. As evidenced by the quality metrics and visual inspection, tsNET produces excellent layouts.},
year = {2017}
}
DOI: https://doi.org/10.1111/cgf.13187
Year: 2017
Conference: EuroVis
link: http://www2.cs.arizona.edu/~kobourov/tsne-eurovis17.pdf
Notes: Great example for dataset description with sources and properties

Matrices: https://www.cise.ufl.edu/research/sparse/matrices/Rajat/rajat11.html

Sparse matrix test problems:
https://dl.acm.org/doi/10.1145/62038.62043

Some graphs created with the graph tool python library: https://graph-tool.skewed.de/
paper type: algorithm, comparison
Technique: multidimensional scaling
Graph feature: clusters (generated), generic, planar, spatial
Dataset tag clean: Collaboration Networks, Stanford GraphBase, SuiteSparse Matrix Collection
dataset size: 20
Dataset tag relations: SuiteSparse Matrix Collection (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/SuiteSparse%20Matrix%20Collection%20b8772d6a2cbb456894b4673e32c6f956.md), Stanford GraphBase (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Stanford%20GraphBase%20effff4b40e9d4a79b6f33825ccca7401.md)
Type of edit to the dataset: NA
Size of graphs (Clean up): 72 - 4941
Easy to find info about graphs?: In Table
Results measured: Neighborhood Preservation, Running Time, Stress
Evaluation type (Multi-Select): Quantitative Individual, Visual Comparison
Supplemental material (Multi-select): Yes
Does Provide Code: External Link
Type of storage for supplemental material: Github
To review: No
Go find the datasets: Yes
Go hunt for citations: Yes
Great example: Yes
Dataset names: 3elt (C. Walshaw - Sparse Matrix), CA-GrQx, EVA, bcsstk09 (C. Walshaw), block_2000, cage8, can_96, dwt_1005, dwt_419, dwt_72, grid17, jazz, lesmis (SparseMatrix - Stanford GraphBase), mesh3e1, netscience, price1000, rajat11, sierpinski3d, us_powergrid (Sparse Matrix), visbrazil
Related to Benchmark datasets (Related to Literature - Algorithm (Dataset tag relations) 1): SuiteSparse Matrix Collection (../../Existing%20benchmark%20datasets%20(1)%204e6ac4f7a1004e179b2efe7128ee12b8/Benchmark%20datasets%20fff01d52e4ad81ae9875ec4733f4a970/SuiteSparse%20Matrix%20Collection%20fff01d52e4ad81448874dfe4b2fdc1f8.md), Stanford GraphBase (../../Existing%20benchmark%20datasets%20(1)%204e6ac4f7a1004e179b2efe7128ee12b8/Benchmark%20datasets%20fff01d52e4ad81ae9875ec4733f4a970/Stanford%20GraphBase%20fff01d52e4ad8183a7bfd55bda2ff06e.md)
Related to Benchmark datasets (Related to Literature - Algorithm (Dataset tag relations) 1) 1: SuiteSparse Matrix Collection (../../Existing%20benchmark%20datasets%20(1)%20d774ccc4903946489c8369c319381d05/Benchmark%20datasets%20fff01d52e4ad81298f4dcb2af7a126a8/SuiteSparse%20Matrix%20Collection%20fff01d52e4ad8166bd8dd2b5cef82c74.md), Stanford GraphBase (../../Existing%20benchmark%20datasets%20(1)%20d774ccc4903946489c8369c319381d05/Benchmark%20datasets%20fff01d52e4ad81298f4dcb2af7a126a8/Stanford%20GraphBase%20fff01d52e4ad81b78740d6eb034c59f4.md)

![Untitled](Graph%20Layouts%20by%20t-SNE%203af4ccbc89b547a38748745511744997/Untitled.png)