---
layout: default
title: 4. Add a Basemap
nav_order: 4
parent: Project Setup
---

# Add a Basemap      

A basemap is helpful to give spatial context to your data as you work. One way to add a basemap is through a plugin. [QGIS plugins](https://plugins.qgis.org/) are user developed tools that extend QGIS functionality beyond the basics. 



## Adding basemaps from web plugin
{: .no_toc}

While your out-of-the-box QGIS applicaiton will have a few basemap options under the XYZ tab of your Browser Panel, you can access way more with a plugin. [QGIS Plugins](https://plugins.qgis.org/){:target="_blank"} are user developed tools that extend QGIS functionality beyond the basics. There are two popular plugins for webmap libraries called QuickMapServices and OpenLayers. The following documentation will show you how to install the QuickMapServices plugin, add basemaps to your QGIS project, and create and export a map using one of them. 



### 1. Install Plugin
{: .no_toc}
[QGIS plugins](https://plugins.qgis.org/){:target="_blank"} are user developed tools that extend QGIS functionality beyond the basics. To access basemaps, we'll first install the QuickMapServices plugin. Click on the **Plugin** menu at the top of your screen and select **Manage and Install Plugins...**

<img src="./images/basemap1.png" style="width:80%">


In the dialogue box that opens, select **All** as a search category on the left and type "QuickMapServices" as one word. Install the NextGIS plugin and close the dialogue box.

<img src="./images/basemap2.png" style="width:80%">


<br>

### 2. Load Basemap
{: .no_toc}

Now go to the **Web** menu at the top of your screen. You should see the QuickMapServices plugin. You will see an array of basemap options. Select OpenStreetMap as your basemap. Like QGIS, [Open Street Map (OSM)](https://www.openstreetmap.org/about){:target="_blank"} is open source and user developed. 


<img src="./images/basemap3.png" style="width:100%">



> * Use the zoom tools located in the toolbar to zoom to see each basemap in detail. <img src="./images/zoom-tools.png" style="width:50%"> 
> * Hide a basemap at any time by unchecking the box beside it in the Layers panel. 
> * Remove a basemap at anytime by right clicking the layer and selecting “remove.”
> * Sometimes when you re-open a QGIS project basemaps previously loaded will turn up blank. Try right-clicking the basemap in your Layers Panel and zooming to it. Otherwise, simply re-add the basemap from the Web menu at the top of your screen.

<br>

Explore adding other basemaps as well. For instance, **Esri's satellite imagery map** is neat. 
 
Note that sometimes when you re-open a QGIS project basemaps previously loaded will turn up blank. Try right-clicking the basemap in your Layers Panel and zooming to it. Otherwise, simply re-add the basemap from the Web menu at the top of your screen.


If you cannot find the plugin "Next GIS Quick Map Services" only "Quick Map Services" or there appear not to be as many basemap options, you may be working on a prior version of QGIS. That's okay! Refer to [this page](https://ubc-library-rc.github.io/gis-reference-mapping/content/hands-on6.html){:target="_blank"} for documentation on how to add basemaps that matches your QGIS version. 
{: .note}



<br>

