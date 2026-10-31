# Data Visualization — Alok Kevadiya

Python for Data Analysis & Visualization — University of Europe, Winter 2026/2027.

Personal exercise repository for **Alok Kevadiya**, organized by lecture week to match [Dr. Dina Deifallah's class material](https://github.com/dina-deifallah/data-viz-class-material-w2026).

[Course overview](course-description/course_description.ipynb) · [Class notes and model answers](https://github.com/dina-deifallah/data-viz-class-material-w2026)

## Exercises

| Week | Topic | Notebook | Charts |
| --- | --- | --- | --- |
| 1 | Course introduction and Plotly basics | [Lecture reference](week01/README.md) | Introductory material; graded weekly exercises start at Lecture 2 |
| 2 | Bar charts — World Happiness Report teaching data | [Open notebook](week02/lecture02_exercise.ipynb) | 2 required charts + 1 optional grouped chart |
| 3 | Line charts — CO₂ emissions | [Open notebook](week03/lecture03_exercise.ipynb) | All-country per-capita comparison; Asian total emissions |
| 4 | Scatter and bubble charts — Gapminder | [Open notebook](week04/lecture04_exercise.ipynb) | Asia in 2002/2007; all countries in 2007 with Asia highlighted |
| 5 | Distribution charts — Airbnb London | [Open notebook](week05/lecture05_exercise.ipynb) | Overlaid price histograms; activity box plots by borough |

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
- `data/airbnb_london.csv`: course-provided sample of 2,500 listings. Week 5 excludes prices above the sample's 95th percentile; activity charts exclude zero reviews per month.

Exercise instructions are preserved inside each notebook, followed by the solution and a short interpretation.

## Course workflow

The instructor's repository supplies lecture notes, datasets, and model answers. This personal repository contains completed exercises and their outputs. Use the official class repository for the latest teaching material; submit work to this repository.

The published course currently includes Weeks 1–5. Later exercises will be added when released and completed.

## Attribution

Exercise prompts, the course overview, and course-provided datasets come from [Dr. Dina Deifallah's class repository](https://github.com/dina-deifallah/data-viz-class-material-w2026). The original MIT notice is preserved in [LICENSE](LICENSE). Completed solution code, interpretations, and chart exports are maintained here for the weekly exercises.
