# outdoor-recreation  
### Ginger Leib
### Final Project for UEP-0239 Geospatial Programming with Python at Tufts University  

#### This is a raster analysis that will determine the best places to live in the Boston Area, given that outdoor activities are important. By using a tree canopy raster, four other indicators will be converted into rasters, resulting in using the following five indicators to complete this analysis:  

1. Tree canopy cover  
2. Farmers market points  
3. Bike trails  
4. Blue bike stations  
5. Public Department of Conservation and Recreation pools  

#### Location Layers for Study Area  
MPO Boundaries from [Mass Dot](https://geo-massdot.opendata.arcgis.com/datasets/mpo-boundaries?geometry=-75.888%2C41.541%2C-67.544%2C42.964)  
ZCTA boundaries from the [Census Bureau](https://www.census.gov/cgi-bin/geo/shapefiles/)  

#### Data Sources for Indicators  
Tree Canopy Raster from the [NLCD](https://www.mrlc.gov/data/nlcd-2016-usfs-tree-canopy-cover-conus)    
Farmers Markets from [MassGIS](https://www.mass.gov/orgs/massgis-bureau-of-geographic-information)  
Bike trails from [MassGIS](https://www.mass.gov/orgs/massgis-bureau-of-geographic-information)  
Public pools from [MassGIS](https://www.mass.gov/orgs/massgis-bureau-of-geographic-information)  
Blue bikes stations from [BlueBikes](https://www.bluebikes.com/system-data)  

#### Below are some important instructions for how to run this notebook  

First, it it will be important to ensure that you have miniconda or anaconda installed to run this notebook.     

Then, you can download the proper environment using the YAML file provided (called outdoor_rec.yml). To do this:  

1. Open your terminal, navigate to this git directory, and type ```conda env create -f outdoor_rec.yml```  

2. Activate the environment by typing ```conda activate outdoor_rec```  

3. Verify that the new environment was installed correctly by typing ```conda env list```  

4. Launch Jupyter Lab by typing ```Jupyter Lab```  

[Click here](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file) for more information about environments with conda.   

### About the environment  

The following packages are included in the environment:

**python 3** standard python library. Find out more [here](https://www.python.org/)  
**ipython 7.10** provides a rich toolkit to make the most out of the python library. Find out more [here](https://ipython.org/)  
**jupyter lab 3** will allow you to run this jupyter notebook. Find out more [here](https://jupyter.org/)   
**scipy** this package will be used to calculate Euclidean Distance for our raster analysis. Find out more [here](https://www.scipy.org/) 
**NumPy** this package will be used to reclassify our rasters. Find out more [here](https://numpy.org/)
**Pandas** helps us maniupulate and examine tabular data. Find out more [here](https://pandas.pydata.org/)
**Geopandas** helps us create and use geodataframes of our data. Find out more [here](https://geopandas.org/)
**matplotlib** helps us plot and make maps. Find out more [here](https://matplotlib.org/)
**Folium** will help us make an interactive map. Find out more [here](https://python-visualization.github.io/folium/)
**Rasterio** will help us convert our vector maps into rasters. It will also help us make a histogram. Find out more [here](https://rasterio.readthedocs.io/en/latest/)
**Rasterstats** allows us to calculate zonal statistics. Find out more [here](https://pythonhosted.org/rasterstats/)
**Contextily** will allow us to add basemaps to our maps. Find out more [here](https://contextily.readthedocs.io/en/latest/)


In addition to the links provided above describing the packages, the following resources helped me when creating this notebook:  

Environments: https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file  

Histograms using rastrio: http://patrickgray.me/open-geo-tutorial/chapter_2_indices.html  

Creating interactive maps using folium: https://docs.astraea.earth/hc/en-us/articles/360049694972-How-to-Display-Vector-Data-on-a-Base-Map-Using-Folium  

Information on reseting the index for zonal statistics: https://www.geeksforgeeks.org/python-pandas-dataframe-reset_index/  