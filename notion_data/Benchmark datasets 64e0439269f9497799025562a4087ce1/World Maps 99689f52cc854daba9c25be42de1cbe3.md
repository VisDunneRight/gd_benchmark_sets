# World Maps

Note: Datasets contain various attributes for a few locations and their geographical adjacency, namely neighboring states, countries, and municipalities. 
Origin Notes: World Bank country information transformed  into a weight-vectors dataset. Some of the incomplete data was filled from disparate sources mentioned in the paper’s supplemental materials: https://doi.org/10.48550/arXiv.1908.07291.
graph features handled: Categorical nodes, Dynamic, Spatial, Weighted nodes
Graph features in papers: dynamic,spatial
Origin Paper: Computing Stable Demers Cartograms (https://www.notion.so/Computing-Stable-Demers-Cartograms-73ed6431833d49bba5807b76ca3b0fd4?pvs=21)
Originally found at: https://data.worldbank.org/indicator
https://github.com/loizuf/StableDemersLP/tree/main/code/StableDemers_TVCG/data
Size: 48-514 nodes, 205-2428 edges
Number of Graphs: 14
Appeared in years: 2019
Type of Collection: Uniform Benchmark
is it stored properly?: No
must be analyzed: No
In repo?: Yes
Related to Literature - Algorithm (1) (Dataset tag relations): Computing Stable Demers Cartograms (https://www.notion.so/Computing-Stable-Demers-Cartograms-852e6a1086c74936a3fbe7d9c25e365e?pvs=21)
cleaned format?: No
duplicate?: No
link works?: Yes
Added in paper: No
OSF link json: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d94aca94a6be102f12e736
Origin paper plaintext: Computing Stable Demers Cartograms
Page id: 99689f52cc854daba9c25be42de1cbe3
unavailable/skip: No
Cleaned ALL data: No
OSF link gexf: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d948f10c2b4d0e8d386217
OSF link gml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d96dde0c2b4d0f653862e3
OSF link graphml: https://files.osf.io/v1/resources/j7ucv/providers/osfstorage/64d971f194a6be112a12eaaa
first look: No
sparkline data: {'min': 48, 'max': 514, 'step_size': 100, 'num_bins': 6, 'bins': [0, 100, 200, 300, 400, 500], 'num_nodes': [4, 4, 0, 0, 0, 6]}
Related to Literature - Algorithm (Dataset tag relations) 1: Computing Stable Demers Cartograms (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Computing%20Stable%20Demers%20Cartograms%20fb418899e13f45f4b6b3c6296e07a599.md)

# Body

### Statistics

![four_in_one.svg](World%20Maps%2099689f52cc854daba9c25be42de1cbe3/four_in_one.svg)

### Descriptions from Literature

From  [Computing Stable Demers Cartograms](https://link.springer.com/chapter/10.1007/978-3-030-35802-0_4)”:

> We run experiments on real-world datasets. For time-series data, we expect a gradual change and strong correlation between the different values. For weight-vectors data, we expect more erratic changes and less correlation. We use two maps with rather different geographic structures: the first (**World**) is a map of world countries, having mixed region (country) sizes in a rather unstructured manner; the second (**US**) is a map of the 48 contiguous US states, having relatively high structure in sizes of its states, with large states in the middle and along the west coast and many smaller states along the east coast.
> 

From Supplemental Materials, Appendix C of [*“Computing Stable Demers Cartograms*”:](https://doi.org/10.48550/arXiv.1908.07291)

![Untitled](World%20Maps%2099689f52cc854daba9c25be42de1cbe3/Untitled.png)

### Example Figures

From  [Computing Stable Demers Cartograms](https://link.springer.com/chapter/10.1007/978-3-030-35802-0_4)”:

![Untitled](World%20Maps%2099689f52cc854daba9c25be42de1cbe3/Untitled%201.png)

=== STOP RENDERING ===

from [Computing Stable Demers Cartograms](../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Computing%20Stable%20Demers%20Cartograms%20fb418899e13f45f4b6b3c6296e07a599.md) 

World bank - bunch of references - all temporal datasets!

Missing Data from the world bank was filled with following linked sources:

https://en.wikipedia.org/wiki/Economy of North Korea#cite note-2

https://tradingeconomics.com/kuwait/rural-population-wb-data.html

http://www.efgs.info/wp-content/uploads/conferences/efgs/2016/S8-1
presentationV1 IdrizShala EFGS2016.pdf

https://tradingeconomics.com/eritrea/rural-population-wb-data.html

https://tradingeconomics.com/kuwait/forest-area-percent-of-land-area-wb-data.
html

https://tradingeconomics.com/kosovo/forest-area-percent-of-land-area-wb-data.
html