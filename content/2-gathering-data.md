---
layout: default
title: 1. Gathering data
nav_order: 1
parent: Project Setup
---

# Assembling Data
For this workshop, a handful of vector datasets of Vancouver have been provided for you. However, in the real world data will seldom be neatly prepared for you. Rather, you'll likely need to search for and download data from various web sources. For this reason, today's workshop will guide you through downloading vector data on city parks from a municipal data portal of your choice.  

----


## Given Data
Inside the `qgis-tools-workshop/data` subfolder you should see the following files, along with their associated 'sidecar files':

- `van-parks.shp`, Vancouver's [parks](https://opendata.vancouver.ca/explore/dataset/parks-polygon-representation/information/){:target="_blank"} as represented by polygons 
- `burnaby-parks.shp`, Burnaby's [parks](https://data.burnaby.ca/search?tags=parks%2520%2526%2520trails)
- `local-area-boundaries.shp`, neighborhood areas designated by the city of vancouver
- `public-art.csv`, public art for the City of Vancouver
- `public-art-artists.csv`, the artists behind public art for the City of Vancouver
- `cultural-spaces.geojson`, cultural spaces of the City of Vancouver
- `census-tracts.shp`, census tracts for the city of vancouver


<br>


## Practice downloading data... 
We'll practice downloading parks data from a municipal open data portal of your choice. The following demonstration will be for the City of Burnaby. 


Downloading geospatial data from municipal data portals isn't always straightforward. It can be tricky to find the right buttons to press to download the right file format. Remember that if there's an interactive map visualizing geospatial data, there is likely a way to access and download the data in a spatial format (e.g., shapefile, geodatabase, or geoJSON). 

<img src="./images/demo1.png" style="width:100%">

<br>

<img src="./images/demo2.png" style="width:100%">

<br>

<img src="./images/demo3.png" style="width:100%">

<br>

<img src="./images/demo4.png" style="width:100%">



<br>

To Do
{: .label .label-green }

Practice downloading geospatial data for public parks of the city of your choice. Note: The dataset might not be named simply 'parks'; it could be 'parks and open spaces'. Download the dataset in either .geoJSON or shapefile format. Make sure to **Unzip the downloaded file if needed, and move it to your workshop folder.**

- [Burnaby](https://data.burnaby.ca/){:target="_blank"}<br>
- [Toronto](https://open.toronto.ca/){:target="_blank"}<br>
- [Victoria](https://opendata.victoria.ca/){:target="_blank"} <br>
- [Kelowna](https://opendata.kelowna.ca/){:target="_blank"}<br>
- [Kamloops](https://mydata-kamloops.opendata.arcgis.com/){:target="_blank"}<br>
- [Penticton](https://open.penticton.ca/){:target="_blank"}<br>
- [Halifax](https://data-hrm.hub.arcgis.com/pages/open-data-catalogue){:target="_blank"}<br>
- [Edmonton](https://data.edmonton.ca/){:target="_blank"}<br>
- [Montreal](https://donnees.montreal.ca/){:target="_blank"}<br>
- [Ottawa](https://open.ottawa.ca/search){:target="_blank"}<br>



Before moving on, make sure all downloaded files are unzipped and moved to your workshop data folder.
{: .warn}

