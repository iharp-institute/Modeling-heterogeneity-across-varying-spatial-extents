# Notebook Descriptions

This repository contains two primary Jupyter notebooks for interaction analysis and visualization.

---

## 1. interaction_multiple_paths.ipynb

### Purpose
This notebook performs the core multi-path interaction analysis between Antarctic sea ice extent and land ice (snow depth) variables.

### Functionality
- Loads sea ice concentration data (NSIDC-0051)
- Loads snow depth / ice sheet data
- Performs spatial alignment and preprocessing
- Computes interaction pathways across multiple spatial extents



## Data Sources

### Sea Ice Concentration Data (NSIDC-0051, Version 2)

This study uses the NSIDC Sea Ice Concentrations dataset.

- Dataset page:  
  https://nsidc.org/data/nsidc-0051/versions/2  

- Direct data access tool:  
  https://nsidc.org/data/data-access-tool/NSIDC-0051/versions/2  

**Instructions:**
1. Select Southern Hemisphere data.
2. Choose the required time range.
3. Download files in NetCDF (.nc) format.



---

### Snow Depth / Land Ice Data (ERA5-Land Reanalysis)

This study uses the ERA5-Land Reanalysis dataset for Snow Depth.

- Dataset page:  
  https://cds.climate.copernicus.eu/datasets/reanalysis-era5-land?tab=download  

**Instructions:**
1. Create/login to a Copernicus Climate Data Store (CDS) account.
2. Select variable: **Snow Depth**.
3. Select Antarctic region.
4. Match the time range with the sea ice dataset.
5. Download in NetCDF (.nc) format.

## Dependencies

To run this code, install the following Python packages:

- numpy
- pandas
- xarray
- netCDF4
- matplotlib
- scipy
- scikit-learn
- cartopy

You can install them using:

pip install numpy pandas xarray netCDF4 matplotlib scipy scikit-learn cartopy


