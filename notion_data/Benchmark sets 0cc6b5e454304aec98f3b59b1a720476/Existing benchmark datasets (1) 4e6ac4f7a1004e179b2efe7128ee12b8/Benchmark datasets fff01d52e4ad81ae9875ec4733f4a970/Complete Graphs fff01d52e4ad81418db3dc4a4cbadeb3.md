# Complete Graphs

Note: The linked dataset includes both the complete graphs $K_n$ for $5≤n≤50$ and the complete bipartite graphs $K_{n_1,n_2}$ for $5≤n1,n2≤40$. Crossing number is conjectured for most of these, and while not proven, we found these used in papers to validate minimum crossing numbers. We also note that the papers in our literature review did not provide example figures. 
Origin Notes: Source code and data are not provided, but the graphs are well known and can be generated easily.
graph features handled: Bipartite, Generic, Known crossing number
Graph features in papers: generic
Size: 5-80 nodes, 10-1600 edges
Number of Graphs: 1342
Appeared in years: 2019
Type of Collection: Uniform Benchmark
is it stored properly?: No
must be analyzed: No
In repo?: Yes
Related to Literature - Algorithm (1) (Dataset tag relations): An effective crossing minimisation heuristic based on star insertion (https://www.notion.so/An-effective-crossing-minimisation-heuristic-based-on-star-insertion-888933e03a604489ada5360688abe597?pvs=21)
cleaned format?: Yes
duplicate?: No
link works?: No
Added in paper: No
OSF link json:  https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d90ebb94a6be0ec012e7e6
Page id: fff01d52e4ad81418db3dc4a4cbadeb3
unavailable/skip: No
Cleaned ALL data: No
OSF link gexf: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d94965803e0c0c10558bc8
OSF link gml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d94db50c2b4d0ea1386352
OSF link graphml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d972030c2b4d0f5d3862dc
first look: No
sparkline data: {'min': 5, 'max': 80, 'step_size': 3, 'num_bins': 27, 'bins': [0, 3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48, 51, 54, 57, 60, 63, 66, 69, 72, 75, 78], 'num_nodes': [0, 1, 3, 6, 15, 24, 33, 42, 51, 60, 69, 78, 87, 96, 105, 108, 99, 87, 78, 69, 60, 51, 42, 33, 24, 15, 6]}
Related to Literature - Algorithm (Dataset tag relations) 1: An effective crossing minimisation heuristic based on star insertion (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/An%20effective%20crossing%20minimisation%20heuristic%20based%205fde465c129249599b79396bf3d3ae04.md)

# Body

### Statistics

![four_in_one.svg](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Complete%20Graphs%20202f26621cf34604935433a41b130f10/four_in_one.svg)

### Descriptions from Literature

From “[An effective crossing minimisation heuristic based on star insertion](https://doi.org/10.7155/jgaa.00487)”:

> **Complete graphs** - Although the crossing number of the complete graph $K_n$ is not known for for $n ≥ 13$, the value is conjectured, and typically assumed to be correct. We compare the nine combinations of schemes to see how close to the conjectured value each of them is able to get, for various sizes of complete graphs up to $n = 50$. We indicate how many crossings are obtained after the initial embedding, as well as at the conclusion of the heuristic. We also provide the runtimes, again separated into time spent producing the initial embedding, and time spent in the main loop of the heuristic.
> 

> **Complete bipartite graphs** - Much like the complete graphs, the crossing number of the complete bipartite graph $K_{n1,n2}$ is only known in general for $n_1 ≤ 6$, but the value is conjectured and typically assumed to be correct. Again, we compare the nine combinations of schemes to see how close to the conjectured value they can get for values up to $n_1,n_2 = 40$, and report the same data as for the Complete graphs.
> 

> The crossing number of the complete graph $K_n$ is conjectured (e.g. see Guy [25]) to be equal to
$H(n) := 1/4 \left\lfloor n/2\right\rfloor \left\lfloor (n − 1)/2\right\rfloor \left\lfloor(n − 2)/2\right\rfloor \left\lfloor (n − 3)/2\right\rfloor$.
Although this conjecture is widely believed to be correct, it has only been confirmed for $n ≤ 12$ despite considerable effort to extend the results further [30]. We ran the graphs $K_n$ for $5 ≤ n ≤ 50$. Each graph was run with 100 random permutations and the minimum found solution was compared to $H(n)$ by computing the percent relative deviation from $H(n)$…
For these graphs, we observe that when $n$ was odd, every scheme combination was able to obtain a drawing with $H(n)$ crossings. However, when $n$ was even, each scheme reached a value which was usually very close but not equal to $H(n)$.
> 

> The crossing number of the complete bipartite graph $K_{n_1,n_2}$ is conjectured (e.g. see Zarankiewicz [35]) to be equal to $Z(n_1, n_2) := \left\lfloor n_1/2\right\rfloor \left\lfloor (n_1 − 1)/2\right\rfloor \left\lfloor n_2/2\right\rfloor \left\lfloor (n_2 − 1)/2\right\rfloor$.
We ran the graphs $K_{n_1,n_2}$ for $5 ≤ n1 ≤ n2 ≤ 40$. Each graph was run with 100 random permutations and the minimum found solution was compared to $Z(n_1,n_2)$… As can be seen in Table 6, QuickCross was successful in obtaining the conjectured optimum in all cases and for all scheme combinations, except $K_{30,30}$ and $K_{40,40}$
>