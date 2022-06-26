# Mapping_Earthquakes

## Overview of the Analysis: Visualizing Earthquake Data

An interactive map was created using JavaScript, the d3 library, and GeoJSON to visually analyze earthquake and tectonic plate data. Users can utilize this map to see the earthquake data in relation to the tectonic plates' location on the earth, as well as see all the earthquakes with a magnitude greater than 4.5.

### Tectonic Plate Data
Using d3.json(), I added the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and added the tectonic plate data to the overlay object with the earthquake data.

![Tectonic Plate Data](https://github.com/jstearns1988/Mapping_Earthquakes/blob/main/resources/tectonic%20plate%20map.png?raw=true)

### Major Earthquake Data
I implemented JavaScript, Leaflet.js, and geoJSON data to add major earthquake data to the map using d3.json(). Customizations such as color and radius size of circle markers based on the earthquake magnitude were created for a more pleasing experience for the user. Finally, popup markers for each earthquake are in place to display the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().

![Major Earthquake Data](https://github.com/jstearns1988/Mapping_Earthquakes/blob/main/resources/major%20earthquake%20data.png?raw=true)

### Additional Map
A third map style, "Dark" was added to the map using JavaScript and Leaflet.js.
![Additional Map](https://github.com/jstearns1988/Mapping_Earthquakes/blob/main/resources/dark%20map.png?raw=true)
