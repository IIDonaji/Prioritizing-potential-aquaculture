---
editor_options: 
  markdown: 
    wrap: 72
---

# Prioritizing Potential Aquaculture on West Coast US

### **About**

In this repository you will fine a geospataila analysis identifying
optimal location for Marine Aquaculture development along the West Coast
of the United States. To determine areas more suitable for Oyster
farming and other marine aquaculture operations, we evaluated Exclusive
Economic Zones (EEZs) based on species specific Sea Surface Temperature
(SST) and Depth requirement.

#### **Objective for this assigment:**

-   Combining vector/raster data
-   Resampling raster data
-   Masking raster data
-   Map algebra
-   Creating a function

### **Repository Structure**
```
├── data
│   ├── average_annual_sst_2008.tif
│   ├── average_annual_sst_2009.tif
│   ├── average_annual_sst_2010.tif
│   ├── average_annual_sst_2011.tif
│   ├── average_annual_sst_2012.tif
│   ├── depth.tif
│   ├── wc_regions_clean.dbf
│   ├── wc_regions_clean.prj
│   ├── wc_regions_clean.shp
│   └── wc_regions_clean.shx
├── figs
├── HW4.pdf
├── HW4.qmd
├── LICENSE
├── Prioritizing-potential-aquaculture.Rproj
├── README.html
└── README.md
```
### **About Data:**

#### **Sea Surface Temperature** 
Use average annual sea surface temperature (SST) from the years 2008 to 2012 to characterize the average sea surface temperature within the region. The data was originally generated from [NOAA’s 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1.](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php)


#### **Bathymetry**
For ocean depth characterization use the [General Bathymetric Chart of the Oceans (GEBCO).3](https://www.gebco.net/data-products/gridded-bathymetry-data#area)


### **Exclusive Economic Zones** 
To designating maritime boundaries use Exclusive Economic Zones off of the west coast of US from
[Marineregions.org.](https://www.marineregions.org/eez.php)



### **Course Information**
Course Title: [EDS 223 - Geospatial Analysis & Remote Sensing](https://eds-223-geospatial.github.io/)
Term: Fall 2025
Program: [UCSB Masters in Environmental Data Science.](https://bren.ucsb.edu/masters-programs/master-environmental-data-science)
Teaching Team:

- Instructor: Annie Adams
- Teaching Assistant: Alessandra Vidal Meza
- Assignment: Homework 4 - Prioritizing Potential Aquaculture

Author: [Ixel M.](https://github.com/IIDonaji)

### References

Hall, S. J., Delaporte, A., Phillips, M. J., Beveridge, M. & O’Keefe, M.
Blue Frontiers: Managing the Environmental Costs of Aquaculture (The
WorldFish Center, Penang, Malaysia, 2011).

Gentry, R. R., Froehlich, H. E., Grimm, D., Kareiva, P., Parke, M.,
Rust, M., Gaines, S. D., & Halpern, B. S. Mapping the global potential
for marine aquaculture. Nature Ecology & Evolution, 1, 1317-1324 (2017).︎

GEBCO Compilation Group (2022) GEBCO_2022 Grid
(<doi:10.5285/e0f0bb80-ab44-2739-e053-6c86abc0289c>)
