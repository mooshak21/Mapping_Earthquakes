# Mapping_Earthquakes

## Overview
We are tasked to expand on our previous map creation by adding data associated with tectonic plates and major earthquakes. Using this data, we will create different overlays that a user can alternate between to visualize the data within each category.

## Deliverable 1 
Tectonic Plate Data:

Here we can see that we have taken the data from a JSON file that contains the locations for the [tectonic plates](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)

![](https://github.com/mooshak21/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Resources/Tectonic.png)

## Deliverable 2
Major Earthquake Data:

Here we have taken the json data for [major earthquakes](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson). We used a function to filter the magnitudes that provide colors for varying ranges of magnitudes. For <5 we have a green color, >=5 and <6 we have a yellow color, and for >6 we have a red color.

![](https://github.com/mooshak21/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Resources/MajorEQ.png)

## Deliverable 3
Adding a third map tile layer:

Here we added a third tile layer (dark) to add to the other tile layers we already had (satellite, streets).
As we can see both the Major Earthquake and All Earthquake overlays can be seen and displayed on the three tile layers.

**Dark**
![](https://github.com/mooshak21/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Resources/Dark.png)

**Streets**
![](https://github.com/mooshak21/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Resources/Streets.png)

**Satellite**
![](https://github.com/mooshak21/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Resources/Satellite.png)
