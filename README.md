# avian-flight-visualizer


## 📌 Project Overview  
This project explores migratory bird flight behavior using multi-source tracking data, including Motus detections, GPS fixes, ARGOS satellite tracks, and barometric pressure readings. The goal is to build a Python-based tool that helps visualize flight paths, estimate altitude profiles, and assess receiver network coverage — all through an interactive, user-friendly dashboard.

Whether you're a researcher, conservation planner, or just curious about avian movement, this tool offers a flexible way to explore spatial and temporal patterns in migration data.

## 🎯 Key Features  
- Interactive map of bird tracks and receiver stations  
- Altitude profile viewer derived from barometric pressure data  
- Species and tag filters for customized exploration  
- Receiver coverage analysis to identify under-monitored regions  
- Exportable reports and visual summaries for decision support

## 🧰 Tech Stack  
- **Languages**: Python (pandas, numpy, scikit-learn, matplotlib, seaborn, plotly, folium)  
- **App Framework**: Streamlit or Dash  
- **Spatial Tools**: geopy, pyproj, haversine  
- **Data Sources**: Motus Wildlife Tracking System, ARGOS, NOAA, synthetic geolocator data

## 📁 Repository Structure  
```
avian-flight-visualizer/
├── data/              # Raw, processed, and synthetic datasets
├── notebooks/         # Exploratory analysis and prototyping
├── src/               # Ingestion, analysis, visualization, and app modules
├── tests/             # Unit tests for core functions
├── docs/              # Methodology and user guide
├── requirements.txt
└── README.md
```

## 🧪 Methodology Highlights  
- Altitude estimation from barometric pressure using the hypsometric formula  
- Track interpolation and spatial joins with receiver locations  
- Visualization of movement patterns across time, space, and altitude  
- Modular design for easy integration of new species or data types

## 🚀 Getting Started  
1. Clone the repo  
2. Install dependencies: `pip install -r requirements.txt`  
3. Run the dashboard: `streamlit run src/app/dashboard.py`  
4. Explore flight paths, altitude profiles, and receiver coverage

## 📚 About the Author  
Jill Jouret is a data scientist with a background in scientific reporting, behavioral analytics, and user-facing tool development. She’s pivoting toward ecological data science and conservation-focused analytics, with a passion for building tools that make complex data accessible and actionable.


