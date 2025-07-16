# Enron

Note: Very high variance in node degrees. Data can be considered threaded and directed, although http://snap.stanford.edu/data/email-Enron.html provides a version of the network that is explicitly undirected.
Origin Notes: Data made public by the Federal Energy Regulatory Commission when investigating Enron. It has had a few changes over time documented in the link. The data is currently hosted by William W. Cohen from CMU on a webiste, and it is also hosted on SNAP. SNAP asks to cite the paper linked in Origin paper.
graph features handled: Dynamic, Dynamic (discrete), Generic, Large
Graph features in papers: dynamic,dynamic (discrete),layered graphs,n-layers
Origin Paper: Introducing the Enron Corpus (https://www.notion.so/Introducing-the-Enron-Corpus-fff01d52e4ad81fba637fe75674b9792?pvs=21)
Originally found at: https://www.cs.cmu.edu/~enron/
Size: The data consists of 150 Enron executives, who sent 500,000 messages between themselves.
Number of Graphs: 1
Child collections: SNAP (Stanford Network Analysis Platform) (SNAP%20(Stanford%20Network%20Analysis%20Platform)%20fff01d52e4ad81f0bc11d53cc1f769cb.md)
Appeared in years: 2015,2013
Type of Collection: Subset of other collection
is it stored properly?: No
must be analyzed: Yes
In repo?: No
Related to Literature - Algorithm (1) (Dataset tag relations): Reordering massive sequence views: Enabling temporal and structural analysis of dynamic networks (https://www.notion.so/Reordering-massive-sequence-views-Enabling-temporal-and-structural-analysis-of-dynamic-networks-59101c28c7a54141bfebd74208f0250f?pvs=21), An Efficient Framework for Generating Storyline Visualizations from Streaming Data (https://www.notion.so/An-Efficient-Framework-for-Generating-Storyline-Visualizations-from-Streaming-Data-d06da0be3b5244b791f30c22ff2b7277?pvs=21)
cleaned format?: No
duplicate?: No
link works?: Yes
Added in paper: Yes
Origin paper plaintext: Introducing the Enron Corpus
Page id: fff01d52e4ad81ff951ae639a98a177c
unavailable/skip: Yes
Cleaned ALL data: No
first look: No
Related to Literature - Algorithm (Dataset tag relations) 1: An Efficient Framework for Generating Storyline Visualizations from Streaming Data (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/An%20Efficient%20Framework%20for%20Generating%20Storyline%20Vi%200a3f35ebac3f468cb9c3adee03f62a06.md), Reordering massive sequence views: Enabling temporal and structural analysis of dynamic networks (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Reordering%20massive%20sequence%20views%20Enabling%20tempora%20f62118d5310d44b099b3ccc71fd5a8aa.md)

# Body

### Descriptions from Literature

From “[Reordering massive sequence views: Enabling temporal and structural analysis of dynamic networks](https://doi.org/10.1109/PacificVis.2013.6596125)”:

> We cleaned the data set by removing duplicates, spam and only to contain internal communication between Enron employees annotated with employee function leaving us with 151 nodes (employees) and 21374 edges (emails). Visualization using a node-link diagram enables the identification of stronger connections (see Figure 9(a)). However, temporal patterns and the evolution of the network cannot be analysed. From the standard MSV (Figure 9(b)) it becomes somewhat clear that transaction density increases over time and we can distinguish between different phases. We cannot, however, see features and identify communities due to visual clutter
> 

### Example Figures

From “[An Efficient Framework for Generating Storyline Visualizations from Streaming Data](https://doi.org/10.1109/TVCG.2015.2392771)”:

![Untitled](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Enron%20ed3c62b92cf14a7b86c691ac3651dab3/Untitled.png)

From “[Reordering massive sequence views: Enabling temporal and structural analysis of dynamic networks](https://doi.org/10.1109/PacificVis.2013.6596125)”:

![Untitled](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Enron%20ed3c62b92cf14a7b86c691ac3651dab3/Untitled%201.png)

=== STOP RENDERING ===

[https://www.cs.cmu.edu/~enron/](https://www.cs.cmu.edu/~enron/)

150 enron executives (users), 500k messages - many more employees

some have attachments

case nodes are users: could be a very connected dataset (perhaps too few nodes) - very high variance in node degree

case nodes are messages: could be a sparsely connected graph

there’s dates → can be layered

This dataset was collected and prepared by the

[CALO Project](http://www.ai.sri.com/project/CALO)

(A Cognitive Assistant that Learns and Organizes). It contains data from about 150 users, mostly senior management of Enron, organized into folders. The corpus contains a total of about 0.5M messages. This data was originally

[made public, and posted to the web](http://www.salon.com/news/feature/2003/10/14/enron/index_np.html)

, by the

[Federal Energy Regulatory Commission](http://www.ferc.gov/)

during its investigation.

The email dataset was later purchased by [Leslie Kaelbling](http://www.ai.mit.edu/people/lpk/lpk.html) at MIT, and turned out to have a number of integrity problems. A number of folks at SRI, notably [Melinda Gervasio](http://www.ai.sri.com/people/gervasio), worked hard to correct these problems, and it is thanks to them (not me) that the dataset is available. The dataset here does not include attachments, and some messages have been deleted "as part of a redaction effort due to requests from affected employees". Invalid email addresses were converted to something of the form user@enron.com whenever possible (i.e., recipient is specified in some parse-able format like "Doe, John" or "Mary K. Smith") and to no_address@enron.com when no recipient was specified.

Visualizations from [https://www.kaggle.com/jamestollefson/enron-network-analysis](https://www.kaggle.com/jamestollefson/enron-network-analysis):

![Untitled](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Enron%20ed3c62b92cf14a7b86c691ac3651dab3/Untitled%202.png)

![Untitled](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Enron%20ed3c62b92cf14a7b86c691ac3651dab3/Untitled%203.png)

This paper definitely uses this as a layered, categorical graph - could even be a hypergraph

> 
> 

→ unclear. Layered?