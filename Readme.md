# Pangeo Landsat8 Gallery Example

This repository contains a definition of the computing environment and notebook corresponding to this gallery example:
http://gallery.pangeo.io/repos/pangeo-data/landsat-8-tutorial-gallery/landsat8.html 

## Overview:

Questions:

1. How can I find, anaylize, and visualize a large set of Landsat-8 imagery on AWS?
2. How do I use xarray and dask together to efficiently work with stacks of raster images?

We will examine raster images from the Landsat-8 instrument. The Landsat program is the longest-running civilian satellite imagery program, with the first satellite launched in 1972 by the US Geological Survey. Landsat 8 is the latest satellite in this program, and was launched in 2013. Landsat observations are processed into “scenes”, each of which is approximately 183 km x 170 km, with a spatial resolution of 30 meters and a temporal resolution of 16 days. The duration of the landsat program makes it an attractive source of medium-scale imagery for land surface change analyses.

Python packages highlighted:
- [satsearch](https://github.com/sat-utils/sat-search)
- [intake-stac](https://github.com/intake/intake-stac)
- [geopandas](https://github.com/geopandas/geopandas)
- [xarray](https://github.com/pydata/xarray)
- [dask](https://github.com/dask/dask)
- [holoviz](https://holoviz.org)
