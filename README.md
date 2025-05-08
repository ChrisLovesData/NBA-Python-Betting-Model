# NBA-Python-Betting-Model

This project builds a Python-based model to predict NBA over/under outcomes using historical team stats, rest days, and rolling averages. The goal is to identify potential value in betting lines using statistical modeling and live updates.

---

##  Tools & Libraries Used
- Python (pandas, numpy, matplotlib, scikit-learn)
- Jupyter Notebook
- Excel for result tracking
- GitHub for version control

---

##  Features Engineered
- Average total points scored last 20 (long-term)
- Average total points allowed last 20 (long-term)
- Average total points scored last 3 (short-term)
- Average total points allowed last 3 (short-term)
- Head-to-Head season averages
- Assist × Assist interaction
- Combined rebound average
- Days of rest (home and away)

---

##  Model Results
- Model accuracy (after fix): **71%** for first round playoff matches
- Total win rate: 58% over 33 games  
- Adjustments made to account for short-term trends (e.g., last 3 games)

---

##  Files
- [`nba_data.ipynb`](nba_data.ipynb): Full model code and predictions
- `results/`: CSV or Excel file with daily predictions vs. Vegas lines

---

##  Next Steps
- Integrate player injury impacts
- Scrape live sportsbook lines
- Test different classification models (logistic regression)

---

##  Author
**Chris Randall**  
Toronto-based data analyst & sports modeling enthusiast  
[Portfolio](https://www.datascienceportfol.io/ChrisRandall)
