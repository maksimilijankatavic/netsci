# Course Topics

Each student keeps the same topic for the full course. The goal is not to switch datasets every lecture. The goal is to build one sustained network analysis project and extend it as new lecture concepts arrive.

Use `Exercise 02` only as the first technical entry point. In Lecture 02, you will load the graph, inspect its basic structure, and produce a first simple analysis. In later lectures, you will return to the same topic and apply new ideas such as centrality, communities, diffusion, resilience, temporal structure, or multilayer analysis when relevant.
The exercise sequence now runs from [`exercise-02.md`](./exercise-02.md) through [`exercise-11.md`](./exercise-11.md), and each step should build on the same topic rather than replacing it.

1. **Student 1 - Karate Club Split**
   - **Problem:** Can the structure of a small social network reveal an internal group split before we are told the outcome?
   - **Why this works across lectures:** Start with basic graph structure, then revisit the same network for centrality, communities, and prediction of the split.
   - **References:** [Exercise 02](./exercise-02.md), [Lecture 02](../lectures/02/lecture.md), [NetworkX generators](https://networkx.org/documentation/stable/reference/generators.html)

2. **Student 2 - Southern Women Bipartite Network**
   - **Problem:** How do attendance patterns between people and events create visible social structure?
   - **Why this works across lectures:** Begin with bipartite graph basics, then extend to projections, similarity, centrality, and community structure.
   - **References:** [Exercise 02](./exercise-02.md), [Lecture 02](../lectures/02/lecture.md), [NetworkX generators](https://networkx.org/documentation/stable/reference/generators.html)

3. **Student 3 - Florentine Families**
   - **Problem:** Which families appear most powerful, and how much of that power comes from brokerage rather than simple popularity?
   - **Why this works across lectures:** This topic supports degree, betweenness, communities, and interpretation of elite social structure over the full course.
   - **References:** [Exercise 02](./exercise-02.md), [Lecture 02](../lectures/02/lecture.md), [NetworkX generators](https://networkx.org/documentation/stable/reference/generators.html)

4. **Student 4 - Les Miserables Character Network**
   - **Problem:** How does the structure of character co-appearance help explain narrative importance and grouping?
   - **Why this works across lectures:** Start with paths and connectivity, then build toward weighted centrality, clusters, and narrative communities.
   - **References:** [Exercise 02](./exercise-02.md), [Lecture 02](../lectures/02/lecture.md)

5. **Student 5 - Facebook Ego Network**
   - **Problem:** Does one person's local social world look like a single group or several overlapping circles?
   - **Why this works across lectures:** This topic grows naturally from neighborhood structure to communities, link prediction, and ego-network interpretation.
   - **References:** [Exercise 02](./exercise-02.md), [SNAP Facebook ego data](https://snap.stanford.edu/data/ego-Facebook.html)

6. **Student 6 - Wikipedia Vote Network**
   - **Problem:** In a directed voting network, who influences outcomes and how does direction change what counts as importance?
   - **Why this works across lectures:** It begins with directed graph basics and later supports PageRank, HITS, reciprocity, and influence analysis.
   - **References:** [Exercise 02](./exercise-02.md), [SNAP Wikipedia vote data](https://snap.stanford.edu/data/wiki-Vote.html)

7. **Student 7 - EU Email Core**
   - **Problem:** What roles emerge in an institutional email network, and who acts as a sender hub, receiver hub, or connector?
   - **Why this works across lectures:** The same graph supports directed connectivity, centrality, communities, and communication-role analysis.
   - **References:** [Exercise 02](./exercise-02.md), [SNAP email-Eu-core data](https://snap.stanford.edu/data/email-Eu-core.html)

8. **Student 8 - College Message Network**
   - **Problem:** How does a message network change when time is ignored, and what is lost when temporal activity is collapsed into a static graph?
   - **Why this works across lectures:** Students can begin with an aggregated graph, then revisit time, growth, bursts, and temporal patterns later.
   - **References:** [Exercise 02](./exercise-02.md), [SNAP CollegeMsg data](https://snap.stanford.edu/data/CollegeMsg.html)

9. **Student 9 - arXiv GR-QC Collaboration Network**
   - **Problem:** Does scientific collaboration form one cohesive community or many local clusters connected by a few bridges?
   - **Why this works across lectures:** This topic supports clustering, components, centrality, small-world reasoning, and collaboration structure.
   - **References:** [Exercise 02](./exercise-02.md), [SNAP ca-GrQc data](https://snap.stanford.edu/data/ca-GrQc.html)

10. **Student 10 - California Road Network**
    - **Problem:** How is a road network structurally different from a social network, and what does that mean for paths and robustness?
    - **Why this works across lectures:** The topic starts with graph basics and later grows into shortest paths, vulnerability, and resilience analysis.
    - **References:** [Exercise 02](./exercise-02.md), [SNAP roadNet-CA data](https://snap.stanford.edu/data/roadNet-CA.html)

11. **Student 11 - Google Web Graph**
    - **Problem:** In a web graph, what is the difference between being heavily linked to and heavily linking out?
    - **Why this works across lectures:** It supports directed structure first, then ranking methods such as PageRank and HITS in later lectures.
    - **References:** [Exercise 02](./exercise-02.md), [SNAP web-Google data](https://snap.stanford.edu/data/web-Google.html)

12. **Student 12 - Amazon Co-purchasing Network**
    - **Problem:** Which products sit at the center of a co-purchasing network, and do those products define meaningful product communities?
    - **Why this works across lectures:** Start with degree and connectivity, then extend to communities, recommendation logic, and link prediction.
    - **References:** [Exercise 02](./exercise-02.md), [SNAP Amazon co-purchasing data](https://snap.stanford.edu/data/com-Amazon.html)

13. **Student 13 - Epinions Trust/Distrust Network**
    - **Problem:** How does a network change when edges carry trust or distrust rather than only connection?
    - **Why this works across lectures:** The topic begins with directed structure and later supports signed analysis, balance, and trust propagation.
    - **References:** [Exercise 02](./exercise-02.md), [SNAP Epinions signed data](https://snap.stanford.edu/data/soc-sign-epinions.html)

14. **Student 14 - Gowalla Geo-social Network**
    - **Problem:** Do friendship ties align with shared movement and location behavior?
    - **Why this works across lectures:** Start with the friendship graph, then build toward geographic interpretation, mobility, and location-aware community structure.
    - **References:** [Exercise 02](./exercise-02.md), [SNAP Gowalla data](https://snap.stanford.edu/data/loc-Gowalla.html)

15. **Student 15 - Yeast Regulatory Network**
    - **Problem:** How do direction and positive or negative regulation shape the structure of a biological network?
    - **Why this works across lectures:** This topic begins with signed directed graph basics and can later support motifs, regulation roles, and biological interpretation.
    - **References:** [Exercise 02](./exercise-02.md), [Lecture 02](../lectures/02/lecture.md)
