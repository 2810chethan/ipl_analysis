#  IPL Data Analysis (2022–2026)

This project performs comprehensive data analysis on IPL ball-by-ball datasets from 2022 to 2026. The focus is on data preprocessing, grouping, and extracting meaningful insights about player and team performance.

##  Project Overview

The dataset contains detailed delivery-level information such as:

* Match details (season, venue, match_id)
* Batting and bowling teams
* Player-level data (striker, bowler)
* Runs scored per ball
* Extras (wides, no-balls, byes, leg-byes)
* Wicket information
* Match phases (Powerplay, Middle, Death)

##  Data Preprocessing

The following preprocessing steps were performed:

* **Handling Missing Values** using `fillna()` and `dropna()`
* **Removing Duplicates** using `drop_duplicates()`
* **Standardization** of player and team names
* **Structural Corrections** (data type conversions)
* **Outlier Detection** using the IQR method (applied on runs and extras)

## 📊 Grouping & Analysis Performed

###  Player Analysis

* Total runs scored by each batsman
* Strike rate calculation
* Most wickets taken by bowlers
* Dismissal type analysis

### Team Analysis

* Total runs scored by each team
* Matches played by each team
* Extras conceded by teams

###  Match Insights

* Runs scored per over
* Phase-wise analysis (Powerplay, Middle Overs, Death Overs)
* Extras breakdown (wides, no-balls, byes, leg-byes)

## 📈 Key Insights

* Identification of top-performing batsmen and bowlers
* Teams with highest scoring patterns
* Phases contributing most to total runs
* Impact of extras on match outcomes

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy

## 📁 Project Structure

ipl_analysis/
│── project4.ipynb
│── README.md


## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/2810chethan/ipl_analysis.git
   ```
2. Open the notebook using Jupyter / VS Code
3. Run all cells to reproduce the analysis


##  Future Enhancements

* Advanced data visualization (heatmaps, boxplots)
* Machine Learning models (run prediction, match outcome prediction)
* Interactive dashboards using Power BI / Streamlit


## 👨‍💻 Author

Chethan Kalyan



This project is developed as part of academic learning and demonstrates practical implementation of data analysis techniques using real-world IPL datasets.
