# EAGER_ER

This repository contains supporting code, additional results, and documentation associated with the manuscript:

**Structural Causal Discovery and Predictive Sufficiency in High-Dimensional Dynamical Systems**

## Important Note

The core code related to the **Entropic Regression package** and the **mutual information estimators** is maintained separately in the ERFit package repository:

https://github.com/almomaa/ERFit-Package

Readers interested in the general implementation of entropic regression, the ERFit MATLAB package, and the information-theoretic estimators used in this work should refer to that repository.

## Overview

This repository provides materials related to the application of entropic regression to high-dimensional precipitation dynamics. The study investigates the distinction between **structural causal discovery** and **predictive sufficiency** using HRRR atmospheric fields and MRMS precipitation observations over the Southwestern United States.

The main objective is to identify atmospheric variables that provide stable conditional information about next-hour precipitation, and then evaluate whether these structurally selected variables are sufficient for predictive modeling.

## Manuscript Summary

The manuscript studies a high-dimensional precipitation system in which:

* HRRR atmospheric variables are used as candidate predictors,
* MRMS precipitation observations are used as the response,
* entropic regression is applied with a one-hour temporal delay,
* spatial aggregation through superpixels is used to evaluate structural consistency,
* transfer entropy and causation entropy are used as information-theoretic baselines,
* predictive models are used to test whether structurally selected variables form a sufficient predictive state.

The central finding is that entropic regression identifies a compact and physically interpretable set of structurally stable variables, but these variables do not provide a complete predictive representation of the system.

## Repository Contents

This repository may include:

* scripts supporting the precipitation case study,
* additional figures and results,
* processed summaries used in the manuscript,
* predictive evaluation outputs,
* documentation related to the workflow.

The repository is intended to support the analyses presented in the manuscript. The general ER package and mutual information estimator implementations are provided through the ERFit package repository linked above.

## Data

The HRRR atmospheric fields and MRMS precipitation observations used in this study are publicly available through their respective data providers. Processed data products were generated from these public sources following the preprocessing and spatial-alignment procedures described in the manuscript.

Due to the size of the gridded atmospheric and precipitation fields, large processed datasets may not be included directly in this repository.

## Code Availability

Code and supporting materials associated with the manuscript will be made available in this repository as appropriate. Additional implementation details for entropic regression and mutual information estimation are available at:

https://github.com/almomaa/ERFit-Package

## Citation

If you use this repository or the associated methods, please cite the related manuscript and the ERFit package when available.

## Contact

For questions related to the manuscript, repository, or implementation details, please contact the lead author.
