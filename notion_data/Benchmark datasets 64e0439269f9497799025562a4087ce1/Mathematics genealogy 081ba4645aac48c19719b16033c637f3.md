# Mathematics Genealogy

Note: Refer to the https://mathgenealogy.org/contact.php for the data, which consists of doctoral graduates in mathematics and some adjacent fields, alongside properties like the degree granting institution and tittle of thesis. Entries also have relations based on advisors. 
Origin Notes: Database from a project started by Harry Coonce and now supported by the North Dakota State University. 
graph features handled: dynamic, nonplanar, temporal, tree-like
Graph features in papers: dynamic,dynamic (discrete)
Originally found at: https://genealogy.math.ndsu.nodak.edu/
Size: 291014 records as of May 2023. In 2016 the graph consisted of 200037 nodes with 3.8% percent of them being isolated, and 1962 components of size two. The largest component contained 180094 nodes.
Number of Graphs: 0
Origin Paper: The Mathematics Genealogy Project (https://www.notion.so/The-Mathematics-Genealogy-Project-c75a9e7eb263423c9d8ad1be3e898095?pvs=21)
Appeared in years: 2023
Type of Collection: Lost/Unavailable
is it stored properly?: No
must be analyzed: No
In repo?: No
cleaned format?: No
duplicate?: No
link works?: Yes
Added in paper: No
Origin paper plaintext: The Mathematics Genealogy Project
Page id: 081ba4645aac48c19719b16033c637f3
unavailable/skip: Yes
Cleaned ALL data: No
Related to Literature - Algorithm (Dataset tag relations) 1: Visualizing Evolving Trees (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Visualizing%20Evolving%20Trees%203596f84acbbe46799f4f093af2f28aae.md)
first look: Yes

# Body

### Description from Literature

From [**Visualizing Evolving Trees](https://www.notion.so/Visualizing-Evolving-Trees-95d3552ad36746f4a3e3614cd1c1f561?pvs=21):**

> **The Mathematics Genealogy:** shows advisor-advisee relationships in the world of mathematics, stretching back to the middle ages [[36](https://link.springer.com/chapter/10.1007/978-3-031-22203-0_23#ref-CR36)]. The dataset includes the thesis titles, students, advisors, dates, and number of descendants. The total number of nodes is around 260,000 and is continuously updated. While this data is not quite a tree (or even connected, or planar), we extract a subset to create a tree with 500 nodes. The maximum node degree of this tree is 5 and the radius is 14.
> 

### Example Figures

From The Mathematics Genealogy Project, the data source at [https://genealogy.math.ndsu.nodak.edu/](https://genealogy.math.ndsu.nodak.edu/):

![Untitled](Mathematics%20Genealogy%20081ba4645aac48c19719b16033c637f3/Untitled.png)

From [**Visualizing Evolving Trees](https://www.notion.so/Visualizing-Evolving-Trees-95d3552ad36746f4a3e3614cd1c1f561?pvs=21):**

![Untitled](Mathematics%20Genealogy%20081ba4645aac48c19719b16033c637f3/Untitled%201.png)

**Fig. 4:** Layouts from DynNoSlice, DynaGraph, Dagre, Radial, ImPrEd, DynaCola and DynaSafe of the same evolving math genealogy tree; each row adds six new nodes.

== STOP RENDERING ==

[https://github.com/abureyanahmed/evolving_tree/tree/main/dataset](https://github.com/abureyanahmed/evolving_tree/tree/main/dataset)

They make you request the data individually and in the linked form they have a note about not redistributing data:

[mgp-permission-agreement.pdf](Mathematics%20Genealogy%20081ba4645aac48c19719b16033c637f3/mgp-permission-agreement.pdf)

![Untitled](Mathematics%20Genealogy%20081ba4645aac48c19719b16033c637f3/Untitled%202.png)

reached out to them 5/18/2023

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