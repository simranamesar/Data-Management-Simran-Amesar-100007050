# Facebook Social Network Analysis using Gephi

## Dataset Information

This project analyzes the Facebook Social Circles dataset from the Stanford Network Analysis Project (SNAP).

Dataset Source:
https://snap.stanford.edu/data/ego-Facebook.html

Dataset File Used:
- facebook_combined.txt.gz

Converted File:
- facebook_edges.csv

Software Used:
- Gephi

---

# Project Objective

The objective of this project is to analyze a real-world Facebook friendship network using Gephi and apply network analysis techniques such as:

- Degree Centrality
- Betweenness Centrality
- Community Detection (Modularity)
- Network Filtering
- Graph Visualization

---

# Network Statistics

| Metric | Value |
|---|---|
| Nodes | 4039 |
| Edges | 88234 |
| Graph Type | Undirected |
| Average Degree | 43.691 |
| Graph Density | 0.011 |
| Network Diameter | 8 |
| Average Path Length | 3.693 |
| Modularity Score | 0.835 |

---

# Tasks Performed

## 1. Importing Dataset
- Imported the Facebook dataset into Gephi
- Selected graph type as Undirected

## 2. Applying Layout
- Applied Yifan Hu layout for better visualization
- Adjusted spacing and structure for readability

## 3. Degree Centrality
- Calculated degree centrality
- Identified highly connected nodes

### Top 5 Nodes by Degree

| Rank | Node ID | Degree |
|---|---|---|
| 1 | 107 | 1045 |
| 2 | 1684 | 792 |
| 3 | 1912 | 755 |
| 4 | 3437 | 547 |
| 5 | 0 | 347 |

---

# Betweenness Centrality

Calculated betweenness centrality to identify bridge nodes between communities.

### Top Bridge Nodes

| Rank | Node ID |
|---|---|
| 1 | 107 |
| 2 | 1684 |
| 3 | 1912 |
| 4 | 3437 |
| 5 | 0 |

These nodes play an important role in connecting different communities.

---

# Community Detection

- Ran the Modularity algorithm
- Colored nodes according to modularity class
- Identified multiple social communities

The network showed strong clustering behavior with a modularity score of 0.835.

---

# Degree Filtering

Applied a degree filter:

Degree >= 5

Purpose:
- Remove weakly connected nodes
- Improve visualization clarity
- Focus on the core structure of the network

---

# Files Included

| File Name | Description |
|---|---|
| facebook_edges.csv | Converted CSV edge list |
| facebook_network.gephi | Gephi project file |
| full_network.png | Full network visualization |
| community_network.png | Community/modularity visualization |
| report.pdf / report.docx | Final report |

---

# Observations

- The network contains densely connected communities.
- Certain nodes act as hubs with very high connectivity.
- Some nodes function as bridges between communities.
- The Facebook graph demonstrates small-world network characteristics.

---

# Learning Outcomes

Through this project, I learned:

- How to analyze large-scale social networks
- How centrality measures identify important nodes
- How modularity detects communities
- How filtering improves network interpretation
- Practical usage of Gephi for visualization and analysis

---

# Conclusion

This project demonstrated how graph theory and network analysis can be applied to social media data. Using Gephi helped visualize relationships, detect communities, and identify influential users within the Facebook social network.
