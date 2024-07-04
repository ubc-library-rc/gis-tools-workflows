---
layout: default
title: Geospatial Data
nav_order: 2
parent: Project Setup
---
# Geospatial Data

A Geographic Information System (GIS) such as QGIS works with data that is tied to a location on Earth. This type of data is often referred to as GIS data, or geospatial data, and is spatially referenced to Earth using location information – most commonly geographic coordinates. A GIS uses this location information to project a geospatial file into a virtual geographic space where it can then be visualized and analyzed.

Geospatial data is often referred to as having two main types: **raster** and **vector**. **Raster data** is data which is made up of pixels arranged in a grid, whereas **vector data** is made up of vertices and the paths between them – creating geometries that represent real-world features or phenomena. In other words, a vector data layer will be made up of either points, lines, or polygons. 
![vector map](./images/vector-map.png)

![raster map](./images/raster-map.png)
   
A third type of spatial data is **tabular data**. Tabular data are data formatted into a table by rows and columns. If the tabular dataset has columns referring to geometry such as latitude and longitude, then the dataset can be displayed in the virtual geographic space of a GIS. 


# Finding Data
The data you'll need depends on your mapping objectives. Maybe you already have data. Maybe you want to create a reference map and all you need is contextual information and the ability to add some labels and markers. Perhaps your research lab is collecting and processing the data as part of the investigative project. Whether your area of interest is local or global, whether your final map will be static, interactive, or simply the results of some spatial analysis — these factors will influence where you look for data. Municipal and federal data repositories are a good place to begin looking for geospatial data. If you have access to a data repository, either through a group you’re working with/for or institutional library for example, reaching out to whoever coordinates on the matter can be useful. You can also begin with a web search and see what is returned. Lastly, in some cases you can make your own data. This is particularly true if you only need a reference point or simple boundary outline. Today's workshop will focus on municipal data repositories to practice searching and downloading data. 


## Some Considerations 
Whether you’re performing spatial analysis or making maps for yourself or a client, its important to keep a record of your data sources as you work. You’ll figure out a system that make sense to you. Trial and error a few times. However, The following considerations are useful to note somewhere like a document or notes file as you go.

```
- What is the dataset of and where did you download it from (save a link)
- What is the downloaded file called? Where is it stored on your computer/external storage device?
- Is there a visual data preview such as an interactive web map?
- What attributes are included in the dataset? 
- Who is the dataset published by and is there a contact for questions? 
- What is the dataset's license?
- When was it last updated?
- What formats can the dataset be downloaded in? 
- What projections can the dataset be downloaded in? 
```

---
#### Resources
- [Some useful sites to look for data](https://ubc-library-rc.github.io/qgis-knowledge-base/content/finding-data.html)
- [Managing your data sources in QGIS](https://docs.qgis.org/3.34/en/docs/user_manual/managing_data_source/index.html)
- [Types of geospatial data](https://www.geographyrealm.com/geodatabases-explored-vector-and-raster-data/)
- [Advanced data management](https://gistbok.ucgis.org/knowledge-area/data-management)
- [Using spatial databases in QGIS](https://docs.qgis.org/3.34/en/docs/training_manual/databases/index.html)