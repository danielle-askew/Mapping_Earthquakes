# Mapping_Earthquakes
For this project we are creating interactive maps using Leaflet.js library, Javascript, and HTML to retrieve earthquake information from a GeoJSON file and plot the results in a visual format.

## Overview
The purpose:
To show the differences between the magnitudes of earthquakes all over the world for the last seven days. 
Our script pulls the GeoJSON earthquake data from the USGS website. This retrieves the geographical coordinates and magnitudes of earthquakes for the last seven days. The data is then added to a map. Since the information is linked to a real-time source, the map will update as it is accessed. 
The Scripts were built using JavaScript and D3.js library. This allows it to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. Leaflet library allows us to plot the data on a Mapbox style map through an API request and made it interactive by adding visualization for different map styles, creating layers to display Tectonic plates, Earthquake magnitude and location information.

Throughout this project, we learned how to create map layers, visual customizations that included:

* Toggling between map styles (i.e. dark, streets, satellite)
* Customization of colors, lines, marker types, and sizes
* Adding popup info box
* Plotting different points, multiple points, lines, polygons
