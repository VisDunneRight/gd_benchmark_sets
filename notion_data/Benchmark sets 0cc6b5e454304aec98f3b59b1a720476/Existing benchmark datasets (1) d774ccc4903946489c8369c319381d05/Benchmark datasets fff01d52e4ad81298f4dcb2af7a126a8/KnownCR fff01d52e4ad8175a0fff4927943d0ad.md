# KnownCR

Note: The papers in our literature search did not show graph layouts in their evaluations. Hence, we do not show example figures. 
Origin Notes: The graphs themselves do not appear to exist online elsewhere, but the method by which they can be created is fully described in https://eldorado.tu-dortmund.de/handle/2003/27430?mode=full.
graph features handled: Known crossing number, Nonplanar
Graph features in papers: generic
Origin Paper: Application of SPQR-Trees in the Planarization Approach for Drawing Graphs (https://www.notion.so/Application-of-SPQR-Trees-in-the-Planarization-Approach-for-Drawing-Graphs-fff01d52e4ad8194850ec855e33b2226?pvs=21)
Size: 9-250 nodes, 18-750 edges
Appeared in years: 2021,2019,2011
Type of Collection: Uniform Benchmark
is it stored properly?: No
must be analyzed: No
In repo?: Yes
Related to Literature - Algorithm (1) (Dataset tag relations): An effective crossing minimisation heuristic based on star insertion (https://www.notion.so/An-effective-crossing-minimisation-heuristic-based-on-star-insertion-888933e03a604489ada5360688abe597?pvs=21), Advances in the Planarization Method: Effective Multiple Edge Insertions (https://www.notion.so/Advances-in-the-Planarization-Method-Effective-Multiple-Edge-Insertions-c518ce875daa4fe7b003ad506eb9a347?pvs=21), Star-Struck by Fixed Embeddings:
Modern Crossing Number Heuristics (https://www.notion.so/Star-Struck-by-Fixed-Embeddings-Modern-Crossing-Number-Heuristics-d8f0e972b962439d8b368e8a28a7046a?pvs=21)
cleaned format?: Yes
duplicate?: No
link works?: No
Added in paper: Yes
OSF link json: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d90ef60c2b4d0d2e3862be
Origin paper plaintext: Application of SPQR-Trees in the Planarization Approach for Drawing Graphs
Page id: fff01d52e4ad8175a0fff4927943d0ad
unavailable/skip: No
Cleaned ALL data: No
OSF link gexf: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d948121101aa0dc76a0c94
OSF link gml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d96dce0c2b4d0f653862d7
OSF link graphml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d9715c0c2b4d0f65386577
first look: No
sparkline data: {'min': 9, 'max': 250, 'step_size': 10, 'num_bins': 26, 'bins': [0, 10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 110, 120, 130, 140, 150, 160, 170, 180, 190, 200, 210, 220, 230, 240, 250], 'num_nodes': [1, 27, 101, 103, 105, 103, 106, 105, 104, 106, 105, 104, 106, 104, 105, 105, 106, 103, 107, 104, 104, 106, 105, 104, 106, 45]}
Related to Literature - Algorithm (Dataset tag relations) 1: Star-Struck by Fixed Embeddings:
Modern Crossing Number Heuristics (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Star-Struck%20by%20Fixed%20Embeddings%20Modern%20Crossing%20Nu%20f31c2a6c7b8d4683a1820d8101f89448.md), An effective crossing minimisation heuristic based on star insertion (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/An%20effective%20crossing%20minimisation%20heuristic%20based%205fde465c129249599b79396bf3d3ae04.md), Advances in the Planarization Method: Effective Multiple Edge Insertions (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Advances%20in%20the%20Planarization%20Method%20Effective%20Mul%20884c2bc419eb4197be261c1f1b3898ce.md)

# Body

### Statistics

![four_in_one.svg](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/KnownCR%20ed33d600c65e4c52a1506a905b774335/four_in_one.svg)

### Description from Literature

From “[An effective crossing minimisation heuristic based on star insertion](https://dx.doi.org/10.7155/jgaa.00487)”:

> KnownCR graphs- these are a set of instances containing between 9 and 250 vertices, first collected by Gutwenger [22], which can be further partitioned into four families of graphs as follows:
> 
> 
> $C_i \times C_j$: The Cartesian product of the cycle on $i$ vertices with the cycle on $j$ vertices. The instances contain graphs with $3 \leq i \leq 7$ and $j \geq i$ such that $ij \leq 250$.
> 
> $G_i \times P_j$: The Cartesian product of the path on $j+1$ vertices with one of the 21 non-isomorphic connected graphs on 5 vertices, where $i$ denotes which of the 21. The instances contain graphs with $3 \leq j \leq 49$.
> 
> $G_i \times C_j$: The Cartesian product of the cycle on $j$ vertices with one of the 21 non-isomorphic connected graphs on 5 vertices, where $i$ denotes which of the 21. The crossing number of these graphs is only known for some of the $G_i$ and only these cases are included. The instances contain graphs with $3 \leq j \leq 50$.
> 
> The Generalised Petersen graphs $P(j,2)$ and $P(j,3)$, on $2j$ vertices. We shall only use those of type $P(j,3)$ as $P(j,2)$ (studied in [20]) are easy for heuristics to solve, as has already been observed in [9]. The instances contain graphs with $9 \leq j \leq 125$.
> 

From “[Advances in the Planarization Method: Effective Multiple Edge Insertions](https://doi.org/10.1007/978-3-642-25878-7_10)”:

> Finally, the KnownCR graphs [11] are a collection of 1946 graphs with known crossing numbers (by proofs), consisting of generalized Petersen graphs (P(m, 2), P(m, 3)) and products of cycles $C_n$, paths $P_n$, and 5-vertex graphs $G_i (C_m \times C_n, G_i \times P_n, G_i \times C_n)$; these graphs have between 9 and 250 nodes.
> 

### Example Figures

From “[Application of SPQR-Trees in the Planarization Approach for Drawing Graphs](https://eldorado.tu-dortmund.de/handle/2003/27430?mode=full)”:

![Screen Shot 2023-01-28 at 2.42.42 PM.png](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/KnownCR%20ed33d600c65e4c52a1506a905b774335/Screen_Shot_2023-01-28_at_2.42.42_PM.png)

=== STOP RENDERING ===

[Eldorado: Application of SPQR-trees in the planarization approach for drawing graphs](https://eldorado.tu-dortmund.de/handle/2003/27430?mode=full)

From *An effective crossing minimisation heuristic based on star insertion,* “KnownCR graphs- these are a set of instances containing between 9 and 250 vertices, first collected by Gutwenger [22], which can be further partitioned into four families of graphs as follows:

- Ci ×Cj: the Cartesian product of the cycle on i vertices with the cycle on j vertices. The instances contain graphs with 3 ≤ i ≤ 7 and j ≥i such that ij ≤ 250.
- Gi×Pj: the cartesian product of the path on j+1 vertices with one of the 21 non-isomorphic connected graphs on 5 vertices, where i denotes which of the 21. The instances contain graphs with 3 ≤ j ≤ 49.
- Gi ×Cj: the cartesian product of the cycle on j vertices with one of the 21 non-isomorphic connected graphs on 5 vertices, where i denotes which of the 21. The crossing number of these graphs are only known for some of the Gi and only these cases are included. The instances contain graphs with 3 ≤ j ≤ 50
- The Generalised Petersen graphs P(j,2) and P(j,3), on 2j vertices. We shall only use those of type P(j,3) as P(j,2) (studied in [20]) are154 Clancy et al. An effective crossing minimisation heuristic easy for heuristics to solve as has already been observed in [9]. The instances contain graphs with 9 ≤ j ≤ 125.” from **(An effective crossing minimisation heuristic based on star insertion, Clancy et al. )**

How to construct a cartesian product graph:

![Screen Shot 2023-01-28 at 2.42.31 PM.png](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/KnownCR%20ed33d600c65e4c52a1506a905b774335/Screen_Shot_2023-01-28_at_2.42.31_PM.png)

Example of construction:

Images showing each Gi, and the known crossing number of Gi x Pn:

![Screen Shot 2023-01-28 at 2.50.06 PM.png](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/KnownCR%20ed33d600c65e4c52a1506a905b774335/Screen_Shot_2023-01-28_at_2.50.06_PM.png)