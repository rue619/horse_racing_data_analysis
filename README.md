# Horse Racing Performance Analytics

## Project Overview

This project analyzes horse racing data to explore factors associated with race performance.

The analysis focuses on horse characteristics, starting odds, draw position, and race conditions. The project uses Python for data cleaning and analysis and Power BI for interactive data visualization.

## Dataset

The dataset contains horse racing records from Hong Kong racing.

The analysis uses two main datasets:

- `races.csv` — race-level information
- `runs.csv` — horse-level race participation and performance information

The final horse-level analysis contains:

- 6,348 races
- 79,447 horse-run records

## Tools Used

- Python
- Pandas
- Jupyter Notebook
- Power BI
- GitHub

## Analysis Process

The project followed these main steps:

1. Data collection
2. Data inspection
3. Data cleaning
4. Data validation
5. Data preparation and feature engineering
6. Exploratory analysis
7. Data visualization
8. Power BI dashboard development
9. Key findings and insights

## Key Analysis Areas

The analysis investigates:

- Horse rating and race performance
- Starting odds and race performance
- Draw position and finishing position
- Race distance
- Venue
- Track going
- Field size

## Dashboard

The Power BI dashboard contains four pages:

### 1. Overview

Provides a high-level summary of the dataset and key performance indicators.

### 2. Horse Performance

Explores the relationship between draw position, horse rating, and race performance.

### 3. Betting & Market

Examines the relationship between starting odds and race outcomes.

### 4. Race Conditions

Explores performance across distance, venue, track going, and field size.

## Key Findings

### Horse Rating

Horses in the 100+ rating group had the best average finishing position and the highest Top-3 rate among the rating groups analyzed.

### Starting Odds

Lower starting odds were strongly associated with better race performance. Horses with lower odds generally had better finishing positions and higher win and Top-3 rates.

### Draw Position

Lower draw numbers generally showed better finishing performance, although the relationship was not perfectly consistent.

### Race Conditions

Performance varied across race distance, venue, track going, and field size.

## Project Structure

```text
Horse_Racing_Data_Analysis/
│
├── data/
│   ├── races.csv
│   └── runs.csv
│
├── cleaned_data/
│   ├── races_clean.csv
│   ├── runs_clean.csv
│   └── horse_race_analysis.csv
│
├── visualizations/
│
├── horse_racing_analysis.ipynb
├── horse_racing_dashboard.pbix
└── README.md