# USGS Earthquake Data Visualization

This project visualizes earthquake data provided by the United States Geological Survey (USGS) for the last 7 days. The data is sourced from the following GeoJSON URL: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson.

## Project Overview

The goal of this project is to create an interactive map that displays earthquake data using Leaflet.js and D3.js. The map will show markers for each earthquake, with the marker size and color representing the earthquake's magnitude and depth, respectively. Clicking on a marker will display additional information about the earthquake in a popup.

## Project Structure

index.html: Contains the HTML structure for the webpage.
style.css: Contains the CSS styles for the webpage.
logic.js: Contains the JavaScript code for fetching earthquake data, creating map features, and rendering the map.
Libraries and APIs Used
Leaflet.js: Used for creating interactive maps.
D3.js: Used for data manipulation and visualization.

## How to Run

To run the project, simply open the index.html file in a web browser. The map should load and display earthquake data based on the provided GeoJSON URL.

## Visualization Features

Markers: Each earthquake is represented by a circle marker on the map.
Marker Size: The size of the marker corresponds to the earthquake's magnitude.
Marker Color: The color of the marker represents the depth of the earthquake, with a color scale indicating different depth ranges.
Popups: Clicking on a marker will display a popup with information about the earthquake, including the location, magnitude, and depth.
Libraries: Leaflet.js, D3.js


## Data Source

United States Geological Survey (USGS)
https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php







