## Overview
This project analyzes the distribution of public resources across over 350 Statistical Area Level 2 (SA2) regions in Greater Sydney using spatial data. We used PostgreSQL with the PostGIS extension to manage and query geospatial datasets, and developed a scoring system to assess how well-resourced each region is in terms of services like schools, public transport, health facilities, and polling stations.

## Objectives
Integrate and clean diverse datasets including transport stops, school zones, polling places, population, and businesses.

Store and manage spatial data using PostgreSQL and PostGIS.

Compute a "well-resourced" score for each SA2 region using z-scores and the sigmoid function.

Visualize regional scores and explore correlations with income data to highlight social and economic patterns.

Tools & Technologies
PostgreSQL + PostGIS: Spatial database management and querying

Python (Pandas, NumPy): Data cleaning, transformation, and analysis

SQL: Data integration and scoring queries

Matplotlib / Plotly: Data visualization

Jupyter Notebook: Workflow documentation and analysis

## Key Results
Computed accessibility scores for SA2 regions normalized by population and area.

Extended analysis with additional datasets (e.g., sourced via web scraping and external APIs).

Revealed clear socio-economic disparities using income correlation and geospatial visualization.

## Getting Started
Install PostgreSQL and PostGIS.

Import datasets using the provided Jupyter notebook.

Run spatial queries and scoring scripts.

View visualizations and summary tables of results.

## Authors
Raquel Kampel

Fawaz 
