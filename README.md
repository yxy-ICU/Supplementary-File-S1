# Code Repository for TBAR Prognostic Study

This repository contains the main R scripts used in the study evaluating the prognostic value of the total bilirubin-to-albumin ratio (TBAR) in critically ill patients with gastrointestinal bleeding.

## Files

- `MIMIC-cox.R`: Cox regression analysis in the MIMIC-IV cohort
- `eICU-cox.R`: Cox regression analysis in the eICU-CRD cohort
- `nomogram-code.R`: nomogram development
- `roc.R`: ROC curve analysis
- `dca.R`: decision-curve analysis
- `calibration.R`: calibration analysis

## Data Availability

The data used in this study are available from the MIMIC-IV (version 3.1) and eICU-CRD (version 2.0) databases on PhysioNet, subject to the required training and data use agreement. Raw patient-level data cannot be publicly shared due to data-use restrictions.

## Purpose

This repository is provided to support transparency and reproducibility of the statistical analyses reported in the manuscript.

## Web Calculator

The web-based calculator is available at:
https://icu-risk-predictor.shinyapps.io/dynnomapp/
