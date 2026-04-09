# Global Health Data Analysis 

## Dataset informations 
### Source link : https://catalog.ourworldindata.org/garden/covid/latest/compact/compact.csv
### Cleaned Rows : 570606 rows 
### columns : 61 colums 
## Variable decription 
| Variable                         | Description                                                  | Type   |
| -------------------------------- | ------------------------------------------------------------ | ------ |
| `country`                        | Nom du pays ou de la région                                  | object |
| `date`                           | Date du relevé                                               | object |
| `total_cases`                    | Nombre total de cas confirmés depuis le début de la pandémie | float  |
| `new_cases`                      | Nombre de nouveaux cas signalés ce jour                      | float  |
| `new_cases_smoothed`             | Moyenne glissante sur 7 jours des nouveaux cas               | float  |
| `total_cases_per_million`        | Nombre total de cas par million d’habitants                  | float  |
| `new_cases_per_million`          | Nombre de nouveaux cas par million d’habitants               | float  |
| `new_cases_smoothed_per_million` | Moyenne glissante sur 7 jours des nouveaux cas par million   | float  |
| `total_deaths`                   | Nombre total de décès depuis le début de la pandémie         | float  |
| `new_deaths`                     | Nombre de nouveaux décès signalés ce jour                    | float  |
| `new_deaths_smoothed`            | Moyenne glissante sur 7 jours des nouveaux décès             | float  |
## Tools Used 
1. Python 3.x – Programming language for data analysis.
2. Pandas – Load, clean, and manipulate datasets.
3. NumPy – Numerical computations and array operations.
4. Matplotlib – Create basic charts like line plots and histograms.
5. Seaborn – Advanced statistical visualizations with a clean style.
6. Jupyter Notebook – Interactive environment for coding and visualizing results.
7. ChatGPT – Assisted in generating explanations, summaries, and improving the README.
## Key findings
### Concentration of Cases:
A small number of countries account for the majority of COVID-19 cases, showing that the pandemic’s impact was uneven globally.
### Waves of Infection: 
Clear waves over time indicate periods of rapid spread followed by declines, reflecting outbreaks and interventions.
### Discrepancy Between Cases and Deaths:
Some countries with high case numbers experienced relatively lower death rates, suggesting differences in healthcare systems, demographics, or response strategies.
### Variation Across Countries:
Daily new cases vary significantly, with some countries experiencing extreme spikes while others remain more stable.
Outbreak Patterns: Sudden spikes point to irregular outbreaks, emphasizing the unpredictable nature of the pandemic in certain regions.
