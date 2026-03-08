# Exercise 06

This exercise is paired with [`lectures/06/lecture.md`](../lectures/06/lecture.md).
Keep the same topic and compare your real network with a random baseline.

## Goal

Use the Erdős-Rényi model as a null model to test which properties of your topic are not explained by chance alone.

## Core Tasks

- Load your topic graph or its main connected sample.
- Build an Erdős-Rényi baseline with the same number of nodes and approximately the same density or edge count.
- Compare your real graph and the ER graph on degree distribution, clustering, average path length, and largest connected component size.
- State whether your graph looks more structured, more clustered, or more unequal than the random baseline.
- Write a short conclusion about which properties appear non-random.

## Topic Focus

1. **Student 1 - Karate Club Split:** Test whether the observed split and local clustering look stronger than chance.
2. **Student 2 - Southern Women Bipartite Network:** Compare a projection or simplified version to an ER baseline and note what the random model misses.
3. **Student 3 - Florentine Families:** Check whether elite-family structure is more clustered or brokered than a random graph of the same size.
4. **Student 4 - Les Miserables Character Network:** Compare narrative co-appearance structure to a random baseline and identify what randomness cannot capture.
5. **Student 5 - Facebook Ego Network:** Test whether local social clustering is much higher than in the ER baseline.
6. **Student 6 - Wikipedia Vote Network:** Compare direction-aware degree patterns and weak connectivity to a random directed baseline if feasible.
7. **Student 7 - EU Email Core:** Test whether the communication network is more clustered or more centralized than chance.
8. **Student 8 - College Message Network:** Compare the aggregated message graph with ER and discuss how time-dependent behavior is lost in the random baseline.
9. **Student 9 - arXiv GR-QC Collaboration Network:** Test whether collaboration produces stronger clustering than a random graph.
10. **Student 10 - California Road Network:** Show why a road network differs strongly from ER in degree distribution and spatially constrained structure.
11. **Student 11 - Google Web Graph:** Compare the web sample to a random baseline and note whether hubs or asymmetry already exceed random expectations.
12. **Student 12 - Amazon Co-purchasing Network:** Check whether product communities and hubs are stronger than a random baseline would predict.
13. **Student 13 - Epinions Trust/Distrust Network:** Ignore sign for the baseline comparison, then state which structural effects sign and direction likely add.
14. **Student 14 - Gowalla Geo-social Network:** Compare the friendship network with ER and discuss whether place-based clustering appears non-random.
15. **Student 15 - Yeast Regulatory Network:** Compare the regulatory sample to ER and explain why biological regulation is not well described by chance wiring.

## Hand In

- A short comparison table between your real graph and the ER baseline.
- One degree distribution plot or summary.
- A paragraph explaining which features are clearly non-random.
