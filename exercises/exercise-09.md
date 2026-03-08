# Exercise 09

This exercise is paired with [`lectures/09/lecture.md`](../lectures/09/lecture.md).
Keep the same topic and build on your connectivity and hub analysis from Exercises 04 and 08.

## Goal

Measure how your network responds to random failure versus targeted attack.

## Core Tasks

- Choose a graph or sample large enough to support repeated removals.
- Simulate random node removal and targeted removal. For the targeted case, use a clear rule such as highest degree or highest betweenness.
- After each removal step, track the size of the largest connected component or another justified resilience metric.
- Compare the random and targeted attack curves.
- Identify which structure makes your network robust or fragile.
- Propose one realistic design or policy change that would improve resilience in your domain.

## Topic Focus

1. **Student 1 - Karate Club Split:** Test whether removing faction leaders or boundary members fragments the club more than random removals.
2. **Student 2 - Southern Women Bipartite Network:** Remove key events or participants and see which side of the bipartite structure is more fragile.
3. **Student 3 - Florentine Families:** Test whether elite brokers are much more damaging to remove than randomly chosen families.
4. **Student 4 - Les Miserables Character Network:** Compare random removals with targeted removal of major or bridging characters.
5. **Student 5 - Facebook Ego Network:** Test whether the ego node and its strongest brokers are single points of failure.
6. **Student 6 - Wikipedia Vote Network:** Compare random loss of voters with targeted removal of highly connected or high-PageRank accounts.
7. **Student 7 - EU Email Core:** Evaluate whether the communication network survives random staff loss better than targeted removal of connectors.
8. **Student 8 - College Message Network:** Test whether message flow is resilient to random user loss but fragile to removal of active intermediaries.
9. **Student 9 - arXiv GR-QC Collaboration Network:** Compare random author removal with targeted removal of bridge authors.
10. **Student 10 - California Road Network:** Focus on targeted removal of high-betweenness intersections or bridge roads.
11. **Student 11 - Google Web Graph:** Compare the effect of random page removal against targeted removal of major link hubs.
12. **Student 12 - Amazon Co-purchasing Network:** Test whether targeted removal of popular products breaks the recommendation network faster than random loss.
13. **Student 13 - Epinions Trust/Distrust Network:** Run the structural test first without sign, then discuss how distrust might amplify fragility.
14. **Student 14 - Gowalla Geo-social Network:** Measure whether local social clusters remain connected after removing major connectors.
15. **Student 15 - Yeast Regulatory Network:** Test the effect of removing regulator hubs versus random operons.

## Hand In

- A plot or table comparing random and targeted removals.
- A short interpretation of the resilience gap.
- One proposed intervention to improve resilience.
