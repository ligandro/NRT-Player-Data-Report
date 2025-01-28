# NRT-Player-Data-Report

<p align="center">
  <img width="40%" src="./images/NRT.png"> &nbsp &nbsp
</p>

# Project Background
 [Neurotactic](https://x.com/neuroTactic_)   specializes in data-driven football analysis, offering insights for individual players, clubs, and national teams. Our expertise helps optimize performance, strategy, and decision-making by leveraging advanced analytics to unlock the full potential of players and teams. Earlier, we used to make player reports using Tableau which took atleast1-2 days to make. I was tasked with created an quick automated data report generator that can generate the report in 3-4 mins by simply running some code.

## Details
- Used for ad-hoc analysis as required by our team's player performance analyst.
- Increased efficiency by reducing the time needed to create reports compared to manually building them in Tableau.
- Made using Python and libraries such as Pandas and Matplotlib.
  
## Data 
The data used in from Wyscout. It is tabular with multiple columns containing different type of player stats.

# 1. Player Data Report
   Used to identify key player strengths, and visualize their standout attributes. 
   
  - **Key Features**

    Filtering: Select player positions and apply filters for age and minutes played.
    
    Statistical Analysis: Compute percentile and z-scores for each statistic.
    
    Visualization: Generate bar and radar plots for highlighting a player's best stats. 4 colors are used to represent the percentile of the player stats. Easy to understand for our clients. Radar shows comparision between player and average. 

    
<p align="center">
  <img width="100%" src="./images/NR1.png"> &nbsp &nbsp
</p>

# 2. Player Comparision Report

  Can find player strengths, calculates aggregate statistics, and finds similar players represented by a similarity score. 
   
  - **Key Features**

    Statistical Analysis: Compute percentile ranks, z-scores, and aggregate stats using custom-weighted combinations of individual stats. Aggregate stats are calculated differently for each position using different weights. Weights are assigned based on our knowlegde of the game.
    
    Player Comparison: Use cosine similarity to find players with similar performance profiles. Top 5 similar players are selected.
    
    Visualization: Generate table and radar plots for comparision of stats. Table contains the aggregate stats and radar compares the main player and another player from the table. 
   
<p align="center">
  <img width="100%" src="./images/NR2.png"> &nbsp &nbsp
</p>
