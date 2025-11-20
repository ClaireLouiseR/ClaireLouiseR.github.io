# Leveraging Network Science to Enhance Australia’s Indo-Pacific Diplomacy

[Open the notebook →](analysis.ipynb){ .md-button }
[Download the report (PDF) →](assets/NetworkScience_Report.pdf){ .md-button target="_blank" }

## Summary
I analysed diplomatic and influence networks to identify where Australia can most effectively deepen ties and broker regional influence across the Indo-Pacific.

## Data
- **Lowy Global Diplomacy Index (2016–2023):** counts of overseas posts across 66 countries to build a weighted, directed diplomacy graph.  
- **Lowy Asia Power Index:** three “network power” graphs from API attributes — **online search interest (OSI)**, **foreign capital investment (FCI)**, and **diplomatic dialogues (DD)**.

## Methods
- Weighted, directed graphs (plus one undirected graph for diplomatic dialogues)  
- Centralities: **betweenness**, **PageRank**, **HITS (hubs/authorities)**  
- **Weighted in/out degree**, **clustering coefficient**  
- **Louvain** communities; compared structures with **Adjusted Rand Index (ARI)**

## Selected results

- **Diplomatic footprint:** Australia has expanded posts in **Oceania**, but remains mid-pack for total posts relative to peers with similar GDP. Diversifying posts beyond Oceania would broaden reach.

- **Brokerage via diplomatic dialogues (DD):** High **PageRank** (and brokerage metrics) indicate Australia is well placed to **convene** and broker across Indo-Pacific diplomatic fora. Deepen ties with **Indonesia, Japan, India** while balancing US alignment.

- **Attention flows (OSI):** Australia is a **net receiver** of attention (≈ **6th** by weighted in-degree). Cultural exchange and business initiatives with **India** and **Japan** are likely to lift visibility.

- **Investment flows (FCI):** **China** dominates as an investment hub; Australia’s hub score is lower. Emphasise **quality over volume** in sectors of advantage (e.g., critical minerals, renewables, education), leveraging governance and reliability.

- **Community structure:** Stable regional ties to **New Zealand**; economic links cluster with **Southeast Asia**. **OSI** and **DD** communities overlap moderately; **FCI** forms distinct blocs → different policy levers by network.

- **Actionable next steps:** Target brokerage opportunities in triads (e.g., **Japan–India–Australia**, ASEAN pairings), strengthen weak ties identified by low edge weights, and track changes **2016–2023** to sequence postings and dialogues.


## Selected Visuals
![Top OSI flows](assets/top_25_online_search_interest_flows.png)

**Full repo:** https://github.com/ClaireLouiseR/COMP8880

