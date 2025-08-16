# Landslide-susceptibility-demo
**Author** Neethusree

**Content**Demo of meso-scale landslide susceptibility mapping using open DEM data and Python (adapted from GSI workflow)

Note: This repository uses only **open or synthetic datasets**. Official GSI datasets are not included due to licensing restrictions.

## Project Overview
This repository showcases a reproducible workflow for landslide susceptibility mapping at meso-scale (1:10,000).  
It mirrors the methodology I applied in professional work at the Geological Survey of India (GSI), adapted here to run on open DEMs and small demonstration inventories.

The goal is to highlight:
- Translation of **ArcGIS workflows → open-source Python**  
- Application of **Landslide Susceptibility Estimation Rating (LSER)** concepts  
- Clear scientific documentation and reproducibility

## Methods
1. **DEM Preprocessing**  
   - Use an open DEM (e.g., SRTM/Copernicus DEM).  
   - Derive slope, aspect, curvature rasters.  

2. **Factor Classes & Scoring**  
   - Assign LSER-style scores to terrain factors.  
   - Combine to produce Total Estimated Susceptibility Values (TESV).  

3. **Classification**  
   - Group into susceptibility zones: *Low / Moderate / High*.  

4. **Validation (Demo)**  
   - Use a small open/synthetic landslide inventory to check overlap. 

