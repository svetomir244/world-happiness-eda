# World Happiness Report – Exploratory Data Analysis

## Project Overview

This project explores global life satisfaction patterns between 2005 and 2023 using data from the World Happiness Report.

The main objective is to investigate happiness rankings, long-term trends, and relationships between life satisfaction and various economic and social indicators.

## Dataset

- Source: World Happiness Report 2024
- Period: 2005–2023
- Observations: 2,363
- Variables: 11
- Data structure: Country-year observations

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Overview

- Data inspection and preprocessing
- Happiness rankings across countries
- Historical trends in life satisfaction
- Changes in happiness between 2011 and 2023
- GDP per capita and life satisfaction correlation
- Economic and social indicators
- Life satisfaction during the COVID-19 period
- Balanced panel analysis

## Key Findings

- Finland recorded the highest Life Ladder score in 2023.
- Among 127 countries observed in both 2011 and 2023, 76 experienced an increase in life satisfaction.
- GDP per capita showed a consistently positive correlation with life satisfaction.
- Social support, GDP per capita, and healthy life expectancy were among the strongest correlates of life satisfaction in 2023.
- Balanced panel analysis demonstrated the importance of consistent country coverage when comparing yearly averages.

## Project Structure

- `data/` – Dataset and source information
- `notebooks/` – Complete exploratory data analysis
- `requirements.txt` – Project dependencies
- `README.md` – Project documentation

## How to Run the Project

Clone the repository, create a virtual environment, and install the required dependencies using:

`pip install -r requirements.txt`

Navigate to the `notebooks/` directory and open `world_happiness_eda.ipynb` using Jupyter Notebook.

## Limitations

The analysis is subject to missing values, uneven country coverage, and the limitations of correlation-based analysis. The observed statistical associations do not establish causal relationships.

## Author

Svetomir Marić