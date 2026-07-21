# Pluto Bladed Terrain Morphology Dataset

## Overview

This repository contains the geospatial data, morphometric measurements, and ONDINE outputs used to characterize the morphology and spatial organization of Pluto's Bladed Terrain Deposits (BTDs).

The dataset accompanies the study:

> Belissa, V. *et al.* **[Manuscript title]**. *[Journal]* ([Year]). [DOI]

The repository is divided into three independent data categories:

1. geospatial vector data distributed as ESRI Shapefiles;
2. measurements and derived quantities stored in Excel workbooks;
3. results exported from ONDINE.

## Repository structure

```text
.
├── shapefiles/
│   ├── [geospatial_dataset_1].shp
│   ├── [geospatial_dataset_1].shx
│   ├── [geospatial_dataset_1].dbf
│   ├── [geospatial_dataset_1].prj
│   └── ...
│
├── measurements/
│   ├── [measurement_table_1].xlsx
│   └── ...
│
├── ondine_results/
│   ├── [ondine_output_1].[extension]
│   └── ...
│
├── LICENSE
└── README.md
```

## Data description

### 1. Shapefiles

The `shapefiles/` directory contains the vector layers used for the spatial and morphological analysis of the BTDs. These layers may include mapped landform boundaries, blade axes, measurement profiles, study areas, and other geometries used in the analysis.
