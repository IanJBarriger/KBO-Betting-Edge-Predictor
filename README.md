# ⚾ KBO Betting Edge Predictor  

## 📖 Overview  
This project predicts **Korean Baseball Organization (KBO)** game outcomes and identifies potential **positive expected value (EV)** betting opportunities. Using machine learning, historical KBO game data, and betting odds, the model estimates win probabilities, compares them with bookmaker implied probabilities, and simulates bankroll growth through backtesting.  

The goal is to showcase applied **data science, sports analytics, and predictive modeling** in a real-world context.  

---

## 🗂️ Repository Structure

```kbo-betting-edge-predictor/
├── data/
│   ├── raw/                # Unprocessed datasets (scraped stats, odds)
│   ├── processed/          # Cleaned & feature-engineered datasets
│   └── external/           # (Optional) extra data sources
├── notebooks/
│   ├── 01_data_collection.ipynb     # Scraping & collecting KBO data
│   ├── 02_data_cleaning.ipynb       # Cleaning & preprocessing
│   ├── 03_feature_engineering.ipynb # Feature engineering
│   ├── 04_modeling.ipynb            # Machine learning models
│   ├── 05_backtesting.ipynb         # Betting strategy simulation
│   └── 06_visualizations.ipynb      # Dashboards & ROI plots
├── src/
│   ├── data_pipeline.py    # Functions for loading/cleaning data
│   ├── features.py         # Feature engineering helpers
│   ├── models.py           # Training/evaluation scripts
│   ├── backtest.py         # Betting strategy simulation
│   └── utils.py            # Shared functions (metrics, configs)
├── reports/
│   ├── figures/            # Graphs, plots, calibration charts
│   └── results.md          # Model performance & backtest summary
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── LICENSE                 # (Optional) open-source license
```

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
   ```

2. Install Dependencies:
   ```pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
```Jupyter Notebook
   ```

5. Open and explore the notebooks in the notebooks/ folder:

- 01_data_collection.ipynb → Scraping & collecting KBO data
- 02_data_cleaning.ipynb → Cleaning & preprocessing
- 03_feature_engineering.ipynb → Rolling stats & implied probabilities
- 04_modeling.ipynb → Machine learning models
- 05_backtesting.ipynb → Betting simulation & bankroll analysis

## 📌 Future Work

- Add pitcher-specific advanced stats (ERA, WHIP, FIP)
- Include weather and travel schedule effects
- Extend to live betting / in-game win probability models
- Deploy model to a hosted web app (Heroku, Render, Streamlit Cloud)

## 🏆 Key Skills Demonstrated

- Data collection via web scraping + APIs
- Data wrangling and feature engineering
- Machine learning modeling (classification, calibration)
- Backtesting & simulation of betting strategies
- Data visualization and storytelling
- (Optional) Web app deployment with Streamlit
