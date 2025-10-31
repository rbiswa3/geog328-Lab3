# geog328-Lab3 
# Geospatial Data Visualization

An interactive web map application for visualizing multiple GeoJSON datasets using Mapbox GL JS.

## Project Description

This project demonstrates asynchronous GeoJSON data loading and visualization techniques in web GIS. It features:

- **Multiple GeoJSON Datasets**: Display and interact with two or more geospatial datasets simultaneously
- **Interactive Map**: Built with Mapbox GL JS with satellite imagery as the base layer
- **Data Table**: Dynamic table showing dataset properties with sorting capabilities
- **Responsive Design**: Side panel with data controls that adapts to different screen sizes
- **Layer Toggle**: Show/hide individual datasets on the map
- **Sortable Table**: Sort data by values for easy analysis

## Features

✓ Loads 2+ GeoJSON datasets asynchronously  
✓ Interactive map with satellite base layer (different from earthquake example)  
✓ Full-screen map with hovering side panel  
✓ Responsive design (side panel hides on screens < 1024px width)  
✓ Table data display with sorting functionality  
✓ Layer visibility toggle controls  
✓ Well-organized file structure  
✓ Cross-browser compatible   

## File Structure

```
repo-name/
├── index.html           # Main application page
├── earthquake.html      # Reference example from tutorial
├── readme.md           # Project documentation
└── assets/
    ├── data1.geojson   # First GeoJSON dataset (points)
    ├── data2.geojson   # Second GeoJSON dataset (polygons/lines)
    ├── earthquakes.geojson  # Reference data
    └── japan.json      # Reference data
```

## Setup Instructions

### Prerequisites
- Mapbox account with access token ([Sign up](https://www.mapbox.com/))
- Text editor (VS Code, Sublime Text, etc.)
- GitHub account
- Git installed

### Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/[your-username]/[repo-name].git
   cd [repo-name]
   ```

2. **Add your Mapbox token**
   - Open `index.html` and `earthquake.html`
   - Replace `YOUR_MAPBOX_ACCESS_TOKEN_HERE` with your actual Mapbox access token
   - Get your token: https://account.mapbox.com/tokens/

3. **Prepare GeoJSON data**
   - Create or download two GeoJSON datasets
   - Place them in the `assets/` folder as `data1.geojson` and `data2.geojson`
   - Each file should be < 2MB in size
   - Validate on [geojson.io](https://geojson.io)
