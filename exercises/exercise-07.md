# Exercise 07

This exercise is paired with [`lectures/07/lecture.md`](../lectures/07/lecture.md).
Keep the same topic and extend your model comparison work from Exercise 06.

## Goal

Test whether your topic shows small-world behavior: short paths combined with stronger clustering than a comparable random network.

## Core Tasks

- Work on the whole graph if it is connected; otherwise use the largest connected component and say so.
- Measure average shortest path length and average clustering coefficient.
- Compare those values with an ER random graph of similar size and density.
- Decide whether your network has the small-world pattern: relatively short paths but substantially higher clustering than the random baseline.
- Identify one or two nodes or edges that act like shortcuts between otherwise local regions.
- Write a short explanation of whether the small-world idea fits your topic well.

## Topic Focus

1. **Student 1 - Karate Club Split:** Decide whether the club has short paths while still preserving strong local circles.
2. **Student 2 - Southern Women Bipartite Network:** Use a projection and test whether shared event attendance creates small-world structure.
3. **Student 3 - Florentine Families:** Check whether elite ties create a compact but clustered social world.
4. **Student 4 - Les Miserables Character Network:** Test whether narrative co-appearance creates dense local groups plus a few connecting shortcuts.
5. **Student 5 - Facebook Ego Network:** Decide whether the ego neighborhood is locally clustered but still easy to traverse.
6. **Student 6 - Wikipedia Vote Network:** Use a suitable undirected or weakly connected version to test whether political or procedural shortcuts appear.
7. **Student 7 - EU Email Core:** Determine whether communication stays clustered within local groups while a few connectors keep paths short.
8. **Student 8 - College Message Network:** Test whether aggregated messaging creates a small-world structure across active users.
9. **Student 9 - arXiv GR-QC Collaboration Network:** Check whether collaboration clusters are linked by a few interdisciplinary shortcuts.
10. **Student 10 - California Road Network:** Evaluate whether a road network fits the small-world pattern or whether spatial constraints dominate.
11. **Student 11 - Google Web Graph:** Test whether the web sample has short paths and discuss whether clustering is strong enough to call it small-world.
12. **Student 12 - Amazon Co-purchasing Network:** Decide whether co-purchase neighborhoods are highly clustered with a few cross-category shortcuts.
13. **Student 13 - Epinions Trust/Distrust Network:** Ignore sign for the main test, then discuss whether trust communities and bridges create small-world structure.
14. **Student 14 - Gowalla Geo-social Network:** Evaluate whether friendship plus geography produces clustered local groups with a few long-range ties.
15. **Student 15 - Yeast Regulatory Network:** Test carefully on an undirected simplification if needed and discuss whether regulation is locally clustered.

## Hand In

- Your clustering and path-length values.
- The same values for a random baseline.
- A short conclusion stating whether your network is small-world, partially small-world, or not convincingly small-world.
