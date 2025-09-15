# avian-flight-visualizer

# Motus Migration Analysis: Station Transitions and Movement Novelty

**Author:** Jill Jouret  
**Role:** Senior Data Scientist pivoting into ecological analytics  
**Project Type:** Portfolio example for conservation science applications

---

## Overview

This notebook explores migratory movement patterns of tagged birds using Motus detection data. It focuses on station-to-station transitions and quantifies movement novelty to distinguish site-faithful behavior from exploratory routes.

The project demonstrates:
- Directed graph construction for migratory pathways
- Novelty ratio analysis per individual (`tagID`)
- Interactive mapping of transitions using station coordinates
- Scientific storytelling through data visualization

---

## Methods

- **Data Source:** Motus Wildlife Tracking System  
- **Key Columns:** `tagID`, `stationName`, `previousStationName`, `latitude`, `longitude`, `travelDuration`, `travelSpeed`  
- **Tools Used:** `pandas`, `networkx`, `folium`, `matplotlib`, `seaborn`

---

## Visualizations

- Novelty ratio plots to highlight behavioral diversity
- Directed graph of station transitions  

---

## Ecological Relevance

This analysis supports conservation efforts by:
- Identifying migratory corridors and station hubs  
- Highlighting individual variation in movement behavior  
- Informing receiver placement and tagging strategies

---

## How to Run

1. Clone the repository  
2. Install dependencies from `requirements.txt`  
3. Run `motus_migration_analysis.ipynb` in Jupyter or VS Code  
4. Output map saved as `station_transitions_map.html`

---
