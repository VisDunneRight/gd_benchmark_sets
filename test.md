The paper presents a technique for storyline visualizations, with a focus on visualizing interactions between entities through time, and a linear programming formulation to compute the layout.

---

Strengths:
- the presented visualizations are easy to understand, and look nice and polished.
- the paper is well positioned in its research area
- the paper is well written and well organized, and is easy to read. 

---

Weaknesses:
1) The improvements over previous storyline techniques may look incremental compared to similar techniques.

2) One of the major weaknesses of using a linear programming technique is that they don’t scale well - which is just briefly addressed in the paper, in the discussion section (7). I believe the authors should give the readers at least an indication of the limitations of the techniques in terms of timing and memory. At the minimum, the authors should at least state how much time it took them to compute the presented examples, and what kind of setup they used. It would be even better though to provide statistics on graphs with different amounts of nodes and edges, and show how the algorithm scales, and how big of a graph can the reader be expected to compute with this technique.

3) In relation to the examples presented in the figures, then, I don't seem to be able to find details about them. I have trouble identifying if the content of Figure 8 is the entire plot of the Matrix, or just a section (same for all the other examples). I understand that representing the entire plot in detail might produce figures that look less nice, but in case that is just a section of the entire plot, I might have the following doubts:
- have the authors cherry-picked a section that looks good with their system, while the rest does not?
- have the authors chosen to represent a reduced section because they could not compute the entire plot?
I believe the authors should provide a justification of how the dataset was created, and how they chose to represent it. 

4) Figure 8 has the plot of the matrix, but I believe the names are wrong: more than half (Nancy, Danny, The Gang, Elaine) don’t seem to be characters that appear in matrix, but rather they seem to have been replaced by names from Figure 7, which contains the plot of another movie. This is probably a bug, but should be fixed before the next submission.

---

The authors might also consider including the following citations. The first two contain storyline algorithms that use groups of nodes that are drawn adjacent, perhaps akin to how interactions are drawn in the paper:

[1] Di Giacomo, E., Didimo, W., Liotta, G., Montecchiani, F., Tappini, A. (2020). Storyline Visualizations with Ubiquitous Actors. In: Auber, D., Valtr, P. (eds) Graph Drawing and Network Visualization. GD 2020. Lecture Notes in Computer Science(), vol 12590. Springer, Cham. [https://doi.org/10.1007/978-3-030-68766-3_25](https://doi.org/10.1007/978-3-030-68766-3_25)

[2] van Dijk, T.C., Lipp, F., Markfelder, P., Wolff, A. (2018). Computing Storyline Visualizations with Few Block Crossings. In: Frati, F., Ma, KL. (eds) Graph Drawing and Network Visualization. GD 2017. Lecture Notes in Computer Science(), vol 10692. Springer, Cham. [https://doi.org/10.1007/978-3-319-73915-1_29](https://doi.org/10.1007/978-3-319-73915-1_29)

The following instead uses multi-objective linear programming to compute a layout algorithm, akin to what the authors do with their formulation:

[3] S. di Bartolomeo, M. Riedewald, W. Gatterbauer and C. Dunne, "STRATISFIMAL LAYOUT: A modular optimization model for laying out layered node-link network visualizations," in IEEE Transactions on Visualization and Computer Graphics, vol. 28, no. 1, pp. 324-334, Jan. 2022, doi: 10.1109/TVCG.2021.3114756.

---

Summary:
- Discuss the scalability of the method.
- Explain how the datasets were generated and what choices were made to represent them.
- Fix bug in figure 8.