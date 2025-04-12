# Social-Network-Analysis
Social Network Analysis, analysis of similarity between 88 languages.

This project examines the relationship between languages based on common vocabulary share accross multiple languages. 
It constructs a network graph where each node is a language and the edges represent the number of words shared. 
This project was developed as part of the Social Media Mining course at the University of Milan.

Process:  

1. Acquired data on shared vocabulary across various languages.
2. Processed and prepared the data for graph building.
3. built the network using only the connected languages with mutual word count exceeding 100.
4. Community Detection using: Louvain Method.

Centrality Metrics:
  * Degree Centrality: Number of direct connections a language possesses
  * Closeness Centrality: Proximity of a language to all other languages 
  * Betweenness Centrality: Frequency ratio of how often a language connects other languages
  * Eigenvector Centrality: Determines a node’s rank from the number of neighbors it has

