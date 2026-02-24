# NBA Player Analysis & Visualization

## Overview
This project explores NBA player performance through a combination of editorial-style visualizations and network analysis. Using public NBA datasets, the analysis highlights scoring style differences, league-wide shooting trends, and structural relationships between players.

---

## Visualizations

### Scoring Style Distribution (NYT-Inspired)
An editorial-style scatterplot comparing the share of two-point and three-point scoring among top NBA players. This visualization highlights differences in offensive styles, distinguishing perimeter-oriented shooters from interior-focused scorers.

### Evolution of Shot Selection in the NBA
A stacked area chart showing how the distribution of two-point shots, three-point shots, and free throws has evolved over time, including the introduction and rapid growth of the three-point shot.

### NBA Top 50 Player Teammate Network
A network visualization modeling teammate relationships among NBA players. Nodes represent players, edges indicate shared team seasons, node size reflects average points per 36 minutes, and colors represent communities identified using Louvain community detection.

---

## Data
- `seasons_stats.csv`: Season-level NBA statistics used for NYT-inspired editorial visualizations of scoring styles and shot selection trends.
- `Per 36 Minutes.csv`: Per-36-minute player statistics used to construct the player teammate network.

Raw data is not included in this repository.

---

## Tools
Python (Pandas, NetworkX), Tableau
