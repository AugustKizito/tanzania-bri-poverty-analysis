# tanzania-bri-poverty-analysis
This project analyzes poverty resilience along Tanzania's BRI corridors using open-source geospatial data. It includes GEE scripts for data pre-processing, Python scripts for spatial modeling and visualization, and a synthetic dataset for reproducibility. The focus is on infrastructure-climate interaction
# Spatial Analysis of Climate Change and Poverty Dynamics in Tanzania

This repository contains scripts, processed datasets, and documentation used to reproduce the spatial econometric analysis presented in the manuscript:

"Climate Change and Poverty Dynamics in Tanzania: Geospatial Analysis of the Interaction Between Infrastructure, Climate Impact, and Regional Disparities"

## Repository Contents

**Code/**
Python scripts used for spatial econometric modeling including:
- Spatial Autoregressive Model (SAR)
- Geographically Weighted Regression (GWR)
- Spatial Durbin Model (SDM)

**Data/**
Processed datasets used for regression analysis:
- poverty indicators
- climate variables
- infrastructure indicators

**Supplementary Materials/**
Additional methodological documentation describing:
- satellite data processing
- land cover classification
- spatial modeling procedures

## Reproducibility

The repository provides the computational workflow used in the study.  
Scripts are written in Python using spatial econometric libraries including:

- geopandas  
- pysal  
- mgwr  
- numpy  
- statsmodels  

## Data Sources

The study integrates datasets from:

- National Bureau of Statistics (NBS), Tanzania
- Tanzania Social Action Fund (TASAF)
- Tanzania Meteorological Authority (TMA)
- CHIRPS precipitation database
- Sentinel-2 satellite imagery (ESA Copernicus)

## Peer Review Access

To preserve double-anonymous peer review, this repository has been anonymized and contains no identifying author information.
