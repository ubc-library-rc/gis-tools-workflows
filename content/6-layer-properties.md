---
layout: default
title: Layer Properties
nav_order: 3
---
# Layer Properties

> In your **Layers Panel**, zoom to the parks data you downloaded yourself. The workshop material will use Vancouver parks for demonstration. 

<img src="./images/layer1.png" style="width:100%;">


If your parks are far away from Vancouver, you might encounter some distortion of the basemap due to the project projection being ill-suited for your area of interest. That's okay. You can also play around with changing the project projection (from the status bar) to something that works for the whole world (and thus the basemap), such as `WGS_1984_Web_Mercator_Auxiliary_Sphere`.
{: .note}

<br>

> Now, control-click (right-click) your parks layer again but this time open its **Properties**. 

<img src="./images/layer2.png" style="width:50%;">

<img src="./images/layer3.png" style="width:90%;">

<br>

While today's workshop won't explore Layer Properties in detail, it's important to know how to access the [Vector Properties Dialogue](https://docs.qgis.org/3.44/en/docs/user_manual/working_with_vector/vector_properties.html#){:target="_blank"}. 


[**Information**](https://docs.qgis.org/3.44/en/docs/user_manual/working_with_vector/vector_properties.html#information-properties){:target="_blank"} and [**Source**](https://docs.qgis.org/3.44/en/docs/user_manual/working_with_vector/vector_properties.html#source-properties){:target="_blank"} will contain metadata for the layer, including the dataset's Coordinate Reference System (CRS). [**Joins**](https://docs.qgis.org/3.44/en/docs/user_manual/working_with_vector/vector_properties.html#joins-properties){:target="_blank"} is useful if, for example, you wanted to load a csv file to your QGIS project with additional descriptive data for parks but no geospatial coordinates.

<br>



## Symbology
[Symbology](https://docs.qgis.org/3.44/en/docs/user_manual/working_with_vector/vector_properties.html#symbology-properties){:target="_blank"} is where you can change how your layer is symbolized and rendered. Currently, the symbology for parks is set to **Single Symbol** meaning every park is symbolized the same. 
    
To Do
{: .label .label-green }

> Try changing the symbolization of all parks by clicking the color bar and choosing a different color from the dialogue box that opens. Click **Apply** in the lower left-hand corner of the **Layers Properties** dialogue window to see the color update on your Map Canvas. When you are content with your changes, click **OK**.


<img src="./images/layer4.png" style="width:100%;">


<br>

Note that you can also access a layer's symbology from the **Layers Panel** by selecting the layer and then clicking the symbology icon<img src="./images/symbology-icon.png" style="width:4%;"> in the Layers Panel, or by just clicking the little symbol next to a layer.



<img src="./images/save-icon.png" style="width:6%"> After adjusting your symbology, SAVE your project.

<br>


## Labels
[**Labels**](https://docs.qgis.org/3.44/en/docs/user_manual/working_with_vector/vector_properties.html#labels-properties){:target="_blank"} will assign labels to your features based on an attribute value. 

To Do
{: .label .label-green }
Add labels for the names of parks to your map. 

> From the **Labels** layer property, change `No Labels` to `Single Labels`. 

> Then assign the value to that which most plausibly contains the parks' names. 


<img src="./images/layer5.png" style="width:100%;">

<br>

> Click **Apply** and check your map canvas. This might be overwhelming. Change the labelling of parks back to `No Labels`. 


<img src="./images/layer6.png" style="width:100%;">

---
#### Resources for further exploration
- [Comprehensive descriptions for all Vector Layer Properties](https://docs.qgis.org/3.44/en/docs/user_manual/working_with_vector/vector_properties.html#){:target="_blank"}
- [Working with Vector Data in QGIS](https://docs.qgis.org/3.44/en/docs/user_manual/working_with_vector/index.html){:target="_blank"}