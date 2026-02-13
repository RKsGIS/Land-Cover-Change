# Land Cover Change Analysis

An interactive Streamlit dashboard for analyzing land cover change using Landsat 8 satellite imagery.


---

## Overview

This application calculates and visualizes four environmental indices to detect changes in:

- Vegetation
- Water bodies
- Urban areas
- Soil conditions

Case Study: Münster, Germany (2013–2022)

---

## Features

- Multi-temporal comparison between two years
- Interactive map visualization (Folium)
- Adjustable threshold slider
- Supports four vegetation indices:
  - NDVI – Vegetation health
  - NDWI – Water detection
  - NDBI – Built-up area detection
  - SAVI – Soil-adjusted vegetation

---

## Installation

### Prerequisites

- Python 3.8+
- Anaconda or Miniconda (recommended)

### Setup

    git clone https://github.com/RKsGIS/Land-Cover-Change.git
    cd Land-Cover-Change
    conda env create -f requirements.yml
    conda activate land-cover-change

### Run the Application

    streamlit run app.py

Open in browser:
http://localhost:8501

---

## Workflow

1. Launch the dashboard
2. Select folder for Year 1 Landsat bands (B1–B7 .tif)
3. Select folder for Year 2 Landsat bands
4. Choose a vegetation index
5. Adjust threshold
6. Explore results on the map

---

## Dataset

- Source: Google Earth Engine
- Satellite: Landsat 8 Surface Reflectance
- Resolution: 30m
- Required Bands: B1–B7

Use the provided `DataDownload_GEE.js` script to download imagery.

---

## Tech Stack

- Streamlit
- Folium
- rioxarray
- NumPy
- Matplotlib

---

## Project Structure

Land-Cover-Change/
- app.py
- DataDownload_GEE.js
- requirements.yml
- sample Landsat files/
- README.md

---




## Project Authors
- Ram Kumar Muthusamy
- Mohamed Shamsudeen


This project was developed as part of a Spatio-Temporal Analysis course at the University of Münster.
