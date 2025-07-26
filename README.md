# Football ML App

A machine learning-powered toolkit for analyzing and supporting football (soccer) betting decisions, focused on the English Premier League (EPL).

## Features
- Predictive modeling for EPL match outcomes
- Data analysis and visualization of team and player statistics
- CSV data files for historical EPL results and betting odds
- Jupyter Notebook dashboard for interactive exploration
- Pre-trained machine learning model (Random Forest)

## File Descriptions
- `premier_league_dashboard.ipynb`: Main Jupyter Notebook for data analysis, visualization, and model usage.
- `rf_model.pkl`: Pre-trained Random Forest model for predictions.
- `epl_2020_21_goals.csv`: EPL 2020/21 season goals data.
- `epl_team_goals_2016_to_2021.csv`: Team goals data from 2016 to 2021.
- `epl_total_goals_2016_to_2021.csv`: Total goals per season from 2016 to 2021.
- `odds_api.csv`: Betting odds data.
- `premier_league_bets.csv`: Example bets and outcomes.
- `premier_league_players_2015_16.csv`: Player statistics for the 2015/16 season.
- `chromedriver-win64/`: ChromeDriver for web scraping (if needed).

## Setup Instructions
1. **Clone the repository** (if not already):
   ```bash
   git clone <repo-url>
   cd Football-ML-App
   ```
2. **Install Python dependencies** (recommended: use a virtual environment):
   ```bash
   pip install -r requirements.txt
   ```
   *(If `requirements.txt` is missing, see below for common packages.)*
3. **(Optional) Install Jupyter Notebook:**
   ```bash
   pip install notebook
   ```

## Usage
1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook premier_league_dashboard.ipynb
   ```
2. Follow the notebook instructions to explore data, visualize statistics, and use the ML model for predictions.

## Requirements
- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- jupyter
- (Optional) selenium (if using web scraping with ChromeDriver)

Install all requirements with:
```bash
pip install pandas numpy scikit-learn matplotlib jupyter selenium
```

## License
This project is for educational and personal use. Please check data sources for their respective licenses.

## Contact
For questions or suggestions, please contact the project maintainer. 