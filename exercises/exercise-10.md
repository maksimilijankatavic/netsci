# Exercise 10

This exercise is paired with [`lectures/10/lecture.md`](../lectures/10/lecture.md).
Keep the same topic and study one dynamic process on top of your network structure.

## Goal

Move from static structure to a simple dynamic model such as diffusion, contagion, opinion change, or cascading failure.

## Core Tasks

- Choose one dynamic model that fits your topic reasonably well.
- Define the state of each node and the transition rule clearly.
- Select initial seed nodes and justify them. At least one run should use a node identified as important in earlier exercises.
- Run the model over time and record how the process evolves.
- Compare at least two scenarios, such as random seed versus central seed, or low probability versus high probability.
- Write a short interpretation of how network structure changes the outcome.

## Recommended Dynamic Lens by Topic

1. **Student 1 - Karate Club Split:** Use a voter model or threshold model for opinion alignment between the two factions.
2. **Student 2 - Southern Women Bipartite Network:** Use a contagion or adoption model on a projection to simulate event or norm spread.
3. **Student 3 - Florentine Families:** Model alliance adoption, rumor spread, or influence diffusion among families.
4. **Student 4 - Les Miserables Character Network:** Use an information-spread model to see which characters accelerate diffusion across the story network.
5. **Student 5 - Facebook Ego Network:** Use a threshold or cascade model for behavior adoption inside the ego network.
6. **Student 6 - Wikipedia Vote Network:** Use a directed influence or cascade model to simulate how support spreads in an election network.
7. **Student 7 - EU Email Core:** Use a simple information diffusion or SIR-style spread on the directed email graph.
8. **Student 8 - College Message Network:** Compare diffusion on the aggregated graph with a time-aware interpretation if timestamps are available.
9. **Student 9 - arXiv GR-QC Collaboration Network:** Simulate diffusion of a new method or collaboration opportunity across authors.
10. **Student 10 - California Road Network:** Use a cascading-failure or blockage-spread model rather than a social contagion model.
11. **Student 11 - Google Web Graph:** Use a directed information-spread or random-surfer style process to study reach.
12. **Student 12 - Amazon Co-purchasing Network:** Model adoption or recommendation cascades starting from a popular product.
13. **Student 13 - Epinions Trust/Distrust Network:** Use a trust-aware opinion or diffusion model and explain how sign alters spread.
14. **Student 14 - Gowalla Geo-social Network:** Model adoption of a place, app feature, or mobility-related behavior through friendship ties.
15. **Student 15 - Yeast Regulatory Network:** Use an activation or cascade model in which regulators influence downstream targets.

## Hand In

- A clear model description.
- A time-series plot, step table, or compact simulation log.
- A comparison between two scenarios.
- A short explanation of how your network structure shaped the dynamics.
