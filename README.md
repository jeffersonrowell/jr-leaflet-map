# JR Leaflet Map

An interactive map built with Leaflet.js to showcase property sites and development overlays.

## Features

✅ Toggleable basemap layers (Streets, Satellite)  
✅ Contours, Floodmap, and Sites layers from QGIS-exported GeoJSON  
✅ Clickable site markers with popup information  
✅ Future expansion: Add 3D previews in info panel or popups

## Folder structure

/jr-leaflet-map
├── index.html
├── README.md
└── geojson/
    ├── contours.geojson
    ├── floodmap.geojson
    └── sites.geojson

## Setup steps

1. Clone the repository:

git clone https://github.com/yourusername/jr-leaflet-map.git

2. Open the folder in VSCode.

3. Export your GeoJSON layers from QGIS → place them inside the `/geojson` folder.

4. Edit `index.html` to update map behavior or styling.

5. Commit + push changes:

git add .
git commit -m "Update layers and map"
git push origin main

6. Enable GitHub Pages (Settings → Pages → Source: main branch → root).

7. Access your live map at:

https://yourusername.github.io/jr-leaflet-map/

## Credits

Built with [Leaflet.js](https://leafletjs.com/)  
Basemaps from OpenStreetMap, OpenTopoMap, and others.
