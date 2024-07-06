---
layout: default
title: Layer Properties
nav_order: 3
---
# Layer Properties

In your **Layers Panel**, zoom to the parks data you downloaded yourself. The workshop material will use Vancouver parks for demonstration. Control-click (right-click) the layer and open its **Properties**. While today's workshop won't explore Layer Properties in detail, it's important to know how to access the [Vector Properties Dialogue](https://docs.qgis.org/3.34/en/docs/user_manual/working_with_vector/vector_properties.html#). 

<img src="./images/layer-properties_20240706.png" style="width:100%;">

    

[**Information**](https://docs.qgis.org/3.34/en/docs/user_manual/working_with_vector/vector_properties.html#information-properties) and [**Source**](https://docs.qgis.org/3.34/en/docs/user_manual/working_with_vector/vector_properties.html#source-properties) will contain metadata for the layer, including the dataset's Coordinate Reference System (CRS). [**Joins**](https://docs.qgis.org/3.34/en/docs/user_manual/working_with_vector/vector_properties.html#joins-properties) is useful if, for example, you wanted to load a csv file to your QGIS project with additional descriptive data for parks but no geospatial coordinates.

### Labels
[**Labels**](https://docs.qgis.org/3.34/en/docs/user_manual/working_with_vector/vector_properties.html#labels-properties) will assign labels to your features based on an attribute value. 

To Do
{: .label .label-green }
- Add labels for the names of parks to your map. 


<img src="./images/layer-properties-labels_20240706.png" style="width:100%;">

### Symbology
[Symbology](https://docs.qgis.org/3.34/en/docs/user_manual/working_with_vector/vector_properties.html#symbology-properties) is where you can change how your layer is symbolized and rendered. Currently, the symbology for parks is set to **Single Symbol** meaning every park is symbolized the same. 
    
To Do
{: .label .label-green }
- Try changing the symbolization of all parks by clicking the color bar and choosing a different color from the dialogue box that opens. Click **Apply** in the lower left-hand corner of the **Layers Properties** dialogue window to see the color update on your Map Canvas. When you are content with your changes, click **OK**.


<img src="./images/layer-properties-symbology_20240706.png" style="width:100%;">



Note that you can also access a layer's symbology from the **Layers Panel** by selecting the layer and then clicking the symbology icon<img src="./images/symbology-icon.png" style="width:4%;">.

---
#### Resources for further exploration
- [Comprehensive descriptions for all Vector Layer Properties](https://docs.qgis.org/3.34/en/docs/user_manual/working_with_vector/vector_properties.html#)
- [Working with Vector Data in QGIS](https://docs.qgis.org/3.34/en/docs/user_manual/working_with_vector/index.html)