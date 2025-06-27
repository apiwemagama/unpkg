# unpkg

South African Provinces GeoJSON
This repository contains GeoJSON files for the provinces of South Africa, suitable for mapping, analysis, and visualization.

Files
south_africa_provinces.geojson: Boundaries of all 9 South African provinces with properties (e.g., province name, ISO code).

Usage
Direct Link:

text
(https://raw.githubusercontent.com/apiwemagama/unpkg/b9dbfede97fdca0c47ec2b099dfd9cf69a90d6c8/sa_provinces.geojson)  
Integration: Use with mapping libraries like Leaflet.js, Mapbox GL JS, or Google Maps API.

Example for Leaflet.js:

js
fetch('https://raw.githubusercontent.com/apiwemagama/unpkg/b9dbfede97fdca0c47ec2b099dfd9cf69a90d6c8/sa_provinces.geojson')  
  .then(response => response.json())  
  .then(data => L.geoJSON(data).addTo(map));  
Preview: Visualize the data using geojson.io or GitHub’s built-in GeoJSON viewer.

Data Sources
Province boundaries derived from OpenStreetMap.

ISO codes aligned with South African government standards.

License
This data is free to use for any purpose (public domain). Attribution is appreciated but not required.
