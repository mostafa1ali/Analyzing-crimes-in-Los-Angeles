# Analyzing Crimes in Los Angeles

This project analyzes crime data from Los Angeles using Python and pandas. The analysis explores crime frequency by hour, area, and victim age group, and visualizes key findings.

## Project Structure

- `Analyzing Crime in Los Angeles.ipynb` — Jupyter notebook containing all analysis code and visualizations.
- `crimes.csv` — Dataset with crime records from Los Angeles.

## Features

- Loads and cleans the LA crimes dataset.
- Analyzes crime frequency by hour and identifies peak crime times.
- Determines which area has the highest frequency of night crimes (10pm–3:59am).
- Groups crimes by victim age brackets and counts occurrences.
- Visualizes results using matplotlib and seaborn.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

Install dependencies with:

```sh
pip install pandas numpy matplotlib seaborn notebook
```

## Usage

1. Place `crimes.csv` in the project directory.
2. Open `Analyzing Crime in Los Angeles.ipynb` in Jupyter Notebook or VS Code.
3. Run the notebook cells to reproduce the analysis and visualizations.

## Example Analyses

- **Peak Crime Hour:** Identifies the hour with the most crimes.
- **Night Crime Hotspot:** Finds the area with the most crimes between 10pm and 4am.
- **Victim Age Analysis:** Groups and counts crimes by victim age brackets.