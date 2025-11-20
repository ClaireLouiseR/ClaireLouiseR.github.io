# Leveraging Network Science to Enhance Australia’s Indo-Pacific Diplomacy

**Summary**  
I analysed diplomatic and influence networks to identify where Australia can most effectively deepen ties and broker regional influence across the Indo-Pacific.

[Open the notebook →](analysis.ipynb){ .md-button }

**Data**  
- **Lowy Institute Global Diplomacy Index (2016–2023):** posts across 66 countries, used to build a weighted, directed global diplomacy graph.
- **Lowy Institute Asia Power Index (API):** constructed three regional “network power” graphs from API attributes — **online search interest (OSI)**, **foreign capital investment (FCI)** and **diplomatic dialogues (DD)**.
**Methods**  
Weighted, directed graphs; metrics included **betweenness centrality** (on inverted edge weights), **PageRank**, **HITS (authorities/hubs)**, **weighted in/out degree**, **clustering coefficient**, and **Louvain community detection** with **modularity** and **Adjusted Rand Index (ARI)** to compare community structures across networks. 

