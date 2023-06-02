# Debates

Added in paper: No
Appeared in years: 1
Cleaned ALL data: No
Graph features in papers: 3
In repo?: No
Origin Notes: Created by researchers at the University of Konstanz for the LingVis framework (https://lingvis.io/) and VisArgue project (http://www.visargue.uni-konstanz.de/en/). First appeared in “NEREx: Named-Entity Relationship Exploration in Multi-Party Conversations”.
Page id: 54eb2cd4ba2c48eb945bd49e5f4bbf4f
Related to Literature - Algorithm (Dataset tag relations) 1: NEREx: Named-Entity Relationship Exploration in Multi-Party Conversations (https://www.notion.so/NEREx-Named-Entity-Relationship-Exploration-in-Multi-Party-Conversations-0c839bcf912a474595a556b7791ff4c2?pvs=21)
Related to Literature DOIs: https://doi.org/10.1111/cgf.13181

Related to Literature DOIs plaintext: https://doi.org/10.1111/cgf.13181

Related to Literature plaintext: NEREx: Named-Entity Relationship Exploration in Multi-Party Conversations
Type of Collection: Lost/Unavailable
cleaned format?: No
duplicate?: No
graph features handled: Categorical Nodes, Directed Edges, edge weighted, node weighted
is it stored properly?: No
link works?: No
must be analyzed: No
unavailable/skip: Yes

### Description from Literature

From “NEREx: Named-Entity Relationship Exploration in Multi-Party Conversations”,

> In order to explore the relations between entities, we use a distance-restricted model for creating entity-pairs. As described in Section 2, prior work considers relations between entities either as semantic relations based on linguistic knowledge or regards two entities as related due to their presence in the same document. The often ungrammatical structure of utterances in verbatim text transcripts (including non-standard lexical items, syntactic patterns, interruptions, repetitions, and crosstalk) requires a simple extralinguistic model. To overcome these limitations, we introduce a model that bounds the scope in which we consider two entities to be related, using a distance threshold (*maxDist*). Our method creates a pair of entities if the entities appear in the same sentences within *maxDist* words of one another.
> 

> However, not only are frequent entity-pairs important, but also pairs that are semantically similar (e.g., *cut $5 trillion*, *cut $4 trillion*). These often present opposing speaker opinions about a given topic. To maximize the chance that entity-pairs represent true semantic relations, we set the default value of *maxDist* to a low value (5 words). To vary the granularity of the analysis, the parameter can be changed interactively depending on the analysis task and data. Nevertheless, some infrequent longer-distance entity-pairs are discovered which do not represent salient relations. To reduce their impact, we calculate the average observed distance (in words) for each entity pair. We use both frequency and average distance in the visualization to reflect the strength of the entity-pair.
> 

### Example Figures

From “NEREx: Named-Entity Relationship Exploration in Multi-Party Conversations”, entity graph of the first first presidential debate between Trump and Clinton:

![cgf13181-fig-0004-m.jpg](Debates%2054eb2cd4ba2c48eb945bd49e5f4bbf4f/cgf13181-fig-0004-m.jpg)

From “NEREx: Named-Entity Relationship Exploration in Multi-Party Conversations”, entity graph of the same debate, focusing on the concept of taxes:

![cgf13181-fig-0006-m.jpg](Debates%2054eb2cd4ba2c48eb945bd49e5f4bbf4f/cgf13181-fig-0006-m.jpg)