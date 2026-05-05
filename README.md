# Python GIS Data Analysis and Spatial Workflows

**Student:** Noah Bohrer  
**Course:** GIST 604B – Open Source GIS  
**Module:** Assignment 3 – Python GIS (Pandas, GeoPandas, Rasterio)  
**University of Arizona**

---

## Project Description
This project demonstrates end-to-end geospatial data analysis using Python. The assignment covers tabular data processing with pandas, spatial vector analysis with GeoPandas, and raster-based remote sensing workflows using Rasterio. It highlights how Python can be used to automate GIS workflows, perform spatial analysis, and integrate multiple data types into a unified analytical pipeline.

---

## Tools and Technologies
- Python  
- pandas (tabular data analysis)  
- GeoPandas (spatial vector analysis)  
- Rasterio (raster and remote sensing workflows)  
- Jupyter Notebooks  
- STAC API (satellite imagery access)  
- Cloud-Optimized GeoTIFFs (COGs)  

---

## What I Did
- Developed reusable Python functions for loading, filtering, and summarizing GIS datasets using pandas :contentReference[oaicite:0]{index=0}  
- Performed data joins and statistical analysis on environmental datasets  
- Loaded and explored spatial datasets including CRS, geometry types, and spatial extents :contentReference[oaicite:1]{index=1}  
- Transformed coordinate systems and executed geometry operations (buffer, centroid, area)  
- Conducted spatial joins and analyzed spatial relationships between datasets  
- Performed overlay analysis and visualized spatial data  
- Processed satellite imagery using Rasterio, including NDVI calculation and masking workflows :contentReference[oaicite:2]{index=2}  
- Built a raster time series from satellite imagery for temporal analysis  

---

## How to View / Run
- Open the repository in GitHub Codespaces or a local Python environment  
- Navigate to the `/notebooks` directory and run the Jupyter Notebooks step-by-step  
- Key folders:
  - `/notebooks/pandas` – tabular data workflows  
  - `/notebooks/geopandas` – spatial vector analysis  
  - `/notebooks/rasterio` – raster and remote sensing workflows  
- Python functions are implemented in the `/src` directory  
- Run tests using:
