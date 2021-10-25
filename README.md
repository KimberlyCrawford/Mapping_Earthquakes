# Mapping_Earthquakes

## Overview
Mapping Earthquakes with JavaScript and APIs

### Purpose
The purpose of this project was to use the Leaflet.js Application Programming Interface (API) to populate a geographical map with GeoJSON earthquake data from a URL. Each earthquake will be visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. In addition, each earthquake will have a popup marker that, when clicked, will show the magnitude of the earthquake and the location of the earthquake.

## Tasks Involved in the Project

- JavaScript and the D3.js library were used to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. 
- Leaflet library was used to plot the data on a Mapbox map through an API request and created interactivity for the earthquake data.

NOTE: Mapbox provides custom maps for websites and applications such as Strava, Facebook, the Financial Times, The Weather Channel, Snapchat, and Instacart. Since October 2019, Mapbox has been generating up to 14 billion individual sensor readings daily across 100,000 map updates on connected devices.

## Challenge

The purpose of this challenge was to expand on the project completed during the module to see the earthquake data in relation to the tectonic plates’ location on the earth as well as all the earthquakes with a magnitude greater than 4.5 on the map.

### Deliverable 1: Add Tectonic Plate Data

Using your knowledge of JavaScript, Leaflet.js, and geoJSON data, tectonic plate data was added using d3.json(), the data was added using the geoJSON() layer, the tectonic plate LineString data was set to stand out on the map, and the tectonic plate data was added to the overlay object with the earthquake data. Below is the first map with Streets view and showing Earthquakes only:

![Streets_earthquakes.png](https://github.com/KimberlyCrawford/Mapping_Earthquakes/blob/main/Streets_earthquakes.png)

### Deliverable 2: Add Major Earthquake Data

Using your knowledge of JavaScript, Leaflet.js, and geoJSON data, major earthquake data was added to the map using d3.json() including color, the radius of the circle based on the magnitude of earthquake, and a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON(). Below is the second map with Satellite view and showing Earthquakes and Tectonic Plates only:

![Satellite_earthquakes_tectonicplates.png](https://github.com/KimberlyCrawford/Mapping_Earthquakes/blob/main/Satellite_earthquakes_tectonicplates.png)

### Deliverable 3: Add an Additional Map

Using your knowledge of JavaScript and Leaflet.js, a third map style was added to the earthquake map. Below is the third map with Dark view and showing Earthquakes, Tectonic Plates and Major Earthquakes:

![Dark_all.png](https://github.com/KimberlyCrawford/Mapping_Earthquakes/blob/main/Dark_all.png)