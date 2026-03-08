# Exercise 05

This exercise is paired with [`lectures/05/lecture.md`](../lectures/05/lecture.md).
Keep the same topic and use the same graph unless your topic requires a projection or induced subgraph.

## Goal

Detect and compare communities in your network, then interpret what those communities mean in domain terms.

## Core Tasks

- Prepare the graph for community detection. If it is directed, signed, or bipartite, explain any conversion or projection you use.
- Apply at least two community detection approaches from this set: Louvain, label propagation, hierarchical clustering, clique percolation.
- Report the number of communities found by each method.
- Compute modularity for at least one partition.
- Identify one or more bridge nodes between communities.
- Visualize one community partition clearly.
- Write a short interpretation of what the communities represent in your topic.

## Topic Focus

1. **Student 1 - Karate Club Split:** Compare detected communities with the known split and identify the boundary members.
2. **Student 2 - Southern Women Bipartite Network:** Project the bipartite network to women or events and interpret the resulting communities.
3. **Student 3 - Florentine Families:** Test whether community structure aligns with historical family blocs or brokerage patterns.
4. **Student 4 - Les Miserables Character Network:** Detect character communities and interpret them as factions, scenes, or narrative modules.
5. **Student 5 - Facebook Ego Network:** Compare detected communities with available circles if your sample includes them.
6. **Student 6 - Wikipedia Vote Network:** Convert to an undirected view if needed, then identify voting blocs and bridge actors.
7. **Student 7 - EU Email Core:** Detect communication communities and compare them with any known organizational grouping if available.
8. **Student 8 - College Message Network:** Use the aggregated graph to identify messaging groups and possible campus subcommunities.
9. **Student 9 - arXiv GR-QC Collaboration Network:** Detect research communities and identify interdisciplinary bridge authors.
10. **Student 10 - California Road Network:** Test whether the road sample forms geographic communities or whether community detection is less informative here.
11. **Student 11 - Google Web Graph:** Detect clusters of pages and discuss whether they resemble domains, topics, or navigation structures.
12. **Student 12 - Amazon Co-purchasing Network:** Compare detected communities with product categories if category labels are available.
13. **Student 13 - Epinions Trust/Distrust Network:** Ignore sign for the main partition, then discuss whether sign may split or destabilize communities.
14. **Student 14 - Gowalla Geo-social Network:** Detect friendship communities and relate them to place-based or mobility-based subgroups.
15. **Student 15 - Yeast Regulatory Network:** Convert carefully if needed and interpret communities as possible functional modules.

## Hand In

- Community counts for at least two methods.
- One modularity score.
- One visualization with nodes colored by community.
- A short interpretation of what the communities mean and which nodes bridge them.
