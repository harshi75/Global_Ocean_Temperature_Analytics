# 🌊 Global Ocean Temperature Analytics

An interactive climate analytics project built using NOAA ERSST v5 ocean temperature data, Polars, Plotly, and Streamlit.

## 📌 Overview

This project analyzes long-term global ocean warming trends using NOAA's Extended Reconstructed Sea Surface Temperature (ERSST v5) dataset.

The system processes more than 33 million ocean temperature observations and provides interactive visualizations to explore climate patterns, temperature anomalies, decadal warming trends, and ocean hotspots.

## 🚀 Features

* Global Ocean Temperature Trend Analysis
* Temperature Anomaly Detection
* Decadal Warming Analysis
* Ocean Hotspot Identification
* Interactive Streamlit Dashboard
* CSV Export of Analytical Results
* High-Performance Data Processing using Polars

## 📊 Dataset

Source: NOAA ERSST v5 (Extended Reconstructed Sea Surface Temperature)

The original NetCDF dataset is not included in this repository because it exceeds GitHub's file size limits.

Download the dataset manually and place it in:

data/sst.mnmean.nc

## 🛠️ Tech Stack

* Python
* Polars
* Streamlit
* Plotly
* Xarray
* NumPy
* Matplotlib
* NOAA ERSST v5 Dataset

## 📂 Project Structure

Global_Ocean_Temperature_Analytics/

├── data/
│   └── sst.mnmean.nc (download separately)

├── dashboard.py

├── ocean_temperature_analytics.py

├── yearly_ocean_temperature.csv

├── temperature_anomalies.csv

├── decadal_ocean_temperature.csv

├── ocean_hotspots.csv

├── requirements.txt

└── README.md

## 📈 Analyses Performed

### 1. Global Ocean Temperature Trend

Analyzes long-term changes in average sea surface temperatures from 1854 to the present.

### 2. Temperature Anomaly Analysis

Calculates deviations from historical average temperatures to identify warming patterns.

### 3. Decadal Warming Analysis

Groups temperature observations by decade to study long-term climate change trends.

### 4. Ocean Hotspot Detection

Identifies regions with the highest average sea surface temperatures.

## ⚙️ Installation

Clone the repository:

git clone https://github.com/harshi75/Global_Ocean_Temperature_Analytics.git

cd Global_Ocean_Temperature_Analytics

Create a virtual environment:

python3 -m venv venv

source venv/bin/activate

Install dependencies:

pip install -r requirements.txt

## ▶️ Run Analytics Script

python ocean_temperature_analytics.py

## 🌐 Run Streamlit Dashboard

streamlit run dashboard.py


## 📷 Dashboard Highlights

* Interactive Temperature Trend Visualization
* Ocean Temperature Anomaly Charts
* Decadal Warming Analysis
* Ocean Hotspot Visualization
* Interactive Data Tables

## 🎯 Key Outcomes

* Processed 33M+ ocean temperature observations
* Built a scalable analytics pipeline using Polars
* Generated climate insights from NOAA ocean datasets
* Developed an interactive dashboard for climate exploration

## 👩‍💻 Author

Harshita Singh

B.Tech CSE (AI & ML)

Climate Analytics • Data Science • Machine Learning

