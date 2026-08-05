# Data-Analysis-and-Visualization

A collection of applied analytics and visual-storytelling projects spanning sports, global development, transportation, networks, clustering, outlier detection, and longitudinal analysis.

The repository demonstrates how the same dataset can be explored through statistical analysis, interactive dashboards, network layouts, dimension reduction, and narrative visualization.

## Portfolio Overview

| Project | Main techniques | Deliverable |
|---|---|---|
| Commute Speed Analysis | Harmonic mean, weekly and annual seasonality, anomaly interpretation | DOCX report |
| Global Football Talent Flows | Longitudinal FIFA analysis, network modeling, K-means, MDS, LOF, Tableau | PDF report and presentation |
| NBA Player Social Graph | Weighted teammate network, centrality, modularity, Gephi layouts | PDF report |
| Olympic Track & Field | Data-quality review, calculated fields, scatterplots, bump charts, NYT-style storytelling | DOCX report |
| NBA Sports Analytics | Tableau historical views, PCA, MDS, LOF, player similarity | PDF report |
| Gapminder Development Analysis | Connected scatterplots, MDS, K-means, development outliers | DOCX report |

## 1. Commute Speed Analysis

This project analyzes daily commute speeds from **January 2022 through December 2023**.

The commute is multimodal:

- Weekdays: train travel
- Weekends: bicycle travel

The analysis uses the harmonic mean of morning and evening speeds and identifies:

- A strong seven-day weekday/weekend cycle
- Weather-related annual variation
- Higher volatility in cycling speeds
- Stable weekday train speeds
- No meaningful long-term upward or downward trend

**File**

```text
Commute Speed AnalysisProblem1_Problem2_Problem3_Solution.docx
```

## 2. Global Football Talent Flows: FIFA 2017-2022

This project combines six FIFA seasons into a longitudinal player-level dataset and examines relationships among:

- Players
- Nationalities
- Positions
- Clubs
- Leagues
- Ratings
- Potential
- Market value

### Methods

- Tableau dashboards
- Year-over-year market-value analysis
- Bump charts for national talent rankings
- Position-depth heatmaps
- K-means clustering
- Multidimensional Scaling
- Local Outlier Factor
- Network-oriented talent-flow analysis

The study focuses on structural patterns in professional football rather than match results.

**Files**

```text
FIFA analytics report.pdf
FIFA_Analytics_2017-2022.pptx
```

A dedicated version of this work is also presented in:

[`fifa-global-talent-analytics`](https://github.com/TriptiSingh-Developer/fifa-global-talent-analytics)

## 3. NBA Player Social Graph

A weighted social network was created from an NBA per-36-minute dataset.

### Data and Graph

- Cleaned dataset: **31,951 rows and 32 columns**
- Selected network: **25 players**
- Weighted edges: **49**
- Edge meaning: number of seasons two players were teammates

### Network Measures

- Eigenvector centrality
- PageRank
- Betweenness centrality
- Closeness centrality
- Weighted degree
- Clustering coefficient
- Modularity and community structure

### Layouts

- ForceAtlas2
- Fruchterman-Reingold
- Circular layout

Python was used to prepare node and edge tables, and Gephi was used for network analysis and visualization.

**File**

```text
NBAPlayerSocialGraph_Analysis.pdf
```

## 4. Olympic Track & Field Visualizations

This analysis reviews an Olympic medal-results dataset containing:

- **2,161 records**
- **14 columns**
- Coverage from **1896 through 2016**

The project identifies data-quality issues involving:

- Missing fields
- Inconsistent event labels
- Mixed units
- Character-encoding problems
- Incorrect country labels
- Ambiguous record flags

### Visual Work

- Single-event sprint scatterplots
- Full-field performance comparisons
- NYT-inspired distance-behind-leader visualization
- Medal-trend line charts
- Country ranking bump charts
- Connected scatterplots for life expectancy and life satisfaction

Excel calculated fields and Tableau visualizations are used to convert timing differences into intuitive performance comparisons.

**File**

```text
Olympic Track & Field Analysis & Visualizations.docx
```

## 5. NBA Sports Analytics

This project recreates and extends sports visualizations using historical NBA data.

### Tableau Analysis

- Career cumulative points
- Career points by age
- Two-point versus three-point scoring composition
- Historical scorer comparisons

### Player Similarity and Outliers

- Principal Component Analysis
- Multidimensional Scaling
- Local Outlier Factor
- Position-based player clusters
- Identification of unusual per-36 statistical profiles

The project combines Tableau visual storytelling with Orange-based exploratory machine learning.

**File**

```text
Sports Analytics.pdf
```

## 6. Gapminder Global Development Analysis

This project recreates a Hans Rosling-style development visualization and studies country trajectories using GDP per capita and life expectancy.

### Workflow

1. Reshape long-format country-year data into wide format with Python
2. Apply MDS in Orange
3. Export two-dimensional coordinates
4. Visualize clusters and trajectories in Tableau
5. Detect economic and health-development outliers

### Methods

- Connected scatterplots
- Multidimensional Scaling
- K-means clustering
- Cluster centroids
- Box plots
- Outlier interpretation

**File**

```text
gapminder_explaination.docx
```

## Technology Stack

| Area | Tools |
|---|---|
| Visualization | Tableau, Excel |
| Network analysis | Gephi, ForceAtlas2, Fruchterman-Reingold |
| Analytical workflows | Python, Pandas |
| Visual machine learning | Orange |
| Statistical methods | K-means, PCA, MDS, LOF |
| Communication | Reports, presentations, annotations, interactive storytelling |

## Current Repository Structure

```text
Data-Analysis-and-Visualization/
├── README.md
├── Commute Speed AnalysisProblem1_Problem2_Problem3_Solution.docx
├── FIFA analytics report.pdf
├── FIFA_Analytics_2017-2022.pptx
├── NBAPlayerSocialGraph_Analysis.pdf
├── Olympic Track & Field Analysis & Visualizations.docx
├── Sports Analytics.pdf
└── gapminder_explaination.docx
```
## Skills Demonstrated

- Exploratory data analysis
- Data cleaning and quality assessment
- Tableau dashboard development
- Visual storytelling
- Network analysis
- Graph centrality and community detection
- PCA, MDS, K-means, and LOF
- Longitudinal and seasonal analysis
- Technical reporting and presentation
