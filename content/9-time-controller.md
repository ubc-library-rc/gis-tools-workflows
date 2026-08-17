---
layout: default
title: Time Controller 
nav_order: 1
parent: Part 2
---
# Time Controller Maps
{: .no_toc}

[Temporal Controller](https://ubc-library-rc.github.io/gis-dhsi/content/day3/temporal-controller.html){:target="_blank"} is a built-in QGIS plugin which allows you to animate your map elements over time. You can then export these images to create a `.gif` or other animation for your project.


We are going to create an animation of the development of Vancouver's Public Art installations over time using the `yearofinstallation` field. 

<br>

## Ensuring your Date Data is Formatted Properly
For the Temporal Controller plugin/tool to work, it needs to pull from a date field that has been properly formatted as date data. 

<!-- This is why, in Part 1, we set the field type to `date` when loading in the CSV data to QGIS. To double-check what data type your field is formatted in, you can go to the Public Art layer Properties, and   -->


If you are creating your own spreadsheet/CSV, try to ensure this happens when you are creating data by properly formatting the cells. However, if you are using data from elsewhere or you forgot to do so, there are ways to ensure that your date field is formatted as a date within QGIS using the Field Calculator in the Attribute Table or Properties.


## Making a Map with Temporal Controller

*1*{: .circle .circle-purple} Open the Properties box of the Historic Public Baths layer and click Manage Fields button. 

<img src="./images/fields-form.png" style="width:100%;">

Take a look at the `Date Opened` field. As you can see, it is categorized as an integer. We need to make sure it is a date to work with the [Temporal Controller](https://ubc-library-rc.github.io/gis-dhsi/content/day3/temporal-controller.html){:target="_blank"} plugin, so we are going to create a new date field for that plugin to work with.

<br>

*2*{: .circle .circle-purple} Click on the Pencil in the upper right corner to Toggle Editing, and then select the Field Calculator (the Abacus looking button).

<img src="./images/edit-icon.png" style="width:30%;">
<img src="./images/edit-icon2.png" style="width:30%;">

<br>

*3*{: .circle .circle-purple} We are going to create an expression to create a new `Date` field for the time unit we will be using (you could also update the current field, but let’s do a new field to make sure we don’t lose any data). We are going to be using years since that is the only date data we have, but you could use any increment of time with Temporal Controller. 

In the field calculator, click “Create a new field.” As your Output field name, write “Installation_date”. As the output field type, click the drop down to select `Date`.

<img src="./images/create-field.png" style="width:100%;">


We are going to use the expression “to date”, which converts a string into a date format. You can find it under the Date and Time expression menu. Since our date is only entered as a year, we have to tell the expression that’s the output we want. 

> Write the following: ```to_date (“Date Opened” , ‘yyyy’)```

The date opened is our current field, and YYYY is the date output we want in the new field. 

> Click OK. You should see a new Date_Clean field in your attribute table. Now we can connect this data to Temporal Controller!


Make sure to click the pencil icon again to turn off editing mode for your attribute table.

<img src="./images/to-date.png" style="width:100%;">

<br>

*4*{: .circle .circle-purple} Now we are going to activate the Temporal Controller option. In your layer properties click on the Clock icon near the bottom.

> - Click Dynamic Temporal Control
> - Select Single Field with Date/Time as the configuration and keep the default Limits.
> - Select the Date_Clean field if it hasn’t already, and change the event duration to 1 year (this will make the animation go year by year; you could set it for any time interval depending on the kind of data you have).
> - Click accumulate features over time to have the features remain on the layer as they are added and as time progresses.

<img src="./images/TemporalController5.png" style="width:100%;">

<br>

*5*{: .circle .circle-purple} To create the animation, we need to open the Temporal Controller Panel. You can select it in the project toolbar, by looking for the Clock Icon.

<img src="./images/TemporalController6.png" style="width:100%;">

<br>

*6*{: .circle .circle-purple} Once you have the panel opened, click on the third button (clock with a triangle) to activate the animation. Then change the dates to the slightly before and after the earliest and latest Installation years of public art (1901 to 2026).


<img src="./images/TemporalController7.png" style="width:100%;">

<br>

> Finally, hit play and see what happens!

> Be sure to change Step to 1 Year or even 5 Years - otherwise you will be waiting for a long time. 


![gif](./images/time-controller-demo.gif)





<br>



*7*{: .circle .circle-purple} We might also want to add a date label on our animation so people can tell the time period as it changes. We can create a label with the Title decoration element. Go to the View menu then select Decorations, then Title Label.

<img src="./images/title-label.png" style="width:100%;">

> Click the Enable Title Label Checkbox.

<img src="./images/edit-title-label.png" style="width:70%;">

<br>

We are going to create an expression to display the year associated with the points coming up in the animation and to format the date. 

> Click Insert an Expression, then insert the following expression: `format_date (@map_start_time , 'yyyy')` (The quotes around the yyyy must be straight single quotes.)

This tells QGIS to display the date as the timestamp of the current time slice being displayed. Click OK.

> - Now we should modify our label display so it is readable. On the background, select white. On font, select 30 for the size, and black for the text color and semi-transparent white for the background color. 
> - For placement, select Top Center. This should make the date appear in the top center as time progresses.

<img src="./images/title-label-edited.png" style="width:70%;">

<img src="./images/temporal-controller-title.png" style="width:100%;">





<br>

*8*{: .circle .circle-purple} To export your animation, you will click the save icon on the Time Controller Panel. This will download a series of png images which you can then knit together into a gif using something like [Ezgif](https://ezgif.com/maker){:target="_blank"}. 









