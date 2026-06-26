# F1 Data Analysis 🏎️

An exploratory data analysis of Formula 1 racing data
spanning 75 seasons (1950-2024) using Python,
Pandas, Matplotlib and Seaborn.

## Project Overview
This project analyzes historical F1 data to uncover
patterns in race results, driver performance,
constructor dominance and nationality trends.

## Dataset
- Source: [Kaggle F1 World Championship Dataset]
  (https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
- Files used: races.csv, drivers.csv, results.csv,
  constructors.csv, driver_standings.csv

## Key Questions Answered
- How has F1 grown over 75 seasons?
- Who are the greatest drivers of all time?
- Which constructors dominated F1 history?
- Where do F1 drivers come from?
- Does starting position affect race results?

## Key Findings
- F1 grew from 7 races (1950) to 24 races (2024)
- Lewis Hamilton leads all time with 105 wins
- Ferrari is most successful constructor with 249 wins
- 43 nationalities have competed in F1
- Starting position strongly correlates with finish

## Visualizations
1. F1 Races Per Year (Line Chart)
2. Top 10 Drivers By Wins (Bar Chart)
3. All Time Dominant Constructors (Bar Chart)
4. Driver Birth Years By Nationality (Box Plot)
5. Points Distribution By Constructor (Box Plot)
6. Grid vs Finish Position (Scatter Plot)
7. Top Driver Nationalities (Bar Chart)
8. F1 Dashboard (Subplot)
9. Race Variables Correlation (Heatmap)

## Tech Stack
- Python 3.13
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Setup
1. Clone the repo
2. Create virtual environment:
   python -m venv env
3. Activate:
   env\Scripts\activate
4. Install dependencies:
   pip install -r requirements.txt
5. Download dataset from Kaggle link above
6. Place CSV files in data/ folder
7. Run F1_analysis.ipynb

## Project Structure
EDA-F1/
├── data/              ← CSV files (download from Kaggle)
├── env/               ← virtual environment
├── F1_analysis.ipynb  ← main notebook
├── requirements.txt   ← dependencies
└── README.md          ← this file