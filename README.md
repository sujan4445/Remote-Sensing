# Remote-Sensing
# NDVI Visualization in Wheat Under Irrigated and Drought Conditions
Handheld NDVI sensing devices generate raw data across multiple growth stages, which can be challenging to interpret due to their volume and complexity. To address this, I developed a visualization approach that compiles NDVI data from all stages under both irrigated and drought conditions into a single image, providing a clearer and more comprehensive understanding of the crop's response.


This repository contains R code used to visualize NDVI (Normalized Difference Vegetation Index) data collected from a wheat field experiment under irrigated** and drought conditions across multiple growth stages.

Project Structure

- `NDVI 24.xlsx` – Source file containing NDVI data for both treatments.
- `grid` – A data frame mapping genotype (`gen`) positions to a grid layout.
- `ndvi_plot_script.R` – Main R script that prepares the data and generates tiled heatmaps.
- `NDVI Heatmap.png` – Output figure showing NDVI values for six growth stages in a single image.

Purpose
To spatially visualize the variation in NDVI values among wheat genotypes under contrasting moisture conditions (Irrigated vs Drought) across six phenological stages.
