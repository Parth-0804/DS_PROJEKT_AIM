# DS_PROJEKT_Msc_AIM 
# Contribution_parth
This Branch is created to research on Football datasets avaliability and possible end to end Ml solution.
Datasets Link:
  https://www.football-data.co.uk/data.php : 
    ➡️Historical football result dataset and betting odds data.
    ➡️ All league divisions from European countries with notes on quality and information of data.csv files
    ➡️ Huge dataset avaliability: season 2007/2008 till current season 2024/2025
    ➡️ This Historic data can be merged with possible open datasets/APIs to make it further useful.
        [possibly: https://github.com/statsbomb/open-data - Player-level stats, match events (passes, shots, xG, pressure, etc.)
                   https://understat.com/ - Detailed xG for players/teams, assists, key passes
                   https://www.transfermarkt.com/ - Player value, injury history, positions, transfers
                   FIFA ratings dataset (via Kaggle) - Player attributes, potential, skill breakdowns
                   OpenLigaDB or API-Football (API-based services) - Real-time or scheduled fixtures, live updates, team lineups
                   ]

Cheatsheet to plotting graphs:
  https://www.kaggle.com/code/akhabash/cheatsheet-70-ggplot-charts/notebook
      ➡️ provide all essential and most commonly used plotly charts in a single page

POSSIBLE END TO END IDEAS:
    1. Player Scouting Dashboard: Combine StatsBomb xG, Transfermarkt value, and FIFA ratings
    2. Match Prediction Model: Use historical odds (football-data.co.uk) + recent form + xG
    3. Fantasy Performance Tracker: Join actual stats + xG with predicted fantasy points
    4. Tactical Heatmap Analyzer: Merge pressure events and pass locations for visualization
    5. Player Regression Detection: Track player's form vs potential (FIFA + stats)
Tech-stack:
    Data Cleaning: pandas, numpy
    ML Modeling: scikit-learn, xgboost, lightgbm
    xG modeling: Custom or replicate StatsBomb’s logistic regression xG
    Deep learning: Use LSTM or transformers for player form trends
    Dashboards: Streamlit, Plotly Dash, Shiny, or React-based UI (like we just built)
