

# Earthquake Clustering Analysis Using DBSCAN

## Overview
This project analyzes global earthquake data using the DBSCAN clustering algorithm to identify regions of high seismic activity. The aim is to detect spatial patterns and visualize clusters on an interactive map, with applications in earthquake risk assessment.

## Project Structure
```
earthquake-clustering
├── data/                        # Contains earthquake data files
│   ├── usgs_main.csv
│   ├── usgs_current.csv
├── notebook/
│   └── earthquake_clustering_analysis.ipynb   # Jupyter Notebook with analysis and visualization
├── README.md                    # Project overview and instructions
├── requirements.txt             # List of required Python packages

```

## Requirements
Install the required packages with:
```bash
pip install -r requirements.txt
```

## Usage
1. **Run the Notebook**: Open `notebook/earthquake_clustering_analysis.ipynb` in Jupyter Notebook.
2. **Analyze Clusters**: Follow the cells to load data, apply DBSCAN clustering, and visualize clusters on a Folium map.

## Results
The analysis reveals clusters of earthquakes along tectonic boundaries, highlighting high-activity regions and isolated events. The interactive map offers a visual representation of these patterns.

## License
This project is licensed under the MIT License.

---
