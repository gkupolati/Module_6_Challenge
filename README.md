# Module_6_Challenge
In this challenge, the Housing Rental Analysis for San Francisco was carried out. I used the san_francisco_housing.ipynb notebook to visualise and analyse the real-estate data. Note that this assignment requires creating visualisation by using hvPlot and GeoViews. Additionally, the sfo_neighborhoods_census_data.csv file from the Resources folder into the notebook was read and a DataFrame was created for use in the analysis.

Of interest is the exploration of the geospatial relationships in the data by using interactive visualisations with hvPlot and GeoViews. The following libraries and dependencies were imported to Build an Interactive Neighbourhood Map:
import geoviews as gv
import geoviews.feature as gf
import xarray as xr
from cartopy import crs
gv.extension('bokeh', 'matplotlib')

Based on the visualisations that were created,I was able to compose a data story which examined the trend in rental income growth compare to the trend in sales prices for all the neighbourhoods across San Francisco.

Some of the initial challenges were that I forgot to install geoviews and related libraries including cartopy into my Jupyter Lab. So I had to halt my analysis to create these environments to be able to do a proper geospartial mapping.

Please note that upon uploading the san_francisco_housing.ipynb into my Github, I observed that the graphical plots and visualization mappings are missing, with only the codes and readme comments left. Please note.
