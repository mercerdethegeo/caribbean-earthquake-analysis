# Southeastern Caribbean Earthquake Analysis

**Author:** Celine Thompson  
**Project status:** In progress  
**Project type:** Independent technical investigation  
**Software:** QGIS, Python, Google Colab

## Quick Links

- [Python Analysis Notebook (Live Google Colab)](https://colab.research.google.com/drive/1ETzMB4eO-4Eg_zl1HZruMBEQDOc5GUkT?usp=sharing)
- [QGIS Maps](maps/)
- [Python Figures](figures/)
- 
## Project Overview

This project investigates the spatial distribution of earthquakes in and around Trinidad and Tobago and their relationship with regional geological structures.

The project combines GIS-based spatial analysis with Python-based statistical analysis to explore earthquake patterns, identify clusters and investigate potential relationships with mapped faults.

It forms part of my independent learning in geospatial science, geophysics and scientific programming.

## Project Objectives

- Investigate earthquake distribution by location, magnitude and depth.
- Identify areas of concentrated seismic activity.
- Examine spatial relationships between earthquakes and mapped faults.
- Explore earthquake clustering using statistical methods.
- Investigate regional tectonic controls on observed seismicity.

## Data Sources

- USGS Earthquake Catalogue
- Institute of Marine Affairs (IMA) fault data
- USGS regional fault data

## Methodology and Progress

### QGIS

- Data import and coordinate reference system management
- Earthquake magnitude and depth classification
- Kernel density estimation (KDE)
- Magnitude-weighted earthquake density mapping
- Fault density mapping
- Fault proximity analysis
- Cartographic visualisation

### Python

- Earthquake catalogue ingestion and cleaning
- Exploratory data analysis
- Descriptive statistics
- Data visualisation
- DBSCAN spatial clustering
- Preliminary cluster characterisation

### Python Libraries

- pandas
- NumPy
- Matplotlib
- scikit-learn

## Preliminary Observations

Initial spatial analysis indicates variations in earthquake distribution and depth across the study area.

Further investigation is required to assess the relationship between observed earthquake clusters, mapped faults and regional tectonic processes.

## Limitations

- Variations in earthquake catalogue completeness
- Uncertainty in earthquake locations and depths
- Availability and resolution of regional fault datasets
- Sensitivity of clustering and density analysis to parameter selection

Spatial proximity alone does not establish a causal relationship between earthquakes and faults.

## Next Steps

- Further evaluate earthquake clustering results.
- Investigate regional tectonic influences.
- Assess the availability of focal mechanism and first-motion polarity data.
- Integrate GIS and Python outputs.
- Prepare a technical report documenting the methodology and findings.

## Project Outputs

Maps, figures, Python notebooks and technical documentation will be added as the investigation progresses.
### Preliminary Earthquake Map

![Earthquake Magnitude Distribution](maps/magnitude%20map.jpeg)

## Disclaimer

This is an independent learning and research project. Findings are preliminary and subject to further investigation.
