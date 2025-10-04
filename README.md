🚗 US Road Accidents Analysis (2016-2023)
📖 Table of Contents
Project Overview

Purpose

Features

Technology Stack

Project Structure

Installation & Setup

Usage Guide

Analysis Components

Key Findings

Data Processing

Contributing

Known Limitations

License

Team

Acknowledgements

Project Overview
A detailed data science project analyzing US road accident data from 2016 to 2023, utilizing a comprehensive dataset of over 7 million records. The project applies advanced analytics and visualization techniques to discover patterns affecting road safety and accident severity, ultimately aiming to inform solutions for risk reduction.

Purpose
Identify key accident patterns and risk factors

Support data-driven initiatives for road safety

Provide actionable insights for traffic management and policy

Aid researchers, policymakers, and agencies in making evidence-based decisions

Features
Core Analysis Components
Univariate and bivariate analyses of accident factors

Geospatial hotspot mapping of accident-prone areas

Temporal and seasonal pattern analysis

Weather and infrastructure impact evaluation

Correlation and multivariate pattern discovery

Visualization Capabilities
Heatmaps and correlation matrices

Geographic accident plotting with maps

Distribution and trend line charts

Interactive time series visualizations

Technology Stack
Core Technologies
Python 3.x

Jupyter Notebooks

Key Libraries
Pandas, NumPy — data manipulation

Matplotlib, Seaborn — visualization

Folium, GeoPandas, Shapely — geospatial data and mapping

Kaggle API — dataset access

Project Structure
EDA Overview: Initial exploration and data quality checks

Univariate Analysis: Variable distribution and frequency analysis

Bivariate Analysis: Relationships between variables (e.g., severity, weather)

Multivariate Analysis: Complex variable interactions and PCA

Geospatial Analysis: Mapping accident hotspots and density

Hypothesis Testing: Statistical tests on weather, time, and infrastructure effects

Installation & Setup
Clone the repository

Download the dataset from Kaggle

Install required packages:

text
pip install pandas numpy matplotlib seaborn folium geopandas
Update dataset paths in notebooks as needed

Run notebooks in order for complete analysis

Usage Guide
Detailed instructions on running analysis notebooks and generating visualizations for exploring US road accident data.

Key Findings
Weather Impact
Poor visibility and precipitation correlate with higher accident severity

Rain and fog increase risk of severe accidents

Clear weather has the most accidents but typically lower severity

Infrastructure Effects
Traffic signals and crossings influence accident severity and frequency

Urban areas show concentrated accident hotspots

Temporal Patterns
Peak accident times align with rush hours

Seasonal effects impact accident frequency

Data Processing
Data cleaning for missing values, duplicates, and outliers

Feature engineering: timestamp conversions, categorical coding

Comprehensive preprocessing for analysis readiness

Contributing
Contributions are welcome! Please fork, propose changes via pull requests, and open issues for major enhancements.

Known Limitations
Data coverage may miss certain accident types or regions

Some variables have missing or inconsistent entries

Results are observational, requiring further validation

License
This project is licensed under the MIT License. See LICENSE for details.
