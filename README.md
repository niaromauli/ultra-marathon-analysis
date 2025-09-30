# Ultra Marathon Analysis

This project explores and analyzes a large dataset of ultra marathon race results from around the world, focusing on 50km and 50-mile events. The analysis is performed in Jupyter Notebook using Python data science libraries.

## Project Overview

- Loads and inspects a dataset containing millions of race results from the file `TWO_CENTURIES_OF_UM_RACES.csv`.
- Focuses on races in the USA, specifically filtering for 50km and 50-mile distances.
- Performs data cleaning and exploratory data analysis.
- Investigates athlete and event characteristics such as:
  - Event year, name, and location
  - Number of finishers
  - Athlete performance (time, speed)
  - Athlete demographic information (age, gender, country, club)

## Dataset

The dataset (`TWO_CENTURIES_OF_UM_RACES.csv`) includes the following columns:

- Year of event
- Event dates
- Event name
- Event distance/length
- Event number of finishers
- Athlete performance
- Athlete club
- Athlete country
- Athlete year of birth
- Athlete gender
- Athlete age category
- Athlete average speed
- Athlete ID

> **Note:** The full dataset is very large (over 7 million rows).

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- seaborn

Install requirements via pip:

```bash
pip install pandas seaborn
```

## Usage

1. Clone this repository.
2. Make sure the dataset `TWO_CENTURIES_OF_UM_RACES.csv` is in the same directory as the notebook.
3. Open `Ultra Marathon Project.ipynb` in Jupyter Notebook.
4. Run the cells to reproduce the analysis or modify them for your own exploration.

## Example

The notebook demonstrates how to:
- Import and inspect the data
- Filter for specific event types and years
- Analyze athlete performances and demographics