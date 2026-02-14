# Homework 1

Data Science homework assignment analyzing faculty salary data.

## Contents

- **hw1.ipynb** — Jupyter notebook with analysis and visualizations
- **Salaries.csv** — Faculty salary dataset

## Dataset

The `Salaries.csv` file contains academic salary data with the following columns:

| Column          | Description                    |
|-----------------|--------------------------------|
| rank            | AsstProf, AssocProf, Prof      |
| discipline      | A or B                         |
| yrs.since.phd   | Years since PhD                |
| yrs.service     | Years of service               |
| sex             | Male / Female                  |
| salary          | Salary in dollars              |

## Setup

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install pandas matplotlib seaborn jupyter
```

## Run

```bash
jupyter notebook hw1.ipynb
```
