# Exercise 02

This exercise is paired with [`lectures/02/lecture.md`](../lectures/02/lecture.md).
You will keep the same topic for the rest of the course. This exercise is only the Lecture 02 foundation for that topic.
Later exercises continue this same topic through [`exercise-03.md`](./exercise-03.md) to [`exercise-11.md`](./exercise-11.md).

## Intro
Use this handout to complete the first pass on your assigned topic using only Lecture 02 concepts.
In this lecture, your job is to load the graph, represent it correctly, and describe its basic structure.
In later lectures, you will return to the same topic and extend this work with new methods.

Use a fixed 60-minute flow:

- 10 minutes: set up your environment and load the dataset.
- 15 minutes: build the graph object and check it loaded correctly.
- 15 minutes: compute and record key metrics (nodes, edges, density, degree stats, connectivity).
- 10 minutes: pull one example path and one cycle, then print a small adjacency-list or matrix snippet.
- 10 minutes: draw the full graph or a representative sample and add a short written reflection.

Use NetworkX for this lab because it handles directed, weighted, and bipartite graphs with the same core workflow.
For bigger datasets, use prepared sample versions so analysis stays fast and visualizations stay readable.

## Card Instructions

1. **Student 1 — Karate Club Split**
   - Work on Zachary’s Karate Club, a classic small social network built into NetworkX; nodes include a club label and edges carry weights.
   - Load the full graph, report nodes, edges, density, degrees, one shortest path, and one cycle.
   - Draw the graph with nodes colored by club.
   - Write 4-5 sentences on what the basic structure already suggests.

2. **Student 2 — Southern Women Bipartite Network**
   - Work on the Davis Southern Women network, a built-in bipartite graph of people and events.
   - Load the graph, separate the two node sets, compute degree on both sides, draw a two-layer visualization.
   - Produce a small adjacency excerpt showing which women attended which events.
   - Add a short note explaining why this is bipartite and what a one-mode projection would mean.

3. **Student 3 — Florentine Families**
   - Work on the Florentine families graph, a classic historical social network in NetworkX.
   - Load the full graph, report nodes, edges, density, connected components, and the three highest-degree families.
   - Find one shortest path between two non-adjacent families and comment on what the path suggests structurally.

4. **Student 4 — Les Misérables Character Network**
   - Work on the Les Misérables co-appearance network of characters, available in NetworkX.
   - Load the graph, inspect node and edge attributes, list the most connected characters.
   - Draw either the full graph or a 15-node core made from highest-degree characters.
   - Show one path between two non-adjacent characters and explain what that path means in graph terms.

5. **Student 5 — Facebook Ego Network**
   - Use one ego network from the SNAP Facebook social-circles collection.
   - Build the graph, report density, connectedness, and degree distribution basics.
   - Visualize the ego node and its 1-hop neighborhood.
   - Write a short paragraph on whether the local structure looks like one group or multiple circles.

6. **Student 6 — Wikipedia Vote Network**
   - Work on the Wikipedia admin-election vote network, where directed edges represent votes in requests for adminship.
   - Use a provided sample subgraph.
   - Build a directed graph, compare top in-degree and top out-degree nodes, check weakly vs strongly connected components.
   - Draw a small directed visualization with arrows.
   - End with a short note on what in-degree and out-degree mean in this setting.

7. **Student 7 — EU Email Core**
   - Use a prepared 200–300 node sample.
   - Build a directed graph, report in-degree, out-degree, density, and weakly connected components.
   - Visualize the sample.
   - Write a short interpretation of which nodes currently look like sender hubs, receiver hubs, or connectors.

8. **Student 8 — College Message Network**
   - Work on the CollegeMsg dataset, a temporal directed message network.
   - Start from the first 500 messages or one day of data.
   - Build an aggregated static graph from those timestamped interactions, then compare the raw interactions with the static graph you created.
   - Report nodes, edges, degrees, components, and one example path in the aggregated graph.

9. **Student 9 — arXiv GR-QC Collaboration Network**
   - Use a sample from the largest connected component.
   - Report nodes, edges, density, degree statistics, clustering coefficient.
   - Find one shortest path between two authors.
   - Draw the sample and comment on whether it looks like one dense group or many local clusters.

10. **Student 10 — California Road Network**
    - Use a prepared local sample rather than the full graph.
    - Compute nodes, edges, degree statistics, connected components, and a shortest path between sampled intersections.
    - Draw the sample and note how a road network differs from a social network at the level of basic graph structure.

11. **Student 11 — Google Web Graph**
    - Use a 200–300 node sample.
    - Build a directed graph, compare in-degree vs out-degree, examine weakly and strongly connected components.
    - Visualize a small neighborhood.
    - Explain why in-links and out-links are not the same on the web.

12. **Student 12 — Amazon Co-purchasing Network**
    - Use one provided category sample or a small induced subgraph.
    - Report nodes, edges, density, connected components, and highest-degree products.
    - Explain what a high-degree node might mean in a co-purchase graph.

13. **Student 13 — Epinions Trust/Distrust Network**
    - Build a directed graph and keep the sign as an edge attribute.
    - For the first attempt, report positive-edge count, negative-edge count, nodes, edges, and degree statistics.
    - First analyze topology while ignoring sign, then add 3-4 sentences on how sign changes interpretation.

14. **Student 14 — Gowalla Geo-social Network**
    - Use only the friendship graph or one ego-network sample.
    - Report nodes, edges, density, components, and visualize a small local neighborhood.
    - As an extension, inspect a few users' check-ins and note whether ties reflect shared places.

15. **Student 15 — Yeast Regulatory Network**
    - Use a small prepared subgraph.
    - Build a signed directed graph, report in-degree and out-degree.
    - Identify likely regulator-like and target-like nodes.
    - Draw the network with edge labels or colors for sign.
    - End with a short note on how this differs from a friendship network at the Lecture 02 level.

## Outro

Finish Exercise 02 when you can clearly answer:

1. What are your node/edge counts, density, and degree pattern?
2. What is one meaningful shortest path or cycle in this graph?
3. What does your sketch or sampled visualization tell you about structure?
4. How did Lecture 02 concepts help you describe this topic in graph terms?

Before you hand in, include:

- a brief method note (commands used),
- printed metrics and a tiny table/summary,
- one screenshot or rendered graph,
- and a 3–5 sentence interpretation.
