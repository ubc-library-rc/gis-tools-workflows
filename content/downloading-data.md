---
layout: default
title: Downloading Data
nav_order: 3
parent: Project Setup
---

# Downloading Data

While the workshop folder you downloaded contains some prepared data for Vancouver, knowing how to search for geospatial data and download it from the web is an important skill to have. Therefore, this page will guide you through downloading different kinds of geospatial data from municipal repositories. If you haven't already:
<!-- Today’s workshop will focus on municipal data repositories to practice searching and downloading data. This page will demonstrate downloading a dataset of public parks from Calgary's open data portal, then guide you through doing the same for Vancouver and one other city of your choice. You will also download Vancouver Business Licenses and an aerial image for a portion of Vancouver.  -->

[Download Workshop Data](./qgis-workshop.zip){: .btn .btn-blue }

## Example: Downloading Parks from Calgary's [Open Data Portal](https://data.calgary.ca/browse?q=parks&sortBy=relevance)
Downloading geospatial data from municipal data portals isn't always straightforward. It can be tricky to find the right buttons to press to downlaod the right file format. Remember that if there's an interactive map vizualizing geospatial data, there is likely a way to access and download the data in a spatial format (e.g., shapefile, geodatabase, or geoJSON). 

![calgary data](./images/calgaray-data_20240519.png)


![calgary parks](./images/calgary-parks-search_20240519.png)
      

![calgary parks export](./images/calgary-parks-export_20240519.png)
    

![calgary parks data source](./images/calgary-view-data-source_20240519.png)



Either geoJSON or shapefile will do. 
<!-- A geoJSON is a smaller file, and you can 
[see difference here](https://ubc-library-rc.github.io/gis-intro-leaflet/content/map-data.html) -->
![calgary parks](./images/calgary-export-geospatial-data_20240519.png)

---





# Practice 

## #1 Download Public Parks
Practice downloading geospatial data for public parks of the city of your choice. Note: The dataset might not be named simply 'parks'; it could be 'parks and open spaces'. Download the dataset in either .geoJSON or shapefile format. Make sure to **Unzip the downloaded file if needed, and move it to your workshop folder.**


[Victoria](https://opendata.victoria.ca/) <br>
[Toronto](https://open.toronto.ca/)<br>
[Kelowna](https://opendata.kelowna.ca/)<br>
[Kamloops](https://mydata-kamloops.opendata.arcgis.com/)<br>
[Calgary](https://data.calgary.ca/) <br>
[Penticton](https://open.penticton.ca/)<br>
[Halifax](https://data-hrm.hub.arcgis.com/pages/open-data-catalogue)<br>
[Edmonton](https://data.edmonton.ca/)



<!-- ## #2 Download Business Licenses 

Use the filter function on the lefthand panel to download only **Restaurants** with **Issued** licenses from all Vancouver [business licenses](https://opendata.vancouver.ca/explore/dataset/business-licences/map/?disjunctive.status&disjunctive.businesssubtype&sort=businesstype&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJsaW5lIiwiZnVuYyI6IkNPVU5UIiwieUF4aXMiOiJmZWVwYWlkIiwic2NpZW50aWZpY0Rpc3BsYXkiOnRydWUsImNvbG9yIjoiIzAyNzlCMSJ9XSwieEF4aXMiOiJmb2xkZXJ5ZWFyIiwibWF4cG9pbnRzIjoiIiwidGltZXNjYWxlIjoiIiwic29ydCI6IiIsImNvbmZpZyI6eyJkYXRhc2V0IjoiYnVzaW5lc3MtbGljZW5jZXMiLCJvcHRpb25zIjp7ImRpc2p1bmN0aXZlLnN0YXR1cyI6dHJ1ZSwiZGlzanVuY3RpdmUuYnVzaW5lc3NzdWJ0eXBlIjp0cnVlLCJzb3J0IjoiYnVzaW5lc3N0eXBlIiwicmVmaW5lLmJ1c2luZXNzdHlwZSI6IlJlc3RhdXJhbnQiLCJyZWZpbmUuc3RhdHVzIjoiSXNzdWVkIn19fV0sImRpc3BsYXlMZWdlbmQiOnRydWUsImFsaWduTW9udGgiOnRydWUsInRpbWVzY2FsZSI6IiJ9&location=12,49.24813,-123.12161). Move the downloaded file to your workshop folder. 

![download businesses](./images/export-businesses_20240607.png)
 -->


## #2 Download Aerial Imagery
Use the [interactivemap](https://opendata.vancouver.ca/explore/dataset/orthophoto-imagery-2015/map/?location=11,49.26624,-123.11794) to download the aerial imagery for 1 grid tile of Vancouver. To do so, click the tile and download the zip folder under the field `MRSID_URL`. **Unzip** the downloaded file and move it to your workshop folder. 
<!-- https://opendata.vancouver.ca/explore/dataset/orthophoto-imagery-2022/map/?location=12,49.27296,-123.12841 -->

![export orthophoto](./images/export-orthophoto_20240608.png)




Before moving on, make sure all downloaded files are unzipped and moved to your workshop data folder.
{: .note}

