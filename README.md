# Wide Receiver Route Tree Analysis
This project explores wide receiver performance and efficiency using NFL play-by-play and Next Gen Stats data. The focus is on route-level efficiency, catch rate patterns, and player archetypes through clustering, with an emphasis on clear, aesthetic data visualizations and modeling.

This repository is part of a broader initiative to explore sports analytics projects.

🧰 Tools & Technologies
- Python (3.10+)
- Libraries:
  - pandas, numpy
  - plotly, matplotlib, seaborn (for data visualization)
  - scikit-learn (for clustering + modeling)
- Data Source:
  - nfl_data_py to access play-by-play + Next Gen Stats data

📊 Key Insights
- Zone-Based Catch Rates: Visualized catch rate by route depth and location to reveal versatile WRs across field zones.
- Efficiency Metrics:
  - Used EPA per Target and Catch Percentage for comparison.
  - Created scatterplots with Separation, YAC Over Expected, and Air Yards per Target to contextualize WR performance.
- Player Archetypes via Clustering: Identified 3 clusters of wide receivers:
  - 🟥 Deep Threats
  - 🟩 YAC Monsters
  - 🟦 Possession WRs
- Performance Comparison by Archetype: Used boxplots to show how catch rate and EPA per target differ across WR styles.
