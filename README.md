# Landform Evolution Analysis using GIS and Remote Sensing

## Overview

This project analyzes landform evolution and land use–land cover (LULC) changes in the region connecting Udupi to Hassan via Charmadi Ghats through Belur road. The study evaluates changes in different land cover categories between 2000 and 2020 using GIS and remote sensing techniques.

## Data Source

Satellite datasets for the study area were obtained from the USGS EarthExplorer platform.

## Methodology

The spatial data was processed and analyzed using several GIS techniques including:

* Buffering
* Layer stacking
* Mosaicking
* Clipping
* Merging

Land cover classification was performed using both **Supervised Classification** and **Unsupervised Classification** methods. The study area was classified into the following land cover categories:

* Water bodies
* Forest
* Barren land
* Urban land
* Agricultural land

An **accuracy assessment** was conducted to evaluate the reliability of the classified land cover data and verify how accurately the thematic classes represent the actual land cover.

All analysis and classification tasks were performed using the **Semi-Automatic Classification Plugin (SCP)** in QGIS.

## Results

The analysis shows that:

* Water bodies remained relatively stable over the study period.
* Agricultural land increased over time.
* Urban settlements gradually expanded between 2000 and 2020.

## Tools Used

* QGIS
* Semi-Automatic Classification Plugin (SCP)
* Remote sensing satellite data
