# Kerala Urban Growth Dashboard

## Overview

This dashboard visualizes urban growth in **Kerala, India**, comparing the years **2000** and **2020**.  
It uses **Leaflet.js** to display transparent PNG overlays of urban areas on top of an OpenStreetMap basemap.  
Users can toggle between the two layers to observe changes in urban settlements over two decades.

---

## Features

- Toggleable layers: **Urban 2000** and **Urban 2020**  
- Info panel on the right with Kerala details and dataset source  
- Legend for urban intensity:
  - Low → Yellow  
  - Medium → Orange  
  - High → Red  
- Clean, static dashboard suitable for demo or teaching purposes  

---

## Dataset

The urban extent datasets are derived from the **Global Human Settlement Layer (GHSL) – WUP (World Settlement Population)**.  

- Classification is based on **built-up presence** and **population density**  
- PNG overlays are exported from **QGIS** with transparency for non-urban areas  
- This ensures clean visualization on top of the basemap  

**Source:** [GHSL WUP](https://ghsl.jrc.ec.europa.eu/)  

---

## Demo

You can view a live demo of the dashboard hosted on GitHub Pages:  

**Demo URL:** [https://YOUR_USERNAME.github.io/kerala-urban-dashboard/](https://reshma-1986.github.io/kerala-urban-dashboard/)  

If you want to run locally:  

```bash
cd kerala-urban-dashboard
python -m http.server 8000


