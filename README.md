# ⚽ DS_PROJEKT_Msc_AIM – Football Data Analytics  
## ✍️ Contribution by: Parth-0804

This branch is created to **research football datasets** and explore a **complete end-to-end ML solution** for player and match analytics.

---

## 📂 Dataset Source

### [football-data.co.uk](https://www.football-data.co.uk/data.php)
- ✅ **Historical football result & betting odds**
- 🌍 All league divisions from top European countries
- 📊 Available from **2007/08 season to 2024/25**
- 📁 Format: CSV (easy to parse, rich in match-level stats)
- 🧩 Suitable for merging with player-level datasets & APIs

---

## 🔗 Combine with These Open Data/APIs

| Dataset | Description |
|--------|-------------|
| [StatsBomb Open Data](https://github.com/statsbomb/open-data) | Match events (passes, xG, shots, pressure) |
| [Understat](https://understat.com) | xG, assists, key passes, team/player form |
| [Transfermarkt](https://www.transfermarkt.com/) | Player values, injuries, position, transfers |
| [FIFA Ratings](https://www.kaggle.com/stefanoleone992/fifa-22-complete-player-dataset) | Player skills, potential, attributes |
| OpenLigaDB / API-Football | Real-time or scheduled match updates |


## Visualization Cheatsheet

🧠 Boost your analysis with quick plots using this:
- [🔗 Kaggle: 70 ggplot/plotly chart cheatsheet](https://www.kaggle.com/code/akhabash/cheatsheet-70-ggplot-charts/notebook)


## 💡 Possible End-to-End Project Ideas

1. **🧬 Player Scouting Dashboard**  
   Combine StatsBomb xG + Transfermarkt value + FIFA attributes

2. **🧠 Match Prediction Model**  
   Use historical betting odds + xG + team form

3. **📈 Fantasy Performance Tracker**  
   Compare expected vs actual points using stats & xG

4. **🔥 Tactical Heatmap Analyzer**  
   Use event locations for pressure/pass heatmaps

5. **📉 Player Regression Detection**  
   Analyze dips in form vs expected performance (FIFA potential)



##  Tech Stack

| Component | Tools |
|----------|-------|
| **Data Cleaning** | `pandas`, `numpy` |
| **ML Modeling** | `scikit-learn`, `xgboost`, `lightgbm` |
| **xG Modeling** | Logistic regression (StatsBomb approach) |
| **Deep Learning** | `LSTM`, `transformers` (for trend detection) |
| **Dashboards** | `Streamlit`, `Plotly Dash`, `Shiny`, `React + Tailwind` |

---

