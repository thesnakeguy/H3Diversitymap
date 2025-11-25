# Quarto Document for H3 Diversity Plotting
This Quarto document and accompanying R script provide a reproducible workflow for visualizing species diversity using H3 hexagonal cells. It processes species occurrence data from a tab-delimited .txt file, calculates various diversity metrics, and generates a map in either an interactive HTML or a static PNG format.

***

### Features
* Flexible Input: Reads species occurrence data from a specified .txt file (longitude, latitude and species should be present) as outputted by GBIF and OBIS

* H3 Hexagon Integration: Utilizes the H3 geospatial indexing system to discretize the map into hexagons of a chosen resolution.

* Multiple Diversity Metrics: Calculates and plots a range of diversity indices, including species richness, Shannon diversity, Simpson diversity, and Hill numbers.

### Two Output Options:

* Interactive HTML: Creates a dynamic, zoomable map using leaflet with OpenStreetMap base layer. Ideal for web-based sharing.

* Static PNG: Generates a high-resolution image using ggplot2, suitable for publications or presentations.

**Customizable Map Backgrounds**: For PNG output, you can choose between an OpenStreetMap base layer or country borders.

<img width="3200" height="2400" alt="H3Hexagons_res5 7_richness" src="https://github.com/user-attachments/assets/f263edee-edcb-49e6-93e7-da1ceaa26868" />



More info: 
- https://github.com/marinebon/obisindicators
- https://iobis.github.io/notebook-diversity-indicators
