# 🌀 Flood Safety Mapping in Honolulu, Hawaii

## Overview

This project analyzes flood risk in **Honolulu County, Hawaii**, using spatial data and network analysis to identify:

- Vulnerable flood zones
- Types of buildings at risk (residential, commercial, social facilities)
- Evacuation routes using road network accessibility
- Safer zones for residents and visitors during flooding events

The goal is to provide data-driven insights for urban planning, emergency preparedness, and public awareness.

---

## 🌐 Data Sources

- [OpenStreetMap](https://www.openstreetmap.org/) — road networks and building footprints
- [FEMA Flood Zone Data](https://msc.fema.gov/portal/home) if included
- Local data sources from Hawaii state GIS (if used)

---

## 🧰 Tools & Libraries

- `osmnx`: Download and analyze street networks
- `geopandas`: Geospatial analysis and mapping
- `matplotlib`: Plotting and visualization
- `shapely`: Geometric operations
- `networkx`: Network graph algorithms

---

## 📊 Key Features

- Extract road and building data for Honolulu County
- Classify buildings by type and overlay flood zones
- Identify flood-prone vs. safe areas
- Analyze accessibility to evacuation routes
- Visualize results with custom maps

---

## 💻 How to Run

1. Install required packages:
    ```bash
    pip install geopandas osmnx shapely networkx
    ```

2. Open the notebook and run step by step.

3. Optional: If running in Google Colab, ensure your data is in Google Drive and adjust the file paths accordingly.

---

## 📝 Author

**Xiyao Song**  
[LinkedIn](https://www.linkedin.com/xiyao-song) • [Website](https://osong.me)

---

## 📌 Disclaimer

This project was originally developed for academic purposes and has been adapted for public release. All data used are open-source. No proprietary course materials are included.
