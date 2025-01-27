# NRT-Player-Data-Report
- Developed a automated player data report generator for Neurotatic.
- Used for ad-hoc analysis as required by our team's player performance analyst.
- Increased efficiency by reducing the time needed to create reports compared to manually building them in Tableau.
- Made using Python and libraries such as Pandas and Matplotlib.
  
### 1. Player Data Report
   Data from Wyscout. Used to identify key player strengths, and visualize their standout attributes.
   
  - **Key Features**

    Filtering: Select player positions and apply filters for age and minutes played.
    
    Statistical Analysis: Compute percentile and z-scores for each statistic.
    
    Visualization: Generate bar and radar plots for highlighting a player's best stats.
   
<p align="center">
  <img width="100%" src="./images/NR1.png"> &nbsp &nbsp
</p>

### 2. Player Comparision Report

  Data from Wyscout. Can find player strengths, calculates aggregate statistics, and finds similar players represented by a similarity score. 
   
  - **Key Features**

    Statistical Analysis: Compute percentile ranks, z-scores, and aggregate stats using custom-weighted combinations of individual stats.
    
    Player Comparison: Use cosine similarity to find players with similar performance profiles.
    
    Visualization: Generate table and radar plots for comparision of stats.
   
<p align="center">
  <img width="100%" src="./images/NR2.png"> &nbsp &nbsp
</p>
