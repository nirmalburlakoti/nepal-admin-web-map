# Nepal Administrative Web Map

An interactive web-based geographical visualization of Nepal's administrative boundaries, allowing users to explore and download administrative divisions from provinces to wards using dynamic, color-coded maps with OpenStreetMap and Google satellite views.

## Features

- **Interactive Map**: Explore Nepal's administrative boundaries from provinces to wards.
- **Dynamic Coloring**: Each province and its subdivisions are assigned a unique color for easy identification.
- **Multiple Basemaps**: Switch between OpenStreetMap, Google Maps, and Google Satellite views.
- **Data Fetching**: Population data for each ward is fetched from the [National Census 2021 API](https://censusapi.cbs.gov.np/) and displayed as a chart.
- **Download Data**: Download the current administrative division as a KML file.
- **Customizable**: Change the stroke color and opacity of the map layers.

## How to Use

1. **Explore the Map**:
   - The map starts at the province level.
   - Click on a province to zoom in and see its districts.
   - Click on a district to see its local levels (municipalities/rural municipalities).
   - Click on a local level to see its wards.
2. **View Population Data**:
   - When you click on a local level, a chart will appear showing the ward-wise population data for that local level.
3. **Download KML**:
   - Click the "Download KML" button to download the currently displayed administrative boundaries as a KML file.
4. **Customize Map**:
   - Use the color picker and opacity slider to change the appearance of the map layers.

## Data Sources

- **Administrative Boundaries**: The GeoJSON data for the administrative boundaries is sourced from different websites.
- **Population Data**: The population data is fetched from the [National Census 2021 API](https://censusapi.cbs.gov.np/).

## Technologies Used

- [Leaflet](https://leafletjs.com/): An open-source JavaScript library for mobile-friendly interactive maps.
- [ApexCharts](https://apexcharts.com/): A modern charting library that helps developers to create beautiful and interactive visualizations for web pages.
- [leaflet-omnivore](https://github.com/mapbox/leaflet-omnivore): A Leaflet plugin for loading and converting various geospatial data formats.
- [tokml](https://github.com/mapbox/tokml): A JavaScript library for converting GeoJSON to KML.