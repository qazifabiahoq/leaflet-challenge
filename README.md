# USGS Earthquake Data Visualization

---

## Project Description

This project visualizes real-time earthquake data from the United States Geological Survey (USGS) for the past seven days. It presents an interactive map where each earthquake is marked, allowing users to explore recent seismic activity globally with intuitive visual cues.

---

## Purpose and Audience

The visualization is designed for geologists, emergency responders, educators, and the general public interested in monitoring earthquake occurrences. It provides an accessible way to analyze earthquake magnitude and depth distribution through a dynamic, user-friendly map interface.

---

## Dataset Overview

Earthquake data is fetched live from the USGS GeoJSON feed for all earthquakes worldwide over the past week. Each record includes information such as geographic coordinates, magnitude, depth, and location description.

---

## Technologies and Methodology

* **Leaflet.js:** For rendering the interactive map and managing map layers and markers.
* **D3.js:** For data fetching, manipulation, and applying color scales corresponding to earthquake depth.
* **GeoJSON Data:** Real-time earthquake data sourced from USGS: [USGS Earthquake GeoJSON Feeds](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php).

The project workflow involves fetching the GeoJSON data, parsing each earthquake record, and placing circle markers on the map. Marker sizes scale proportionally with earthquake magnitude, and colors represent earthquake depth using a gradient color scale. Clicking markers triggers popups with detailed earthquake information.

---

## Key Features

* **Interactive Map:** Pan and zoom to explore earthquake locations globally.
* **Scaled Markers:** Circle size increases with earthquake magnitude for easy visual impact.
* **Depth Color Coding:** Markers are color-coded by depth, allowing quick identification of shallow versus deep earthquakes.
* **Informative Popups:** Clicking a marker reveals earthquake details including location, magnitude, and depth.

---

## How to Use

1. Clone or download the project files.
2. Open `index.html` in any modern web browser.
3. The map loads automatically, displaying earthquake markers for the last 7 days.
4. Click on any marker to view detailed information about that earthquake.

---

## Project File Structure

* **index.html:** HTML layout of the webpage.
* **style.css:** Styling for the webpage elements.
* **logic.js:** JavaScript code handling data fetching, map rendering, and visualization logic.

---

## Data Source

United States Geological Survey (USGS)
GeoJSON Earthquake Feed: [https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all\_week.geojson](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)

---

## Conclusion

The USGS Earthquake Data Visualization project provides a practical and interactive tool for exploring recent seismic activity worldwide. By integrating real-time data with intuitive mapping, the project helps users understand earthquake patterns by magnitude and depth in a visually engaging manner.

---

If you would like, I can also help you format this as a README file or prepare a project summary for your portfolio!
