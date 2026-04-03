# Automated Urban Heat Island & Tree Canopy Analysis
**A Geospatial Data Science Study of Boulder, Colorado**

![Project Header](/public/images/boulder_analysis.png)

## Overview
This repository contains a technical study on the correlation between urban building density and tree canopy coverage in Boulder, CO. The project leverages **PyQGIS** and **Spatial Data Science** methodologies to identify "Heat Vulnerability Zones"—areas where high building density overlaps with low canopy coverage.

The goal is to provide an automated, reproducible pipeline for urban planners to prioritize tree-planting initiatives based on building-specific heat risk.

## Key Features
- **Automated Spatial Pipeline**: Custom PyQGIS scripts to clean messy urban datasets (Fixing Geometries) and perform proximity buffering.
- **Large-Scale Data Integration**: Processes 10,000+ building footprints and tree inventory points from the City of Boulder Open Data portal.
- **Heat Discovery Algorithm**: Intersection methodology that identifies specific structures lacking "Greenery Buffers" (30m).

## Technical Stack
- **GIS Software**: QGIS 3.x
- **Automation**: Python (PyQGIS API)
- **Spatial Operations**: Buffering, Intersection, Geometric Cleaning (Fix Geometries)
- **Visualization**: Professional Cartography using Dark Matter base maps and Emerald-to-Heat-Map gradients.

## Methodology
1. **Data Ingestion**: Importing Building Footprints (Vectory) and Tree Inventory (Point) datasets.
2. **Geometric Normalization**: Automated cleaning of self-intersecting polygons in city-scale datasets.
3. **Proximity Modeling**: Generating 30-meter radial buffers around urban forestry assets.
4. **Risk Intersection**: Spatial intersection of building footprints with canopy buffers to identify "Mitigated" vs "Vulnerable" structures.

## About the Author
I am a **Computer Science Master's Student at CU Boulder**, focused on the intersection of Data Science, AI, and Geospatial Intelligence. This project demonstrates my ability to build robust, automated geoprocessing pipelines for environmental and urban research.

---
*Note: This analysis was conducted using publicly available data from the Boulder Open Data Hub.*
