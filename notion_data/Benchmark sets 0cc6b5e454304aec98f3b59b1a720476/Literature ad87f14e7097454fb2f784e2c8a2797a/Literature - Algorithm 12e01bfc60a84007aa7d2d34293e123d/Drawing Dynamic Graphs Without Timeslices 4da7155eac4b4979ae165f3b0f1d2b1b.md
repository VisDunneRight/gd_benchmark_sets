# Drawing Dynamic Graphs Without Timeslices

Citation name: Simonetto2018
Authors: Paolo Simonetto and Daniel Archambault and Stephen Kobourov
Bibtex: @incollection{Simonetto2018,
  doi = {10.1007/978-3-319-73915-1_31},
  url = {https://doi.org/10.1007/978-3-319-73915-1_31},
  year = {2018},
  publisher = {Springer International Publishing},
  pages = {394--409},
  author = {Paolo Simonetto and Daniel Archambault and Stephen Kobourov},
  title = {Drawing Dynamic Graphs Without Timeslices},
  booktitle = {Lecture Notes in Computer Science}
}
DOI: https://doi.org/10.1007/978-3-319-73915-1_31
Year: 2017
Conference: GD
link: https://link.springer.com/content/pdf/10.1007%2F978-3-319-73915-1.pdf
Notes: Dataset sources: 

InfoVis Co-Authorship (Discrete): a co-authorship network for papers published
in the InfoVis conference from 1995 to 2015 [1]. Authors collaborating on a paper
are connected in a clique at the time of publication of the paper. Note this is
not a cumulative network as authors can appear, disappear, and appear again.
The data is of discrete nature with exactly 21 timeslices (one per year).
Van De Bunt (Discrete): shows the relationships between 32 freshmen at
seven different time points. A discrete dynamic graph is built using the method
of Brandes et al. [9], with an undirected edge inserted into a timeslice if the
participants reciprocally report “best friendship” or “friendship” at that time.
Newcomb Fraternity Data (Discrete): contains the sociometric preference of
17 members of a fraternity in the University of Michigan in the fall of 1956 [39].
As in previous work [9], at each timeslice, we inserted undirected edges connect-
ing students to their three best friends.
Rugby (Continuous): is a network derived from over 3,000 tweets involving
teams in the Guinness Pro12 rugby competition. The tweets were posted between
09.01.2014 and 10.23.2015. Each tweet contains information about the involved
teams and the time of publication with a precision down to the second.
Pride and Prejudice (Continuous): lists the dialogues between characters in
the novel Pride and Prejudice in order [29]. The book has 61 chapters and the
data set includes over 4,000 interactions between characters.
paper type: algorithm, comparison
Technique: force-directed
Graph feature: dynamic, dynamic (continuous)
Dataset tag clean: Blogposts/Tweets/Forum Posts, Collaboration Networks, Social Networks
Dataset used: infovis coauthorship, van de bunt, newcomb fraternity data, rugby, pride and prejudice
dataset size: 5
Dataset tag relations: Assorted Collaboration Network (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Assorted%20Collaboration%20Network%206062ff126f474a50b5f3dc9b945d43da.md), Social Networks (../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Social%20Networks%2090888b3285d042d49072985b05f95203.md)
Type of edit to the dataset: NA
Size of graphs (Clean up): 224 - 4000
Size of graphs: not specified
Easy to find info about graphs?: NO, Text
Results measured: Crowding, Distortion, Node Movement Minimization, Running Time, Stress
Evaluation type (Multi-Select): Quantitative Individual
Evaluation type: not really visual
Supplemental material (Multi-select): video
Supplemental material available: Yes,https://cs.swan.ac.uk/~dynnoslice/software.html
Does Provide Code: External Link
Type of storage for supplemental material: university website
To review: No
Go find the datasets: Yes
Go hunt for citations: No
Great example: No
Dataset names: infovis coauthorship, newcomb fraternity data, pride and prejudice, rugby, van de bunt
Related to Benchmark datasets (Related to Literature - Algorithm (Dataset tag relations) 1): Social Networks (../../Existing%20benchmark%20datasets%20(1)%204e6ac4f7a1004e179b2efe7128ee12b8/Benchmark%20datasets%20fff01d52e4ad81ae9875ec4733f4a970/Social%20Networks%20fff01d52e4ad811e963fc9641224bac2.md), Assorted Collaboration Network (../../Existing%20benchmark%20datasets%20(1)%204e6ac4f7a1004e179b2efe7128ee12b8/Benchmark%20datasets%20fff01d52e4ad81ae9875ec4733f4a970/Assorted%20Collaboration%20Network%20fff01d52e4ad81c6b058fa7c75c14808.md)
Related to Benchmark datasets (Related to Literature - Algorithm (Dataset tag relations) 1) 1: Assorted Collaboration Network (../../Existing%20benchmark%20datasets%20(1)%20d774ccc4903946489c8369c319381d05/Benchmark%20datasets%20fff01d52e4ad81298f4dcb2af7a126a8/Assorted%20Collaboration%20Network%20fff01d52e4ad81e6ade9eb25f7da3f5f.md), Social Networks (../../Existing%20benchmark%20datasets%20(1)%20d774ccc4903946489c8369c319381d05/Benchmark%20datasets%20fff01d52e4ad81298f4dcb2af7a126a8/Social%20Networks%20fff01d52e4ad81e78e2efb90274be5f4.md)