# Aesthetic Discrimination of Graph Layouts

Citation name: klammler2018
Authors: Moritz Klammler and Tamara Mchedlidze and Alexey Pak
Bibtex: @InProceedings{klammler2018,
author="Klammler, Moritz
and Mchedlidze, Tamara
and Pak, Alexey",
editor="Biedl, Therese
and Kerren, Andreas",
title="Aesthetic Discrimination of Graph Layouts",
booktitle="Graph Drawing and Network Visualization",
year="2018",
publisher="Springer International Publishing",
address="Cham",
pages="169--184",
doi=”10.1007/978-3-030-04414-5_12”,
abstract="This paper addresses the following basic question: given two layouts of the same graph, which one is more aesthetically pleasing? We propose a neural network-based discriminator model trained on a labeled dataset that decides which of two layouts has a higher aesthetic quality. The feature vectors used as inputs to the model are based on known graph drawing quality metrics, classical statistics, information-theoretical quantities, and two-point statistics inspired by methods of condensed matter physics. The large corpus of layout pairs used for training and testing is constructed using force-directed drawing algorithms and the layouts that naturally stem from the process of graph generation. It is further extended using data augmentation techniques. Our model demonstrates a mean prediction accuracy of 96.48{\%}, outperforming discriminators based on stress and on the linear combination of popular quality metrics by a small but statistically significant margin.",
isbn="978-3-030-04414-5"
}
DOI: https://doi.org/10.1007/978-3-030-04414-5_12
year: 2018
Conference: GD
link: https://link.springer.com/content/pdf/10.1007%2F978-3-030-04414-5.pdf
Notes: machine learning - uses ml to discriminate between which is the best layout in terms of quality

Great Example: The github has extensive readme, they also provide all code, reports slides associated with the paper.
paper type: quality metrics
Technique: machine learning
Graph feature: generic
Dataset tag clean: AT&T, Custom (Replicable), Matrix Market, RandDAG, Rome-Lib
Dataset used: Rome-Lib, North Lib, Random DAG, Matrix Market, custom
dataset size: 36000
Dataset tag relations: North DAGs (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/North%20DAGs%20a58f7143ef524c8a8c737df90162d3fb.md), Rome-Lib (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Rome-Lib%20c2f20984de724f4c89764b0bc494e99e.md), Matrix Market (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Matrix%20Market%2080bd4320417342458aefa031cf65db1f.md), RandDAG (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/RandDAG%2054b6ed8fdecb4256b2cca6298f09965e.md)
Type of edit to the dataset: NA
Size of graphs: ?
Easy to find info about graphs?: NO, Text
Results measured: ML-related Metrics, Success Rate (ML)
Evaluation type (Multi-Select): Case Study, Quantitative Aggregated
Evaluation type: visual, aggregate
Supplemental material (Multi-select): appendix
Supplemental material available: yes https://arxiv.org/abs/1809.01017
Does Provide Code: External Link
Type of storage for supplemental material: Github, arxiv
To review: No
Go find the datasets: No
Go hunt for citations: No
Great example: Yes