# Exercise 04

This exercise is paired with [`lectures/04/lecture.md`](../lectures/04/lecture.md).
Keep the same topic and extend your earlier analysis.

## Goal

Use connectivity concepts to identify fragile structure, critical connectors, and simple resilience weaknesses in your topic.

## Core Tasks

- Load the same graph or prepared sample.
- Report the number and sizes of connected components. For directed graphs, report both weakly and strongly connected components.
- Identify articulation points or bridges when the graph type supports them. If your graph is directed, explain how you adapted the analysis.
- Remove one critical node and one critical edge, then measure what changes in connectivity.
- Report how the largest connected component changes after removal.
- Write a short resilience note explaining whether the network depends on a few critical connectors or has strong redundancy.

## Topic Focus

1. **Student 1 - Karate Club Split:** Test whether a few boundary members are crucial to keeping the full club connected.
2. **Student 2 - Southern Women Bipartite Network:** Check whether specific events or participants hold the bipartite structure together.
3. **Student 3 - Florentine Families:** Identify families whose removal would break brokerage paths between elite subgroups.
4. **Student 4 - Les Miserables Character Network:** Find characters whose removal fragments the co-appearance network into narrative subgroups.
5. **Student 5 - Facebook Ego Network:** Determine whether the ego node is the main articulation point or whether the neighborhood has backup ties.
6. **Student 6 - Wikipedia Vote Network:** Compare weak and strong connectivity, then test the effect of removing a key voting actor.
7. **Student 7 - EU Email Core:** Identify communication bottlenecks and test whether one sender or connector holds the sample together.
8. **Student 8 - College Message Network:** Examine whether message flow is dominated by a few connectors or already spread across several components.
9. **Student 9 - arXiv GR-QC Collaboration Network:** Test whether bridge authors connect otherwise separate collaboration clusters.
10. **Student 10 - California Road Network:** Focus on articulation intersections and bridge roads that most affect reachability.
11. **Student 11 - Google Web Graph:** Compare weak and strong connectivity and identify pages that appear structurally critical.
12. **Student 12 - Amazon Co-purchasing Network:** Test whether a few products act as bridges between categories or whether clusters remain connected without them.
13. **Student 13 - Epinions Trust/Distrust Network:** Analyze connectivity first without sign, then discuss whether distrust edges may hide fragile trust structure.
14. **Student 14 - Gowalla Geo-social Network:** Determine whether local friendship neighborhoods are weakly connected through a small set of users.
15. **Student 15 - Yeast Regulatory Network:** Identify regulator or operon nodes whose removal most changes reachability in the directed network.

## Hand In

- Component counts before and after removals.
- A list of articulation points or bridges, or a short note if none appear.
- One before/after visualization or summary table.
- A short explanation of your network's main vulnerability.
