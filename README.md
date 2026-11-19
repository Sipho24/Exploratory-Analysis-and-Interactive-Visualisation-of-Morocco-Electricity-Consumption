```
# Morocco Electricity Consumption & Environmental Factors - AnalystLab Africa Week 5
```

```
Analyst: Sipho Madlanga | Track: Data Analytics (Track 1)
Tools: Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn, Plotly (Anaconda)
```

```
## Project
Exploratory analysis of electricity consumption across three power zones in Morocco (Tetouan), using 52,416 readings taken every 10 minutes from 1 January to 30 December 2017, alongside temperature, humidity and wind speed. Goal: identify consumption patterns, test environmental relationships, and produce evidence-based recommendations for an energy management organisation.
```

```
## Files
- week5_morocco_power.ipynb - the complete analysis (Tasks 1-6)
- powerconsumption.csv - original dataset (52,416 rows x 9 columns)
- powerconsumption_datadictionary.csv - field descriptions
- powerconsumption_clean.csv - cleaned dataset produced by Task 2 (adds Year, Month, Day, Hour, DayOfWeek, Date)
- week5-analytical-report.pdf - short analytical report
- charts/ - chart images exported from the notebook
```

```
## How to reproduce
1. Install Anaconda (Python 3). In a terminal run once: pip install plotly notebook
2. Put the CSVs and the notebook in one folder (e.g. ~/Desktop/Week5_Morocco_Power)
3. From that folder: jupyter notebook, open week5_morocco_power.ipynb
4. Kernel > Restart & Run All
5. The notebook runs top-to-bottom without errors, reproducing every table and chart and regenerating powerconsumption_clean.csv
```

```
## What the notebook does
Task 1 inspection (52,416 x 9; 0 missing; 0 duplicates; all 52,415 gaps exactly 10 minutes) | Task 2 cleaning and time columns | Task 3 consumption patterns | Task 4 environmental relationships (association, not causation) | Task 5 visualisation (Plotly interactive plus Matplotlib/Seaborn) | Task 6 six findings and four recommendations
```

```
## Interpretation notes (from the brief)
- PowerConsumption readings are Kilowatt-Hours per 10-minute observation, interpreted as the consumption level recorded at each observation; analysis uses averages, not summed totals
- GeneralDiffuseFlows and DiffuseFlows have insufficient descriptions; no conclusions rest on them
```