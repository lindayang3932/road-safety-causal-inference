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

The notebooks are exploratory working analyses, not a validated end-to-end pipeline. Outputs were cleared and duplicate notebook source was consolidated. The original Colab paths and cell ordering are retained; adjust paths and run relevant sections after obtaining authorized input data. Set `DATACOMMONS_API_KEY` in your environment before retrieving covariates. See [data notes](data/README.md). The R Markdown contains the detailed diagnostic workflow and requires local input files and R packages. The LaTeX reports summarize or transcribe the supplied research notes; they do not represent newly rerun results. In particular, different model versions may use different analytic samples. The assignment mechanism and appropriate inference level remain under review.

This is work in progress, not a published paper. Research data and outputs should not be redistributed without permission from the research team.

