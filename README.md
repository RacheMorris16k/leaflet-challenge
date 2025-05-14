# leaflet-challenge
This project uses **Leaflet.js**, **D3.js**, and **GeoJSON** data from the USGS to visualize earthquakes across the globe. Users can view recent seismic activity on an interactive map with color- and size-coded markers, a depth legend, and multiple map layers.

## Features

- Interactive map using Leaflet
- Earthquake data pulled from USGS GeoJSON Feed (updated every 5 minutes)
- Markers scale by magnitude and color by depth
- Popups for each earthquake showing:
  - Magnitude
  - Depth
  - Location
- Depth legend for color reference
- Tectonic plate boundaries overlay (optional)
- Layer control to toggle base maps and overlays

## Technologies Used

- [Leaflet.js](https://leafletjs.com/)
- [D3.js](https://d3js.org/)
- [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)
- HTML, CSS, and JavaScript

## Setup Instructions

1. Clone or download this repo.
2. Open the project folder in **Visual Studio Code**.
3. Install the **Live Server** extension if you don’t already have it.
4. Right-click `index.html` and select **"Open with Live Server"**.
5. Explore the earthquake map in your browser.

## File Structure
leaflet-challenge/
│
├── index.html # Main HTML file
├── static/
│ ├── css/
│ │ └── style.css # Custom styles
│ └── js/
│ └── logic.js # Earthquake + tectonic plate visualization
└── README.md # You're here!

## Sources

- Earthquake Data: [USGS Earthquake Hazards Program](https://earthquake.usgs.gov)
- Tectonic Plates GeoJSON: [Fraxen's GitHub Repo](https://github.com/fraxen/tectonicplates)

## Author

Created by Rache Morris for a UCI Coding Bootcamp Module 15 Challenge.

---


