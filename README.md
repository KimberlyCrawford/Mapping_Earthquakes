# Mapping_Earthquakes

## Overview
Creating a map with JavaScript???

### Purpose
The purpose of this project was to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. JavaScript and the D3.js library was used to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. The Leaflet library was used to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

## Data

The data for this project was taken from a URL for GeoJSON earthquake data from the USGS website. Geographical coordinates and the magnitudes of earthquakes were retrieved for the last seven days.

![filename.png](https://github.com/KimberlyCrawford/Mapping_Earthquakes/blob/main/static/images/filename.png)

## Tasks Involved in the Project

- JavaScript and the D3.js library were used to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. 
- Leaflet library was used to plot the data on a Mapbox map through an API request and created interactivity for the earthquake data.

NOTE: Mapbox provides custom maps for websites and applications such as Strava, Facebook, the Financial Times, The Weather Channel, Snapchat, and Instacart. Since October 2019, Mapbox has been generating up to 14 billion individual sensor readings daily across 100,000 map updates on connected devices.

## Challenge

The purpose of this challenge was to expand on the project completed during the module and use JavaScript and ??? to see the earthquake data in relation to the tectonic plates’ location on the earth as well as all the earthquakes with a magnitude greater than 4.5 on the map.

#### Deliverable 1: Add Tectonic Plate Data

Using your knowledge of JavaScript, Leaflet.js, and geoJSON data, tectonic plate data was added using d3.json(), the data was added using the geoJSON() layer, the tectonic plate LineString data was set to stand out on the map, and the tectonic plate data was added to the overlay object with the earthquake data.

![filename.png](https://github.com/KimberlyCrawford/Mapping_Earthquakes/blob/main/static/images/filename.png)

### Deliverable 2: Add Major Earthquake Data

Using your knowledge of JavaScript, Leaflet.js, and geoJSON data, major earthquake data was added to the map using d3.json() including color, the radius of the circle based on the magnitude of earthquake, and a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().

![filename.png](https://github.com/KimberlyCrawford/Mapping_Earthquakes/blob/main/static/images/filename.png)

### Deliverable 3: Add an Additional Map

Using your knowledge of JavaScript and Leaflet.js, a third map style was added to the earthquake map.

![filename.png](https://github.com/KimberlyCrawford/Mapping_Earthquakes/blob/main/static/images/filename.png)