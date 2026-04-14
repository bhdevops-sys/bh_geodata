### BH Marine Conservation Geodata

A curated spatial data repository supporting marine conservation, fisheries management, and coastal ecosystem analysis with an aim of supporting data-driven decision-making for sustainable ocean management and conservation planning.

---
#### Overview

This repository contains geospatial layers and supporting data focused on:

Fisheries (artisanal)
Marine habitats (underwater habitats)
Conservation and protected areas
Coastal communities and livelihood data
Environmental pressures (pollution, illegal activities)

---
#### Repository Structure
├── data/
│ ├── fisheries/ # Fisheries-specific layers
│ ├── habitats/ # Marine habitat layers
│ ├── conservation/ # MPAs,LLMAs protected areas
│ └── socio_economic/ # Community and livelihood data
│
├── metadata/ # Dataset descriptions and sources
├── scripts/ # Data processing and analysis scripts
├── notebooks/ # Jupyter notebooks for exploration
├── outputs/ # Maps, figures, and analysis outputs
└── README.md # Project documentation

---
#### Fisheries Layers

The repository includes multiple fisheries-related geospatial layers:

1. Fishing Effort
   - Artisanal fishing grounds
2. Landing Sites
   - Fish landing sites
3. Gear Types
Spatial distribution of fishing gears:
   - Gillnets
   - Longlines
   - Traps
   - Monofilaments
4. Catch Data (Spatialized)
Species distribution by catch
Catch per unit effort (CPUE)
6. Illegal, Unreported, and Unregulated (IUU) Indicators
Reported hotspots
Enforcement patrol zones

---
#### Habitat Layers
Mangrove extent and density
Coral reef distribution and health status
Seagrass beds
Coastal land cover classifications

---
#### Conservation Layers
Marine Protected Areas (MPAs)
Locally Managed Marine Areas (LMMAs)
Restricted fishing zones
Biodiversity hotspots

---
#### Socio-Economic Layers
Coastal community locations
Livelihood activities (fishing, farming, tourism)
Infrastructure (markets, roads, landing sites)

---
#### Data Formats

Supported formats:
   - GeoJSON (.geojson)
   - Raster formats (.png, .jpeg, .tif)

---
#### Usage
Tools
You can use the data with:
 - QGIS / ArcGIS
 - Python (GeoPandas, Rasterio)
 - Google Earth Engine
 - R (sf, raster)

**** Example Python
```python
import geopandas as gpd

# Load fisheries layer
fishing_zones = gpd.read_file("data/fisheries/fishing_zones.geojson")

# Preview
print(fishing_zones.head())
```
---
#### Contact
For questions or collaboration:
Name: Ochieng
Email: stevemtalii@gmail.com/mtalii@baharihai.org
