# Enron

Appeared in years: 2
Child collections: SNAP%20(Stanford%20Network%20Analysis%20Platform)%201cd77eaee57147ce8263b2f9eaa2589c.md
Graph features in papers: 4
In repo?: No
Note: Very high variance in node degrees 
Data can be considered threaded and directed, SNAP version of network data is explicitely undirected though
Origin Notes: Data made public by the Federal Energy Regulatory Comission when investigating Enron. It has had a few changes over time documented in the link. The data is currently hosted by William W.Cohen from CMU on a webiste,and it is also hosted on SNAP. SNAP asks to cite the paper linked in Origin paper, although this is not the original source of the data.
Origin paper plaintext: Introducing the Enron Corpus
Page id: ed3c62b92cf14a7b86c691ac3651dab3
Related to Literature - Algorithm (1) (Dataset tag relations): https://www.notion.so/Reordering-massive-sequence-views-Enabling-temporal-and-structural-analysis-of-dynamic-networks-59101c28c7a54141bfebd74208f0250f, https://www.notion.so/An-Efficient-Framework-for-Generating-Storyline-Visualizations-from-Streaming-Data-d06da0be3b5244b791f30c22ff2b7277
Related to Literature - Algorithm (Dataset tag relations) 1: https://www.notion.so/An-Efficient-Framework-for-Generating-Storyline-Visualizations-from-Streaming-Data-0a3f35ebac3f468cb9c3adee03f62a06, https://www.notion.so/Reordering-massive-sequence-views-Enabling-temporal-and-structural-analysis-of-dynamic-networks-f62118d5310d44b099b3ccc71fd5a8aa
Related to Literature DOIs: https://doi.org/10.1109/PacificVis.2013.6596125,https://doi.org/10.1109/TVCG.2015.2392771
Related to Literature DOIs plaintext: https://doi.org/10.1109/PacificVis.2013.6596125,https://doi.org/10.1109/TVCG.2015.2392771
Related to Literature plaintext: An Efficient Framework for Generating Storyline Visualizations from Streaming Data, Reordering massive sequence views: Enabling temporal and structural analysis of dynamic networks
Size: 150 enron executives, 500k messages
cleaned format?: No
duplicate?: No
graph features handled: Generic
is it stored properly?: No
link works?: Yes
must be analyzed: Yes
where to find: https://www.cs.cmu.edu/~enron/
🧾Origin Paper: https://www.notion.so/Introducing-the-Enron-Corpus-52663d33d36b4940b5966f72f6c73a70

From [**An Efficient Framework for Generating Storyline Visualizations from Streaming Data**](https://www.notion.so/An-Efficient-Framework-for-Generating-Storyline-Visualizations-from-Streaming-Data-0a3f35ebac3f468cb9c3adee03f62a06) 

![Untitled](Enron%20ed3c62b92cf14a7b86c691ac3651dab3/Untitled.png)

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

![Untitled](Enron%20ed3c62b92cf14a7b86c691ac3651dab3/Untitled%201.png)

![Untitled](Enron%20ed3c62b92cf14a7b86c691ac3651dab3/Untitled%202.png)

This paper definitely uses this as a layered, categorical graph - could even be a hypergraph

From [Reordering massive sequence views: Enabling temporal and structural analysis of dynamic networks](https://www.notion.so/Reordering-massive-sequence-views-Enabling-temporal-and-structural-analysis-of-dynamic-networks-f62118d5310d44b099b3ccc71fd5a8aa) 

![Untitled](Enron%20ed3c62b92cf14a7b86c691ac3651dab3/Untitled%203.png)

> We cleaned the data set by removing duplicates, spam and only to contain internal communication between Enron employees annotated with employee function leaving us with 151 nodes (employees) and 21374 edges (emails). Visualization using a node-link diagram enables the identification of stronger connections (see Figure 9(a)). However, temporal patterns and the evolution of the network cannot be analysed. From the standard MSV (Figure 9(b)) it becomes somewhat clear that transaction density increases over time and we can distinguish between different phases. We cannot, however, see features and identify communities due to visual clutter
> 

→ unclear. Layered?