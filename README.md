# Statistical Analysis of a Cluster-Randomized Road Safety Intervention

Research collaboration with Professor Cathy Xia, The Ohio State University.

This repository documents my statistical analyses of a geographically assigned road-safety advertising intervention, focusing on model assumptions, rare-event outcomes, geographic spillover, and sensitivity of treatment-effect estimates.

## Research components

| Component | Report | Analysis |
|---|---|---|
| Parallel trends, mixed-effects DiD, and driving behavior | [LaTeX](reports/did_mixed_effects.tex) | [Python notebook](code/street_vision_analysis.ipynb) |
| Fatal crash counts and model diagnostics | [LaTeX](reports/fatal_crash_models.tex) | [R Markdown](code/fatal_crash_models.Rmd), [Python notebook](code/crash_analysis.ipynb) |
| Geographic spillover | [LaTeX](reports/geographic_spillover.tex) | [Python notebook](code/crash_analysis.ipynb) |
| Treatment-window and group/county sensitivity | [LaTeX](reports/did_mixed_effects.tex) | [Python notebook](code/crash_analysis.ipynb) |

## My contributions

- Assessed parallel trends and compared OLS and mixed-effects difference-in-differences specifications.
- Investigated Poisson and alternative count models for sparse fatal crash outcomes using distributional diagnostics, simulation and covariate exploration.
- Constructed a geographic exposure indicator and estimated spillover among control counties.
- Examined robustness to alternative campaign periods and influential groups or counties.

## Reproducibility and status

This is work in progress, submission in progress.

