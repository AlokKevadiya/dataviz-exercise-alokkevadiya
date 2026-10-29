# Data Visualization — Alok Kevadiya

Lecture exercises for Weeks 2–4, with Python code, saved notebook outputs, and chart previews.

## Exercises

| Week | Topic | Notebook | Charts |
| --- | --- | --- | --- |
| 2 | Bar charts — World Happiness Report teaching data | [Open notebook](week02/lecture02_exercise.ipynb) | 2 required charts + 1 optional grouped chart |
| 3 | Line charts — CO₂ emissions | [Open notebook](week03/lecture03_exercise.ipynb) | All-country per-capita comparison; Asian total emissions |
| 4 | Scatter and bubble charts — Gapminder | [Open notebook](week04/lecture04_exercise.ipynb) | Asia in 2002/2007; all countries in 2007 with Asia highlighted |

Each weekly folder contains an `outputs/` directory with SVG and PNG exports generated from the notebook figures. Each weekly README displays the previews.

## Run locally

Use Python 3.10 or newer. Download or clone the entire repository so the CSV files stay in `data/`.

```bash
python -m pip install -r requirements.txt
python -m jupyterlab
```

Open a notebook and choose **Restart Kernel and Run All Cells**. The CSV paths support starting Jupyter from either the repository root or the weekly folder. Week 4 uses Plotly's bundled Gapminder dataset and needs no separate data download.

GitHub shows saved static chart outputs. Open the notebooks in Jupyter for interactive hover information. If GitHub temporarily fails to render a notebook, use the weekly chart previews.

## Data and interpretation

- `data/world_happiness_2023.csv`: course-provided, 63-country teaching sample. Regional and dataset averages are unweighted sample means.
- `data/co2_emissions.csv`: course-provided series for 15 countries, 2000–2022. The per-capita values are reported as course dataset values; they are not independently verified current statistics.
- Gapminder: Plotly's bundled historical sample, 142 countries and 1,704 observations from 1952–2007. The charts use 2002 and 2007, rather than current values.

Exercise instructions are preserved inside each notebook, followed by the solution and a short interpretation.
