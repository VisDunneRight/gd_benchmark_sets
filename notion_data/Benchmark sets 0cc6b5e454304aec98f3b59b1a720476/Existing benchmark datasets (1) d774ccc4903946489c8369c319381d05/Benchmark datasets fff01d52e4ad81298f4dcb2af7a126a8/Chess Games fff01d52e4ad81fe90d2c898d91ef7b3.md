# Chess Games

Note: The data used in the literature focuses on the 200 most common openings. These are all sequences of 6 moves  and are topologically equivalent. 
Origin Notes: 20,058 chess openings from games in a database of played online chess games. The authors of “Sequence Braiding: Visual Overviews of Temporal Event Sequences and Attributes” collected the dataset online from the data science platform kaggle. The dataset was collected by user Mitchell J and collects data from the chess website Lichess.org.
graph features handled: Categorical nodes, Dynamic, Dynamic (discrete), N-layers
Graph features in papers: dynamic,dynamic (discrete),layered graphs,n-layers
Origin Paper: Chess Game Dataset (Lichess) (https://www.notion.so/Chess-Game-Dataset-Lichess-fff01d52e4ad81a5bb03c3c22d32b9e0?pvs=21)
Originally found at: https://www.kaggle.com/datasets/datasnaek/chess?resource=download
https://github.com/VisDunneRight/sequence_braiding/blob/master/data/chess.json
Size: The data consists of 20058 sequences, which result in a disconnected graph of 118164 nodes, and  98106 edges.
Appeared in years: 2020
Type of Collection: Single Graph
is it stored properly?: No
must be analyzed: Yes
In repo?: Yes
Related to Literature - Algorithm (1) (Dataset tag relations): Sequence Braiding: Visual Overviews of Temporal Event Sequences and Attributes (https://www.notion.so/Sequence-Braiding-Visual-Overviews-of-Temporal-Event-Sequences-and-Attributes-54be1011c0324f04bcc2bafa58b89859?pvs=21)
cleaned format?: Yes
duplicate?: No
link works?: Yes
Added in paper: No
OSF link json: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d90eed4cf7480eef055740
Origin paper plaintext: Chess Game Dataset (Lichess)
Page id: fff01d52e4ad81fe90d2c898d91ef7b3
unavailable/skip: No
Cleaned ALL data: No
OSF link gexf: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d948ae4cf74810580556b8
OSF link gml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d96e1b0c2b4d0f65386312
OSF link graphml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d9705494a6be112912e9d0
first look: No
sparkline data: {'min': 0, 'max': 2, 'step_size': 1, 'num_bins': 3, 'bins': [0, 1, 2], 'node_degree': [203, 39710, 78251]}
Related to Literature - Algorithm (Dataset tag relations) 1: Sequence Braiding: Visual Overviews of Temporal Event Sequences and Attributes (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Sequence%20Braiding%20Visual%20Overviews%20of%20Temporal%20Eve%204dfe62dc294b4ef1b453ecf09be2ea0f.md)

# Body

### Descriptions from Literature

From “[Sequence Braiding: Visual Overviews of Temporal Event Sequences and Attributes](https://doi.org/10.1109/TVCG.2020.3030442)”:

> 200 Chess openings displayed with Sequence Braiding. Each line represents a sequence of moves of the white player, each group is a chess piece type. Most openings start with a pawn, and very little with the knight.
> 

### Example Figures

From “[Sequence Braiding: Visual Overviews of Temporal Event Sequences and Attributes](https://doi.org/10.1109/TVCG.2020.3030442)”:

![Screen Shot 2023-01-21 at 2.15.02 PM.png](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Chess%20Games%20023a47d6ae914567a05132ac1dfbe972/Screen_Shot_2023-01-21_at_2.15.02_PM.png)

**Fig. 7.** 200 Chess openings displayed with Sequence Braiding. Each line represents a sequence of moves of the white player, each group is a chess piece type. Most openings start with a pawn, and very little with the knight. After moving a pawn, it is common to move a knight or a pawn, it is a little less common to move a bishop, and only a little number of openings move the queen on the second move.