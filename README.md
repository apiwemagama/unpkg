# South African Provinces GeoJSON
This repository contains GeoJSON files for the provinces of South Africa, suitable for mapping, analysis, and visualization.

## 📂 Files
- south_africa_provinces.geojson: Boundaries of all 9 South African provinces with properties (e.g., province name, ISO code).

## 🛠️ Usage
1. Direct Link:

text
https://raw.githubusercontent.com/apiwemagama/unpkg/b9dbfede97fdca0c47ec2b099dfd9cf69a90d6c8/sa_provinces.geojson

2. Integration: Use with:

Leaflet.js:

js
fetch('https://raw.githubusercontent.com/apiwemagama/unpkg/b9dbfede97fdca0c47ec2b099dfd9cf69a90d6c8/sa_provinces.geojson')  
  .then(response => response.json())  
  .then(data => L.geoJSON(data).addTo(map));  
Mapbox/Google Maps: Load via their respective GeoJSON methods.

3. Preview:

Drag-and-drop the file into geojson.io.

GitHub’s built-in viewer (click the file).

## 📊 Data Sources

- Province boundaries: Derived from OpenStreetMap (simplified for clarity).
- ISO codes: Matched with South African government standards.

## 📜 License

Public Domain: No restrictions—use freely for any purpose (credit appreciated but not required).
