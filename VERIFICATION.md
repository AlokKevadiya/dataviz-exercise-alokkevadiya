# Verification — 29 October 2026

All 13 non-empty Python code cells across Weeks 2–4 were executed in order with a fresh IPython namespace for each notebook. Each notebook was checked twice: with the repository root as the working directory and with its weekly folder as the working directory. Both path configurations passed without Python errors.

| Week | Checks | Result |
| --- | --- | --- |
| 2 | Regional aggregation, descending display order, zero baselines, top/bottom 8 selection, group separator, sample mean, optional grouped chart | Passed |
| 3 | All 15 countries; all required Asian countries; full 2000–2022 series; exactly one highlighted line; grey context; endpoint labels; plotted series matched to CSV | Passed |
| 4 | Asia only for 2002/2007 (33 countries per year); two year styles and connectors; all 142 countries for the bubble chart; population encoded by area; Asia drawn over grey context; logarithmic GDP axes; explanatory annotation | Passed |

All seven chart figures have embedded PNG outputs and matching PNG/SVG exports. All notebook schemas and local README links passed validation. Chart previews were visually inspected for labels, titles, legends, and annotations.

The execution environment used Python 3.12, pandas 2.2.3, and Plotly 6.5.0. The checks above cover the notebook code and outputs; they do not certify the course datasets as independently verified real-world statistics.

## Course alignment and Week 5 — 31 October 2026

The official Week 2–4 exercise prompts were compared against the completed notebooks; their required tasks match. The course overview and original MIT notice have been included, with direct links to official notes and model answers.

Week 5 adds four executed code cells and two figures. All cells passed sequential execution in a fresh IPython namespace from both the repository root and `week05/`. Checks cover the full-sample 95th-percentile price filter, exclusion of shared rooms from the histogram, shared £10 bins, overlay mode with 0.6 opacity, separate group median lines, positive review-rate filtering, descending borough medians, exactly two highlighted boroughs, and visible box-plot outliers. Both charts include the filter disclosure and median reference annotations. Two embedded PNG outputs and four PNG/SVG exports were generated and visually inspected.
