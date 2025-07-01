# 🌍 Leaflet Earthquake Visualization

## 📖 Overview

This project visualizes real-time earthquake data from the United States Geological Survey (USGS) using **Leaflet.js**. The interactive map displays the location, depth, and magnitude of recent earthquakes around the world.

This project helps illustrate geospatial patterns in seismic activity and supports USGS efforts to educate the public and decision-makers.
---

## 🔧 Technologies Used

- **Leaflet.js** for interactive maps
- **D3.js** for fetching and parsing GeoJSON data
- **HTML/CSS/JavaScript**
- **GeoJSON** USGS API:  
  [USGS All Earthquakes (Past 7 Days)](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)

---

## 📊 Features

✅ Plot of all recent global earthquakes  
✅ Circle size based on magnitude  
✅ Circle color based on earthquake depth  
✅ Popups with location, magnitude, and depth  
✅ Color-coded legend to explain depth ranges  
✅ Responsive map with Leaflet TileLayer

---

## 🎨 Depth Color Scale

| Depth Range (km) | Color     |
|------------------|-----------|
| > 90             | Dark Red  |
| 70–90            | Orange-Red|
| 50–70            | Orange    |
| 30–50            | Yellow    |
| 10–30            | Lime      |
| < 10             | Light Green |

Color is calculated using a depth-based conditional logic in `logic.js`.

---

## 🛠️ How to Run Locally

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/leaflet-challenge.git
cd leaflet-challenge/Leaflet-Part-1 ```

2.	Open the map in your browser:

Simply double-click index.html or use a local server (e.g. Live Server extension in VS Code).

---
## 👩‍💻 Author

Aditi Nankar
Geospatial & Data Visualization Enthusiast
