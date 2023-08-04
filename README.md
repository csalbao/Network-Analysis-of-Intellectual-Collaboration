# Connecting Minds: A Network Analysis of Intellectual Collaboration

This repository contains code and associated files used in the analysis of co-authorship network among AI research authors. The data was derived from papers in the field of AI, published from 2019 to 2023 and indexed in the ArXiv dataset provided by Cornell University.

The objective of this project is to understand the underlying structure of collaborations in AI research by analyzing the co-authorship network. We primarily focus on the largest connected component of the network, with a specific focus on a subgraph of top authors and their first-step neighbors.

Key areas of analysis include:

- Centrality Measures: Calculating degree, betweenness, closeness, eigenvector centrality, and PageRank to identify key authors in the network.
- Community Detection: Uncovering communities within the network using the Louvain method, providing insights into how researchers cluster together in their collaborations.
