# Mathematics genealogy

Added in paper: No
Appeared in years: 1
Cleaned ALL data: No
Graph features in papers: 2
In repo?: No
Note: (Circa 2016 the graph consisted of 200037 nodes with 3.8% percent of them being isolated, and 1962 components of size two). Largest component contained 180094 nodes.
Page id: 081ba4645aac48c19719b16033c637f3
Related to Literature - Algorithm (Dataset tag relations) 1: Visualizing Evolving Trees (https://www.notion.so/Visualizing-Evolving-Trees-3596f84acbbe46799f4f093af2f28aae?pvs=21)
Related to Literature DOIs: 10.1007/978-3-031-22203-0_23
Related to Literature DOIs plaintext: 10.1007/978-3-031-22203-0_23
Related to Literature plaintext: Visualizing Evolving Trees
Size: 291014 records as of May 2023 (possibly nodes)
Type of Collection: Lost/Unavailable
cleaned format?: No
duplicate?: No
graph features handled: nonplanar, temporal, tree-like
is it stored properly?: No
link works?: Yes
must be analyzed: No
unavailable/skip: Yes
where to find: https://genealogy.math.ndsu.nodak.edu/

[https://github.com/abureyanahmed/evolving_tree/tree/main/dataset](https://github.com/abureyanahmed/evolving_tree/tree/main/dataset)

from [https://genealogy.math.ndsu.nodak.edu/](https://genealogy.math.ndsu.nodak.edu/):

![Untitled](Mathematics%20genealogy%20081ba4645aac48c19719b16033c637f3/Untitled.png)

^ from source website one of their examples for their poster services. 

From [**Visualizing Evolving Trees**](Tree%20of%20Life%20cb0493d6b6da4a73a979f06225983011/Visualizing%20Evolving%20Trees%2095d3552ad36746f4a3e3614cd1c1f561.md)

![Untitled](Mathematics%20genealogy%20081ba4645aac48c19719b16033c637f3/Untitled%201.png)

Fig. 4: Layouts from DynNoSlice, DynaGraph, Dagre, Radial, ImPrEd, DynaCola and DynaSafe of the same evolving math genealogy tree; each row adds six new nodes.

They make you request the data individually and in the linked form they have a note about not redistributing data:

[mgp-permission-agreement.pdf](Mathematics%20genealogy%20081ba4645aac48c19719b16033c637f3/mgp-permission-agreement.pdf)

![Untitled](Mathematics%20genealogy%20081ba4645aac48c19719b16033c637f3/Untitled%202.png)

reached out to them 5/18/2023

=== STOP RENDERING ===

It is non-planar because multiple advisors can advise the same person or a person can have multiple advisors! Infact, there is a K3,3 in it

In July 2016, Cosmin Ionita and Pat Quillen of 
MathWorks used MATLAB to analyze the Math Genealogy Project graph. At 
the time, the genealogy graph contained 200,037 vertices. There were 
7639 (3.8%) isolated vertices and 1962 components of size two 
(advisor-advisee pairs where we have no information about the advisor). 
The largest component of the genealogy graph contained 180,094 vertices,
 accounting for 90% of all vertices in the graph. The main component has
 7323 root vertices (individuals with no advisor) and 137,155 leaves 
(mathematicians with no students), accounting for 76.2% of the vertices 
in this component. The next largest component sizes were 81, 50, 47, 34,
 34, 33, 31, 31, and 30.
For historical comparisonn, we also have data from June 2010, when 
Professor David Joyner of the United States Naval Academy asked for data
 from our database to analyze it as a graph. At the time, the genealogy 
graph had 142,688 vertices. Of these, 7,190 were isolated vertices (5% 
of the total). The largest component had 121,424 vertices (85% of the 
total number). The next largest component had 128 vertices. The next 
largest component sizes were 79, 61, 45, and 42. The most frequent size 
of a nontrivial component was 2; there were 1937 components of size 2. 
The component with 121,424 vertices had 4,639 root verticies, i.e., 
mathematicians for whom the advisor is currently unknown.

The Mathematics Genealogy Project graph is nonplanar. Thanks to 
Professor Ezra Brown of Virginia Tech for assisting in finding the 
subdivision of *K*3,3 depicted below. The green vertices
 form one color class and the yellow ones form the other. Interestingly,
 Gauß is the only vertex that needs to be connected by paths with more 
than one edge.