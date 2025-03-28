# Cyber Attack Location Analysis

## Overview
This project visualizes worldwide cyber attacks using interactive maps and dashboards. The dataset includes details like affected companies, locations, attack methods, and organization types.

## Features
- **Interactive Maps:**
  - Folium map with markers for attacks.
  - Advanced interactive map using Mapbox.
- **Dashboard with Panel:**
  - Country selection for attack filtering.
  - Dynamic Folium map updates.
- **Marker Clustering:** Improved readability of attack locations.

## Technologies Used
- Python libraries: `geopandas`, `hvplot`, `numpy`, `pandas`, `panel`, `plotly`, `folium`, `geojson`, `bokeh`
- Data: `cyberyoyo.xlsx`
- Mapbox for enhanced visuals

## Installation & Usage
1. Install dependencies:
   ```sh
   pip install geopandas hvplot numpy pandas panel plotly folium geojson bokeh
   ```
2. Run the script in Jupyter Notebook or Python.
3. Open `dashboard.html` for the interactive map.
4. Serve the dashboard with:
   ```sh
   panel serve --show script.py
   ```

## Notes
- Requires a valid Mapbox token.
- Ensure `cyberyoyo.xlsx` is in the correct path.
- Bokeh warnings may appear but do not affect functionality.

## Author
Bonilkumar Tailor

