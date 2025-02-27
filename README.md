# Maritime Vessel Tracking System

<p align="center">
  <img src="logo.PNG" alt="Centered Image" width="50%">
</p>

## Overview
This project creates a real-time maritime vessel tracking system using AIS (Automatic Identification System) data from AISHub. The system collects, processes, and visualizes vessel movements through an interactive web interface.

## Components

### 1. Data Collection (`data_collect.py`)
- Connects to AISHub API
- Stores raw JSON responses

### 2. Data Processing (`data_enrichment.ipynb`)
- Cleans and processes AIS data
- Implements ML models for:
  - Vessel trajectory prediction
  - Vessel type classification
  - Anomaly detection

### 3. API (`api.py`)
- Flask-based REST API
- Endpoints for vessel data and statistics
- Query interface for processed data

### 4. Visualization (`Visualising.py`)
- Interactive Folium map
- Real-time vessel positions
- Route visualization

## Dependencies
- Python 3.8+
- Flask
- Folium
- Pandas
- Scikit-learn
- Requests
- Python-dotenv

## License
This project is part of academic coursework at TUAS.
