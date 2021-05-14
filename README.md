# outdoor-recreation
### This is my Final Project for UEP-0239

#### This is a raster analysis that will determine the best places to live in the Boston Area, given that outdoor activities are important. By using a tree canopy raster, four other indicators will be converted into rasters, resulting in using the following five indicators to complete this analysis:

1. Tree canopy cover
2. Farmers market points
3. Bike trails
4. Blue bike stations
5. Public Department of Conservation and Recreation pools

Location Layers for Study Area
MPO Boundaries from [Mass Dot](https://geo-massdot.opendata.arcgis.com/datasets/mpo-boundaries?geometry=-75.888%2C41.541%2C-67.544%2C42.964)
ZCTA boundaries from the [Census Bureau](https://www.census.gov/cgi-bin/geo/shapefiles/)

Data Sources for Indicators
Tree Canopy Raster from the [NLCD](https://www.mrlc.gov/data/nlcd-2016-usfs-tree-canopy-cover-conus)  
Farmers Markets from [MassGIS](https://www.mass.gov/orgs/massgis-bureau-of-geographic-information)
Bike trails from [MassGIS](https://www.mass.gov/orgs/massgis-bureau-of-geographic-information)
Public pools from [MassGIS](https://www.mass.gov/orgs/massgis-bureau-of-geographic-information)
Blue bikes stations from [BlueBikes](https://www.bluebikes.com/system-data)

#### Below are some important instructions for how to run this notebook

First, it it will be important to ensure that you have miniconda or anaconda installed to run this notebook.   

Then, you can download the proper environment using the YAML file provided (called outdoor_rec.yml). To do this:

1. Open your terminal, navigate to this git directory, and type "conda env create -f outdoor_rec.yml"

2. Activate the environment by typing "conda activate outdoor_rec"

3. Verify that the new environment was installed correctly by typing "conda env list"

[Click here](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file) for more information about environments with conda. 



