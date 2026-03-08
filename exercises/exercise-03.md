# Exercise 03

This exercise is paired with [`lectures/03/lecture.md`](../lectures/03/lecture.md).
Keep the same topic from [`topics.md`](./topics.md) and build directly on your work from [`exercise-02.md`](./exercise-02.md).

## Goal

Use Lecture 03 metrics to move from basic graph description to node importance and structural interpretation.

## Core Tasks

- Load the same graph or prepared sample you used in Exercise 02.
- Compute degree-based measures. For directed graphs, report in-degree and out-degree separately.
- Compute at least three centrality measures from this set: degree, betweenness, closeness, eigenvector, PageRank.
- Compute density, average clustering, and one path-based metric such as diameter, eccentricity, or average shortest path length.
- If the graph is disconnected, run path-based metrics on the largest connected component and state that choice clearly.
- Produce one visualization where node size or color reflects a centrality score.
- Write a short interpretation of which nodes are important and why different metrics do not always agree.

## Topic Focus

1. **Student 1 - Karate Club Split:** Compare nodes `0` and `33`, then identify one high-betweenness boundary node between the two factions.
2. **Student 2 - Southern Women Bipartite Network:** Report centrality separately for women and events, then create one projection and compare what changes.
3. **Student 3 - Florentine Families:** Identify which family leads in degree, which leads in betweenness, and whether they are the same.
4. **Student 4 - Les Miserables Character Network:** Compare the most connected characters with the strongest bridge characters and relate this to narrative structure.
5. **Student 5 - Facebook Ego Network:** Compare the ego node with its strongest local brokers and decide whether local influence is centralized or shared.
6. **Student 6 - Wikipedia Vote Network:** Compare top in-degree, top out-degree, and top PageRank nodes to show how direction changes importance.
7. **Student 7 - EU Email Core:** Distinguish sender hubs, receiver hubs, and connector nodes using in-degree, out-degree, and betweenness.
8. **Student 8 - College Message Network:** Use the aggregated graph and identify users that look central by volume versus reach.
9. **Student 9 - arXiv GR-QC Collaboration Network:** Compare highly collaborative authors with bridge authors that connect local clusters.
10. **Student 10 - California Road Network:** Identify intersections with high betweenness and explain why they matter more than high-degree intersections.
11. **Student 11 - Google Web Graph:** Compare top in-link targets with top out-link sources and discuss whether PageRank aligns more with one side.
12. **Student 12 - Amazon Co-purchasing Network:** Identify products that look like hubs versus products that connect otherwise separate product groups.
13. **Student 13 - Epinions Trust/Distrust Network:** First ignore sign and analyze centrality, then explain how trust and distrust could change the meaning of a central node.
14. **Student 14 - Gowalla Geo-social Network:** Identify local friendship hubs and comment on whether they seem neighborhood-based or globally connected.
15. **Student 15 - Yeast Regulatory Network:** Separate regulator-like nodes from target-like nodes using out-degree, in-degree, and betweenness.

## Hand In

- A table of your main metrics.
- One centrality-ranked list of the top 5 nodes.
- One annotated visualization.
- A short interpretation explaining what centrality reveals about your topic.
