# KBO-Betting-Edge-Predictor

## Project overview:

"This project predicts KBO baseball game outcomes and identifies positive expected value (EV) betting opportunities using machine learning. The pipeline covers data collection, feature engineering, modeling, and backtesting betting strategies."

## Key features:

- Scraped/collected historical KBO and odds data
- ML models (logistic regression, random forest, XGBoost)
- Simulated bankroll growth via backtesting
- Visualizations of ROI and model calibration


## 🔍 Data Sources  
- **KBO Official Website** ([koreabaseball.com](https://www.koreabaseball.com/)) — game results, team & player stats.  
- **OddsPortal** (https://www.oddsportal.com/baseball/south-korea/kbo/) — historical bookmaker odds.  
- (Optional) **TheOddsAPI** (https://theoddsapi.com/) — sports odds API for real-time betting lines.  

---

## 🧑‍💻 Tech Stack  
- **Python**: pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn  
- **Jupyter Notebook** for EDA and model development  
- **Streamlit** (optional) for building an interactive web app  
- **Tableau / Plotly** (optional) for visualization dashboards  

---

## 🚀 How to Run  

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/kbo-betting-edge-predictor.git
   cd kbo-betting-edge-predictor
